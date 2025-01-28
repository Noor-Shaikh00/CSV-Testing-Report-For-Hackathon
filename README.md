# CSV-Testing-Report-For-Hackathon

## Test Cases

Below is the list of test cases for the application:

| Test Case ID | Description               | Steps                                      | Expected Result          | Actual Result            | Status  | Remarks               |
|--------------|---------------------------|--------------------------------------------|--------------------------|--------------------------|---------|-----------------------|
| TC001        | Validate product listing  | Open product page > verify products        | Products displayed       | Products displayed       | Passed  | No issues found       |
| TC002        | Test API error handling   | Discount API > Refresh page                | Show fallback message    | Fallback message shown   | Passed  | Handled gracefully    |
| TC003        | Check cart functionality  | Add item to cart > verify cart             | Cart updates correctly   | Cart updates correctly   | Passed  | Works as expected     |
| TC004        | Test responsiveness layout| Resize window layout > browser check       | Layout adjusts properly  | Layout adjusts properly  | Passed  | Responsive verified   |
