Test case id | Priority | Description | Version
---|---|---|---
LoginFunc06.3 | `high` | Verify login functionality whith unformatted phone number| `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* phone number: 629999999999

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Select login option phone number
3. Select the country Brazil
4. Enter the phone number id provided in the "test data" section
5. Click outside the text field

### Expected Results
1. Button "Continuar" should remain disabled
2. System should present the error highlighting the field or with a error message
