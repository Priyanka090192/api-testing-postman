GET /products API

Purpose: Fetch list of products

Test Steps:

Send GET request to /products

Validate status code = 200

Validate JSON schema includes id, name, price, category

Validate response time < 500ms

POST /order API

Purpose: Place a new order

Test Steps:

Send POST request with JSON body (user_id, product_id, quantity)

Validate status code = 201

Validate response contains order confirmation

Validate negative scenario: invalid product_id → error 400
