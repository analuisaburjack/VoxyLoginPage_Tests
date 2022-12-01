Test case id | Priority | Description | Version
---|---|---|---
LoginFunc04.2 | `high` | Verify login functionality whith unformatted e-mail| `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* e-mail id: ana@

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Select login option e-mail
3. Enter the e-mail id provided in the "test data" section
4. Click outside the text field

### Expected Results
1. Button "Continuar" should remain disabled
2. System should present the error highlighting the field or with a error message
