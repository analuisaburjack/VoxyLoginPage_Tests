Test case id | Priority | Description | Version
---|---|---|---
L4 | `critical` | Verify login functionality whith correctly formated phone number, although, invalid| `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* phone number: 62999999999

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Select login option phone number
3. Select the country Brazil
4. Insert invalid phone number provided on test data section
5. Click on "CONTINUAR"

### Expected Results
1. User should be presented with a pop-up warning that it wasn't possible to find an account matching the information given
2. System should present only the option to try again
3. User should not be able to access the platform
