Test case id | Priority | Description | Version
---|---|---|---
LoginFunc05 | `high` | Verify login functionality whith blank phone number| `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* phone number: blank

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Select login option phone number
3. Click on the text field
4. Click outside the text field

### Expected Results
1. Button "Continuar" should remain disabled
2. System should present the error highlighting the field or with a error message
