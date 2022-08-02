# For-Petstore

# User

## POST https://petstore.swagger.io/v2/user

1. Check that http:// protocol is unsupported
2. Check that correct request returns status code 200
3. Сheck that request returns correct response body
4. Check that request returns correct response headers
5. Check that response field names are as expected
6. Check that response field types are as expected
7. Check that response field values are as expected
8. Check that response non-nullable fields are not null
9. Check that response time is less than 250ms
10. Check that request with missing required parameters returns error response
11. Check that request with invalid parameter value returns error response
12. Check that request with empty parameter value returns error response
13. Check that request with invalid parameter types returns error response
14. Check that request with boundary values is validated correctly
15. Check that request with invalid values in headers returns error response
16. Check that request with unsupported method returns error response
17. Check that request with huge json in request body returns error response
18. Check that request with empty request body returns error response
19. Check all supported response status codes

## DELETE https://petstore.swagger.io/v2/user/{username}

1. Check that http:// protocol is unsupported
2. Check that correct request returns status code 200
3. Сheck that request returns correct response body
4. Check that request returns correct response headers
5. Check that response field names are as expected
6. Check that response field types are as expected
7. Check that response field values are as expected
8. Check that response non-nullable fields are not null
9. Check that response time is less than 250ms
10. Check that request with non-existent in base {username} value returns error response
11. Check that request with alredy deleted user {username} value returns error response
12. Check that request realy delete user-data from DB
13. Check that request with unsupported method returns error response
14. Check all supported response status codes

