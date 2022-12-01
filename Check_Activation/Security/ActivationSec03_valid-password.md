Test case id | Priority | Description | Version
---|---|---|---
ActivationSec03 | `critical` | Verify login functionality when a valid password is provided| `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* activation code: 123456789123
* password: aA123456

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Click on "Eu tenho um código"
3. Enter the activation code provided in the "test data" section
4. Click on "Continuar"
5. Enter password provided in the "test data" section

### Expected Results
1. Button "Ativar" should remain disabled
2. System should present the password strength
