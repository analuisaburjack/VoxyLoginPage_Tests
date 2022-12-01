Test case id | Priority | Description | Version
---|---|---|---
ActivationFunc04 | `critical` | Verify activation functionality whith invalid activation code | `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* activation code: 123456789123
* e-mail id: [insert here valid e-mail id]
* name: Ana
* surname: Burjack
* country: Brazil
* phone number: 62999999999
* native language: Português
* password: 12345678aA
* confirm password: 12345678aA

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Click on "Eu tenho um código"
3. Enter the activation code provided in the "test data" section
4. Click on "Continuar"
5. Enter informations provided by the "test data" section
6. Click on "Ativar"

### Expected Results
1. User should be presented with a warning that the activation code is invalid and request a correction
2. System should present only the option to try again
3. User should not be able to access the platform
