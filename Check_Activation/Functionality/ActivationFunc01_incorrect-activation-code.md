Test case id | Priority | Description | Version
---|---|---|---
AF01 | `high` | Verify login functionality whith incorrect activation code| `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* activation code: 555555555555555

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Click on "Eu tenho um código"
3. Enter the activation code provided in the "test data" section

### Expected Results
1. Button "Continuar" should remain disabled
2. System should present the error highlighting the field or with a error message
