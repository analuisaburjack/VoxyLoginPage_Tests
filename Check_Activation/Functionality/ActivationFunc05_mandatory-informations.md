Test case id | Priority | Description | Version
---|---|---|---
ActivationFunc05 | `critical` | Verify login functionality when no mandatory information is provided| `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* activation code: [insert here valid activation code]
* e-mail id: blank
* name: blank
* surname: Burjack
* country: Brazil
* phone number: 62999999999
* native language: Português
* password: blank
* confirm password: blank

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Click on "Eu tenho um código"
3. Enter the activation code provided in the "test data" section
4. Click on "Continuar"
5. Click on e-mail field
6. Click on name field
7. Enter informations provided by the "test data" section

### Expected Results
1. Button "Ativar" should remain disabled
2. System should present the error highlighting the field or with a error message
