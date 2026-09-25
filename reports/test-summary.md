# Test Execution Summary

## Project
API Testing with Postman

## API
JSONPlaceholder

## Test Execution

| Metric | Result |
|---|---:|
| Requests Executed | 7 |
| Tests Passed | 35 |
| Tests Failed | 0 |
| Execution Status | PASS |

## Test Scenarios

| Test ID | Method | Endpoint | Expected Status | Result |
|---|---|---|---:|---|
| TC001 | GET | `/posts` | 200 | PASS |
| TC002 | GET | `/posts/1` | 200 | PASS |
| TC003 | POST | `/posts` | 201 | PASS |
| TC004 | PUT | `/posts/1` | 200 | PASS |
| TC005 | PATCH | `/posts/1` | 200 | PASS |
| TC006 | DELETE | `/posts/1` | 200 | PASS |
| TC007 | GET | `/posts/9999` | 404 | PASS |

## Validation Coverage

- HTTP status code validation
- Response body validation
- Required field validation
- Response header validation
- Content-Type validation
- Response time validation
- Positive test scenarios
- Negative test scenario
- Automated Postman test scripts
- Collection-level test execution

## Performance Requirement

Response-time assertions use a threshold of **less than 2000 ms**.

The threshold was selected to account for network latency when testing a publicly hosted API.

## Final Result

**35 automated assertions passed with 0 failures.**