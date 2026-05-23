# TASK 2 — API Testing using Postman

## Objective
Validate a REST API response using Postman.

## Tool Used
- Postman

## API Endpoint
GET https://jsonplaceholder.typicode.com/posts/1

## Test Case
Verified that the response status code is 200.

## Test Script Used
```javascript
pm.test("Status code is 200", function () {
    pm.response.to.have.status(200);
});
