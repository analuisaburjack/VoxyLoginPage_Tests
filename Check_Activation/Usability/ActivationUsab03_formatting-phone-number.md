Test case id | Priority | Description | Version
---|---|---|---
ActivationUsab03 | `medium` | Verify activation usability concerning the formatting of the correct phone number presented| `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* activation code: 123456789123
* phone number: 62999999999

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Click on "Eu tenho um código"
3. Enter the activation code provided in the "test data" section
4. Click on "Continuar"
5. Select the country Brazil
6. Insert correct phone number provided in the test data section

### Expected Results
1. System should format the phone number presented according to the country formatting, for this test,
the phone number entered should be presented as (62) 99999-9999
