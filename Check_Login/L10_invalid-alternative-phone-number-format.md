Test case id | Priority | Description | Version
---|---|---|---
L10 | `medium` | Verify login functionality whith invalid alternative phone number format| `1.0`

### Prerequisites
1. access to browser
2. working internet

### Test Data
* phone number: 6 2)99999--9999(

### Steps
1. Navigate to login page (https://app.voxy.com/v2/#/login/)
2. Select login option phone number
3. Select the country Brazil
4. Enter the phone number id provided in the "test data" section
5. Click outside the text field

### Expected Results
1. Button "Continuar" should remain disabled
2. System should present the error highlighting the field or with a error message
