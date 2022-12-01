Test case id | Priority | Description | Version
---|---|---|---
ActivationFunc06.5 | `high` | Verify login functionality whith unformatted e-mail| `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* activation code: 123456789123
* e-mail id: ana@ana.c

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Click on "Eu tenho um código"
3. Enter the activation code provided in the "test data" section
4. Click on "Continuar"
5. Enter the e-mail provided in the "test data" section
6. Click outside the text field

### Expected Results
1. Button "Continuar" should remain disabled
2. System should present the error highlighting the field or with a error message
