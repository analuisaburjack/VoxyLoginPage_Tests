# Voxy Login Page Tests
Coding challenge - Voxy login page test cases

<br>This repository contains test cases for the login page scenario. It is organized in two sections:
* Check_Activation
* Check_Login

<br>Each section is then subdivided in:
* Functionality
* Security
* Usability

<br>Each test case id is named ActivationFuncter the high-level function is being tested, wich aspect wil be tested and the number sequence.

Examples:
* ActivationFunc01
* LoginSec02

<br>Each test case name must contain its id and a brief description, hyphaned instead of spaced in between the words.

Examples:
* ActivationFunc01_incorrect-activation-code
* ActivationSec05_invalid-password-confirmation

## Index

### Check_Activation

Id | Description | Priority
---|---|---
[ActivationFunc01](./Check_Activation/Functionality/ActivationFunc01_incorrect-activation-code.md)|incorrect activation code|`high`
[ActivationFunc02](./Check_Activation/Functionality/ActivationFunc02_correct-activation-code.md)|correct activation code|`high`
[ActivationFunc03](./Check_Activation/Functionality/ActivationFunc03_valid-informations.md)|valid informations|`critical`
[ActivationFunc04](./Check_Activation/Functionality/ActivationFunc04_invalid-activation-code.md)|invalid activation code|`critical`
[ActivationFunc05](./Check_Activation/Functionality/ActivationFunc05_mandatory-informations.md)|mandatory informations|`critical`
[ActivationFunc06.1](./Check_Activation/Functionality/ActivationFunc06.1_unformatted-email.md)|unformatted email|`high`
[ActivationFunc06.2](./Check_Activation/Functionality/ActivationFunc06.2_unformatted-email.md)|unformatted email|`high`
[ActivationFunc06.3](./Check_Activation/Functionality/ActivationFunc03_valid-informations.md)|unformatted email|`high`
[ActivationFunc06.4](./Check_Activation/Functionality/ActivationFunc06.4_unformatted-email.md)|unformatted email|`high`
[ActivationFunc06.5](./Check_Activation/Functionality/ActivationFunc06.5_unformatted-email.md)|unformatted email|`high`
[ActivationSec01](./Check_Activation/Security/ActivationSec01_copypaste-password-confirmation.md)|copypaste password confirmation|`high`
[ActivationSec02.1](./Check_Activation/Security/ActivationSec02.1_invalid-password.md)|invalid password|`critical`
[ActivationSec02.2](./Check_Activation/Security/ActivationSec02.2_invalid-password.md)|invalid password|`critical`
[ActivationSec02.3](./Check_Activation/Security/ActivationSec02.3_invalid-password.md)|invalid password|`critical`
[ActivationSec02.4](./Check_Activation/Security/ActivationSec02.4_invalid-password.md)|invalid password|`critical`
[ActivationSec03](./Check_Activation/Security/ActivationSec03_valid-password.md)|valid password|`critical`
[ActivationSec04](./Check_Activation/Security/ActivationSec04_valid-password-confirmation.md)|valid password confirmation|`critical`
[ActivationSec05](./Check_Activation/Security/ActivationSec05_invalid-password-confirmation.md)|invalid password confirmation|`critical`
[ActivationUsab01](./Check_Activation/Usability/ActivationUsab01_activation-code-correction.md)|activation code correction|`high`
[ActivationUsab02](./Check_Activation/Usability/ActivationUsab02_password-instructions.md)|password instructions|`high`
[ActivationUsab03](./Check_Activation/Usability/ActivationUsab03_formatting-phone-number.md)|formatting phone number|`medium`

### Check_Login

Id | Description | Priority
---|---|---
[LoginFunc01](./Check_Login/Functionality/LoginFunc01_valid-email.md)|valid email|`critical`
[LoginFunc02](./Check_Login/Functionality/LoginFunc02_valid-phone-number.md)|valid phone number|`critical`
[LoginFunc03](./Check_Login/Functionality/LoginFunc03_blank-email.md)|blank email|`high`
[LoginFunc04.1](./Check_Login/Functionality/LoginFunc04.1_unformatted-email.md)|unformatted email|`high`
[LoginFunc04.2](./Check_Login/Functionality/LoginFunc04.2_unformatted-email.md)|unformatted email|`high`
[LoginFunc04.3](./Check_Login/Functionality/LoginFunc04.3_unformatted-email.md)|unformatted email|`high`
[LoginFunc04.4](./Check_Login/Functionality/LoginFunc04.4_unformatted-email.md)|unformatted email|`high`
[LoginFunc04.5](./Check_Login/Functionality/LoginFunc04.5_unformatted-email.md)|unformatted email|`high`
[LoginFunc05](./Check_Login/Functionality/LoginFunc05_blank-phone-number.md)|blank phone number|`high`
[LoginFunc06.1](./Check_Login/Functionality/LoginFunc06.1_unformatted-phone-number.md)|unformatted phone number|`high`
[LoginFunc06.2](./Check_Login/Functionality/LoginFunc06.2_unformatted-phone-number.md)|unformatted phone number|`high`
[LoginFunc06.3](./Check_Login/Functionality/LoginFunc06.3_unformatted-phone-number.md)|unformatted phone number|`high`
[LoginFunc07](./Check_Login/Functionality/LoginFunc07_valid-alternative-phone-number-format.md)|valid alternative phone number format|`medium`
[LoginFunc08](./Check_Login/Functionality/LoginFunc08_invalid-alternative-phone-number-format.md)|invalid alternative phone number format|`medium`
[LoginSec01](./Check_Login/Security/LoginSec01_invalid-email.md)|invalid email|`critical`
[LoginSec02](./Check_Login/Security/LoginSec02_invalid-phone-number.md)|invalid phone number|`critical`
[LoginUsab01](./Check_Login/Usability/LoginUsab01_formatting-phone-number.md)|formatting phone number|`medium`