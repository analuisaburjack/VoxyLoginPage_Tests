Test case id | Priority | Description | Version
---|---|---|---
ActivationSec01 | `high` | Verify activation security while not allowing to copypaste the password confirmation | `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* activation code: 123456789123
* password: 12345678aA

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Click on "Eu tenho um código"
3. Enter the activation code provided in the "test data" section
4. Click on "Continuar"
5. Enter the password provided in the "test data" section
6. Copy password
7. Try to paste the password in the password confirmation field

### Expected Results
1. The password confirmation field should remain blank
