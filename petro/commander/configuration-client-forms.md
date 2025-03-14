# Configuration Client Forms

This topic contains all the Verifone Commander Configuration Client forms. The configuration forms in this topic are described in the menu order displayed on the Verifone Commander Configuration Client.

## Security

### Manage Users

### Configure Users

Use **Security > Manage Users > Configure Users** to add, edit, or remove users. The current users are listed on the left side of the form.

| Field/Button                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | AllowableValue/Function                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Add**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Click to add a new user.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Delete**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Select an existing user and click Delete to remove the user from the Users list.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Name**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Enter the name of the user (number of characters are unlimited).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Disallow Login**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     | Select to disallow the selected user from logging in to the Configuration Client.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
| **Employee**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                           | <p>Assign an employee type to the user by selecting from the drop-down list.<br/>The employee types with security levels are created using <strong>Security > POS Security > Employees</strong>.</p>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Roles**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              | Roles are set up on the Configure Roles tab. The roles assigned to the selected user are displayed in this box.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Edit**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Click to display the available roles. Select one or more roles for the user and click **Done**.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| **Passwords Settings**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 | **(Password settings section begins here)**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
| **Min Length**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Enter a minimum length for the user’s password (7 - 30).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Max Length**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Enter a maximum length for the user’s password (8 - 30).                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **# of Days to Expire**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | <p>Enter the number of days until the password expires.<br/><strong>Note</strong> The password should be changed before it expires.</p>                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
| **Force Change on Next Login**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Select to make the user change their password the next time they log in.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **New Password**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       | Enter the user’s new password. The new password should meet the requirements of the password guidelines.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
| **Confirm New Password**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | Enter the password again to confirm.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                     |
| **Password Guidelines**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Click to display password guidelines.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                    |
| **Secure User Settings**                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               | <p>‘Secure user’ is a user who can access PA-DSS sensitive Card Holder Data (CHD) in ‘EPS Secure Reports’ from POS via the <strong>Network Manager</strong> menu.<br>POS prompts for secure employee ID and secure user password prior to processing this menu item.<br>To avoid having to type username on POS keyboard, this feature allows associating a POS employee ID to a user. When POS prompts, secure user must enter their ‘secure employee ID’ and the PA-DSS compliant ‘user’ password. On successful validation, PA-DSS sensitive Card Holder Data (CHD) is exposed in the EPS reports. If validation fails, masked PAN is provided in the EPS Reports.<br><br>Secure Admin is a ‘secure user’ who can manage ‘secure user’ as well as ‘secure admin’ accounts.<br><strong>Note:</strong> The 'Secure User Administration' section is displayed when you log in as 'manager' (the default secure user admin account) or any user that is configured as a secure admin.</p> |
| Secure User ID                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         | Enter the Secure User ID.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| Secure User Administration                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                             | Enable if the user has secure user administration rights.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| <p><strong>Verifone C-Site Management</strong><br>The Verifone C-Site Management application allows remote configuration of data for the POS system through the web. Without visiting each location changes and updates can be done remotely for any or all locations. These updates can be done selectively or all at once for all the POS devices from the web application.<br><br>OTP is a one-time password generated by the Verifone Commander for accessing certain menus. Verifone C-Site Management now supports remote generation and retrieval of OTP. Passwords generated this way are sent to the email address associated with the Verifone C-Site Management user login.<br><br><strong>Note:</strong> Refer to the Verifone C-Site Management User Reference documentation for more information on this feature. The User Reference is available on Premier Portal.</p> |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                          |
| User ID                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                | Add the same Verifone® C-Site Management Email User ID address that was configured as part of OTP settings in the Verifone® C-Site Management application and Click Save.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |

### Configure Roles

Use **Security > Manage Users > Configure Roles** to assign permissions, add new roles, edit and delete current roles, and add and delete functions from each role. These roles are assigned to users.

The current roles are listed on the left side of the form.

Addition, removal, or modification of the roles can only be performed by a secure administrator. The “Secure Role” attribute allows secure administrators to specify whether a role's access should be limited only to secure users. If this attribute is set, the role can only be assigned to a secure user.

#### To Edit a Role

1. Select the role from the Roles list.
2. Click **Edit** at the Functions box.
3. Change the name in the Role Name text box.
4. To edit the function assignment to the role, enable or disable the functions in the Functions form.
5. Click **Done** in the Functions form.
6. Click **Save**.

#### To Add Role and Add Functions to Role

1. Click **New**.
2. Enter the name in the Role Name text box.
3. Click **Edit** at the Functions box to assign functions to the role.
4. Select the function(s) for the role from the Functions form.
5. Click **Done** in the Functions form.
6. Click **Save**.

#### To Delete a Role

1. Select the role from the Roles list.
2. Select **Delete**.
3. Click **Save**.

#### Role Function Description

The following is the list of role functions and their descriptions:

| Function                       | Description                            | Additional Info                                                                                  |
| ------------------------------ | -------------------------------------- | ------------------------------------------------------------------------------------------------ |
| **allowAllCsrRpts**            | Allow all cashier reports view         | Allow user to view all cashier reports that are available                                        |
| **allowOpenCsrRpts**           | Allow open cashier reports view        | Allow user to view open cashier reports (current and/or reports with MOP amounts not yet filled) |
| **allowRestricted**            | Allow Restricted Access                |                                                                                                  |
| **bypassEmployeeId**           | Bypass employee id                     | Bypass employee id validation validation in POS security functions                               |
| **cbeginupgrade**              | Request Auto Upgrade                   | Engine to begin upgrade                                                                          |
| **ccarwashdisable**            | Disable Car Wash                       |                                                                                                  |
| **ccarwashenable**             | Enable Car Wash                        |                                                                                                  |
| **cclosedaynow**               | Close Day Now                          |                                                                                                  |
| **ccwpaypointinit**            | Initialize Carwash Paypoint            |                                                                                                  |
| **ccwpdclose**                 | Carwash Paypoint Period Close          | Performs Period Close On Carwash Paypoint                                                        |
| **cdcrdriverinit**             | Initialize DCR Driver                  |                                                                                                  |
| **cdcrinit**                   | Initialize DCR                         | Initialize DCRs                                                                                  |
| **cdisablelogin**              | Disable Helpdesk Login                 |                                                                                                  |
| **cenablelogin**               | Enable Helpdesk Login                  |                                                                                                  |
| **cfeatureenablement**         | Update a feature                       | Update Licensed Features                                                                         |
| **cFPDinit**                   | Init FP Display Config                 |                                                                                                  |
| **cfueldrvinit**               | Initialize Fuel Driver                 |                                                                                                  |
| **cfuelinit**                  | Initialize Fuel                        |                                                                                                  |
| **cfuelprices**                | Download Fuel Prices                   |                                                                                                  |
| **changepasswd**               | Change Password                        |                                                                                                  |
| **cping**                      | Pings a given destination              |                                                                                                  |
| **crefreshcfg**                | Refresh Configuration                  |                                                                                                  |
| **crefreshepsconfig**          | Refresh Eps Config                     |                                                                                                  |
| **cswupgradepkg**              | Update software                        |                                                                                                  |
| **diagdeleteclass**            | Delete Diagnostic Class                | Delete a previously loaded dynamic diagnostic classfile                                          |
| **diagloadclass**              | Load Diagnostic Class                  | Load a classfile to be run as dynamic diagnostic                                                 |
| **diagrunclass**               | Run Diagnostic Class                   | Execute a dynamic diagnostic class                                                               |
| **findfilename**               | View report period filename            |                                                                                                  |
| **getPLUsFromGempro**          | Send plu.dat to NEWPRO                 | Send plu.dat from GEMPRO to NEWPRO                                                               |
| **notifyamber**                | Notify amber alert                     | Notify Controller of amber alert updates                                                         |
| **releaseCredential**          | Release the credential                 |                                                                                                  |
| **repeatEvent**                | Repeat last event                      | Notify specified event listener of the last occurrence of the specified event                    |
| **sendPLUsToGempro**           | Send plu.dat to GEMPRO                 | Send PLU data from NEWPRO to GEMPRO                                                              |
| **uagevalidationcfg**          | Update age validation config           |                                                                                                  |
| **ubannercfg**                 | Update banner config                   |                                                                                                  |
| **ubluelawcfg**                | Update blue law config                 |                                                                                                  |
| **ucarwashcfg**                | Update carwash config                  |                                                                                                  |
| **ucashaccsite**               | Update cash acceptor config            |                                                                                                  |
| **ucashierenddraweramts**      | Update Cashier End Drawer Amounts      |                                                                                                  |
| **ucashierreportreviewstatus** | Update Cashier Report Review Status    |                                                                                                  |
| **ucashiertrackingcfg**        | Update cashier tracking configuration  |                                                                                                  |
| **ucouponfamcfg**              | Update coupon family config            |                                                                                                  |
| **ucurrencycfg**               | Update currency config                 | Update currency dataset configuration                                                            |
| **ucwpaypointcfg**             | Update carwash paypoint config         |                                                                                                  |
| **udatetime**                  | Set Time and Date                      | Set the internal clock on Controller, including timezone and daylight savings time parameters    |
| **udcrheadercfg**              | Update DCR header config               |                                                                                                  |
| **udcridlescreencfg**          | Update DCR Idle Screen                 | Update DCR Idle Screen config dataset configuration                                              |
| **udcrmessagecfg**             | Update DCR message config              |                                                                                                  |
| **udcrtrailercfg**             | Update DCR trailer config              |                                                                                                  |
| **udiscountdenomcfg**          | Update discount denom config           |                                                                                                  |
| **uecheckcfg**                 | Update Echeck Config                   |                                                                                                  |
| **uemvcfg**                    | Update EMV Configuration               | Update All EMV Configuration Settings                                                            |
| **uemvinit**                   | Update EMV Initialization              | Update All EMV Initialization Settings                                                           |
| **uepsprepaidcfg**             | Update EPS Prepaid Card Config         |                                                                                                  |
| **uesafecfg**                  | Update Esafe Config                    |                                                                                                  |
| **ufeecfg**                    | Update fee config                      | Update fee dataset config                                                                        |
| **ufepcardcfg**                | Update Fep's card configuration        | Update Fep's card configuration parameters like various limits, enable/disable card              |
| **ufepcardtypecfg**            | Update Fep's card configuration        | Update Fep's card configuration parameters based on card Type like limits, enable/disable etc.   |
| **ufepcfg**                    | Update Fep's configuration             | Update Fep's configuration parameters like network, cashback etc.                                |
| **ufoodservicecfg**            | Update Food Service Config             |                                                                                                  |
| **uFPDcfg**                    | Update FP Display Config               |                                                                                                  |
| **ufuelcfg**                   | Update Fuel Site Configuration         | Update the fueling dispensers, products, mops, tanks, and prices for the site                    |
| **ufuelprices**                | Update Fuel Prices                     | Update the fueling prices for the site                                                           |
| **ufueltaxex**                 | Update Fuel Tax Exemption Config       |                                                                                                  |
| **ufunctionlist**              | Refresh function list                  |                                                                                                  |
| **ugrouplist**                 | Update Group List Configuration        | Update available report groups                                                                   |
| **uifsfcfg**                   | Update IFSF Network Config             |                                                                                                  |
| **uinhouseacctcfg**            | Update in-house account config         | Update in-house account dataset config                                                           |
| **ukioskorder**                | Commit kiosk order                     |                                                                                                  |
| **ulogocfg**                   | Update logo config                     | Update logo dataset config                                                                       |
| **uloyaltycardcfg**            | Update Loyalty Card Configuration      |                                                                                                  |
| **uloyaltycardtypecfg**        | Update Loyalty Card Type Configuration |                                                                                                  |
| **uloyaltyglobalcfg**          | Update Global Loyalty parameters       |                                                                                                  |
| **uMaintenance**               | Update NAXML maintenance               | Update configuration datasets as NAXML maintenance documents                                     |
| **umaintfprht**                | Update maint fprht                     |                                                                                                  |
| **umaintpostal**               | Update maint postal                    |                                                                                                  |
| **umaintregistrationkey**      | Update maint registration key          |                                                                                                  |
| **umainttelephone**            | Update maint telephone                 |                                                                                                  |
| **umainttotalizers**           | Update maint totalizers                |                                                                                                  |
| **umanagedcfg**                | Update Managed Configuration           |                                                                                                  |
| **umanagedmodulecfg**          | Update Module Configuration            |                                                                                                  |
| **umanageradjustment**         | Update Manager Adjustments             |                                                                                                  |
| **umanagercorrection**         | Update Manager Corrections             |                                                                                                  |
| **umenucfg**                   | Update menu config                     | Update menu dataset config                                                                       |
| **umobilecfg**                 | Update Mobile Configuration            |                                                                                                  |
| **umopcfg**                    | Update MOP config                      | Update MOP dataset config                                                                        |
| **umwscashmovementreport**     | Update MWS Cash Movement Info          |                                                                                                  |
| **unetposcfg**                 | Update Network Configuration           | Update POS related Network Configuration                                                         |
| **unetworkcfg**                | Update Network Settings                | Update Network Settings (IP, route, etc.)                                                        |
| **unetworkpartcfg**            | Update network settings                |                                                                                                  |
| **upaymentcfg**                | Update payment config                  | Update payment dataset config                                                                    |
| **upinpadmsgcfg**              | Update Pinpad Idle and Swipe messages  |                                                                                                  |
| **uPLUCacheList**              | Update PLU cache list                  | Update the list of PLUs cached on POS                                                            |
| **uplupromocfg**               | Update PLU Promo config                | Update PLU Promo dataset config                                                                  |
| **uPLUs**                      | Update PLU dataset                     |                                                                                                  |
| **upolicycfg**                 | Update policy config                   |                                                                                                  |
| **upopcfg**                    | Update pop config                      |                                                                                                  |
| **uposcfg**                    | Update POS config                      | Update POS dataset config                                                                        |
| **upospaymentconfig**          | Update POS Payment Configuration       |                                                                                                  |
| **upossecurity**               | Update POS security                    | Update POS security config dataset config                                                        |
| **uprepaidcfg**                | Update Prepaid Card Config             |                                                                                                  |
| **upscdcrcfg**                 | Update DCR config                      | Update DCR dataset config                                                                        |
| **upscdcrkeycfg**              | Update DCR Key config                  | Update DCR Key dataset config                                                                    |
| **uregistercfg**               | Update register config                 | Update register specific dataset config                                                          |
| **ureportcfg**                 | Update Report Configuration            |                                                                                                  |
| **ureportlist**                | Update Report List Configuration       | Update the order of available reports                                                            |
| **ureportstatus**              | Update Manager Review Status           |                                                                                                  |
| **urestrictionscfg**           | Update restriction config              | Update restriction dataset config                                                                |
| **usalescfg**                  | Update sales config                    |                                                                                                  |
| **usapphireprop**              | Update Controller system properties    |                                                                                                  |
| **uscreencfg**                 | Update POS Screen Configuration        |                                                                                                  |
| **usecuritylogservercfg**      | Update Security Log Server IP Address  |                                                                                                  |
| **uslogancfg**                 | Update slogan config                   | Update slogan dataset config                                                                     |
| **usoftkeycfg**                | Update softkey config                  | Update softkey dataset config                                                                    |
| **utaxratecfg**                | Update tax rate config                 | Update tax rate dataset config                                                                   |
| **utlssite**                   | Update TLS config                      |                                                                                                  |
| **utriggerpullcfg**            | Update Trigger Pull Configuration      | Update All Trigger Pull Configuration Settings                                                   |
| **uuseradmin**                 | User Administration                    | User admin update                                                                                |
| **uvendingmachinecfg**         | Update Vending Machine config          | Update Vending Machine dataset config                                                            |
| **uvipercfg**                  | Update Viper's site level Config       | Update Viper's site level Config like various limits, and pop configuration                      |
| **vagevalidationcfg**          | View age validation config             |                                                                                                  |
| **validate**                   | Validate the credential                |                                                                                                  |
| **vappcfg**                    | View App Specific Config               |                                                                                                  |
| **vAppInfo**                   | View App Info                          | View App Version Info                                                                            |
| **vappmodules**                | View App Module Names                  | View the list of Application noted module names.                                                 |
| **vbannercfg**                 | View banner config                     |                                                                                                  |
| **vbluelawcfg**                | View blue law config                   |                                                                                                  |
| **vcarwashcfg**                | View carwash config                    |                                                                                                  |
| **vcashaccsite**               | View cash acceptor config              |                                                                                                  |
| **vcashierpdlist**             | View cashier report period list        | View list of cashier report periods available                                                    |
| **vcashierrept**               | Cashier Reports                        | View the cashier period reports                                                                  |
| **vcashiertrackingcfg**        | View cashier tracking configuration    |                                                                                                  |
| **vcashiertrackingrept**       | View cashier tracking report           |                                                                                                  |
| **vcouponfamcfg**              | View coupon family config              |                                                                                                  |
| **vcurrencycfg**               | View currency config                   | View currency dataset config                                                                     |
| **vcwpaypointcfg**             | View carwash paypoint config           |                                                                                                  |
| **vcwpaypointpdlist**          | View cw paypoint period list           | View list of cw paypoint periods available                                                       |
| **vcwpaypointpdrept**          | View cw paypoint period report         |                                                                                                  |
| **vdatetime**                  | Get Time and Date                      | View the Controller internal time                                                                |
| **vdcrheadercfg**              | View DCR header config                 |                                                                                                  |
| **vdcridlescreencfg**          | View DCR Idle Screen                   | View DCR Idle Screen config dataset config                                                       |
| **vdcrmessagecfg**             | View DCR message config                |                                                                                                  |
| **vdcrtrailercfg**             | View DCR trailer config                |                                                                                                  |
| **vdiscountdenomcfg**          | View discount denom config             |                                                                                                  |
| **vecheckcfg**                 | View Echeck Config                     |                                                                                                  |
| **vemvcfg**                    | View EMV Configuration                 | View All EMV Configuration Settings                                                              |
| **vemvinit**                   | View EMV Initialization                | View All EMV Initialization Settings                                                             |

### Manage Devices

The Manage Devices form is used to add and enable external POS devices like the Attendant Payment Terminal and Carbon Verifone Commander Workstation.

::: note Refer to the Attendant Payment Terminal and Carbon Verifone Commander Workstation Feature References for more information on this feature. The Feature References are available on Premier Portal. :::

1. In Verifone Commander Config Client, go to Security > Manage Devices.
2. Click on Guidelines to generate a token, to read the guidelines.

3\. Click Add to start adding the terminals.

4\. Enter the external POS ID in the Terminal ID field. The ID should be between 151 and 199. Each application type should have a unique ID. This terminal ID should be entered as the POS ID for the terminal while configuring the terminal from Devices > Attendant Payment Terminal > Terminal. 5. Select the application type from Application Type drop-down. 6. Add a description for the terminal to help identify the terminal. 7. Get the IP address and port for the terminal from the IT team. 8. Select Enable to enable the device. 9. Click Save. A one-time password (OTP) is required to save the configuration. 10. Click Generate OTP and enter the OTP generated on the Verifone Commander display.

11\. After save is successful, a. User can see a ‘Generate’ button in ‘Token Action’ column of the form. b. User will not be allowed to modify the ‘Terminal ID’ of the saved entry. 12. On clicking ‘Generate’ button, token is sent to the corresponding device that is configured from Devices > Attendant Payment Terminal > Terminal. 13. APT device is expected to accept the token and send the details like serial number, model, version, etc. to Verifone Commander. 14. When the Verifone Commander receives a response from the device, ‘Serial number’ and ‘Status’ columns are updated on the Config Client form 15. Once token generation is successful, user will not be allowed to modify the ‘Application Type’ of the device entry

### POS Security

#### Employees

Use to edit, add, and delete employees. In addition to logging in and out of the register, this employee information is used for the Payroll Report, Summary by Register Report, and Summary by Cashier Report. The current employees are listed on the left side of the form.

| **Field/Button**         | **Allowable Value/Function**                                                                                                                                                                                                   |
| ------------------------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Name**                 | Assign a name for the employee. Alphanumeric, 1 - 30 characters.                                                                                                                                                               |
| **Employee Number**      | <p>Assign a unique employee number, such as a company-assigned ID, to identify the employee for internal and payroll purposes. Alphanumeric, 1 - 15 characters.<br>Used for Employee Number Login and security validation.</p> |
| **Security Level**       | Select the employee’s security level. The employee has access to all functions that have a security level less than or equal to the security level assigned.                                                                   |
| **Can Cashier**          | Select to allow the employee to perform cashier functions when in Sales mode.                                                                                                                                                  |
| **New Password**         | Enter the password that the employee must use to clock in or out. Alphanumeric, 1 - 8 characters.                                                                                                                              |
| **Confirm New Password** | Enter the password again to confirm.                                                                                                                                                                                           |
| **Delete**               | Select to delete the selected employee information.                                                                                                                                                                            |

#### Security Ctrls

Use to assign a security level to submenu items in the list. The Items in the list are reports or non-sales functions. These security levels correspond to the Security levels assigned to each employee. Only the entries in the Security Level column can be changed. Only employees with the assigned security level can view these reports or perform these non-sales functions.

Select a security level from the drop-down list.

**Backdoor Login Restriction** Backdoor login access to the POS has been restricted. With the existing implementation, the security level assigned for the backdoor menu is `10`. The `Device Control` and `Adjust Screen Saver` are the options provided through backdoor entry.

After the backdoor login has been restricted the default security level for `Device Control` and `Adjust Screen Saver` is changed to 7.

### Sales Functions Security

Use to assign a security level to the following sales functions in the list:

* Apply Updates (MUP)
* Safe Drop Correction (SDC)
* Refund (REF)
* Void Ticket (VTI)
* Void Line (VLI)
* Price Override (POR)
* Discount (MDC)
* Suspend (SUS)
* No Sale (NSA)
* Payout (POU)
* Error Correct

Only employees with the assigned security level can perform these functions.

When the user clicks a security level and Apply All is selected, the value is applied to all the sales functions.

The user can also configure any of the functions independently. Default value for Pay Out is 7 and Default value for Apply Updates is 7. Default value for all the other functions is 0. 0 indicates that the function does not require a security check and any employee can perform the function.

### Site Security

The POS Pairing process establishes a trust relationship between the Verifone Commander and each Verifone POS Workstation and creates secure communication links. It is similar to where a cellphone is paired to a speaker or automobile dash display.

The POS workstation pairing process is strongly recommended by Verifone to be performed on the same day the system is Auto Upgraded. After an auto upgrade, each Verifone POS displays messages that the system needs to be paired.

:::note Refer to the POS Pairing Feature Reference documentation for more information on this feature. The User Reference is available on Premier Portal. :::

Pairing after the initial Auto Upgrade, Pairing Expired/Revoked If the POS displays the “Sec. Alert - Pairing Invalid” or the “Sec. Alert - Pairing Required” message, follow these steps to pair the Verifone POS Workstation with the Verifone Commander. The POS Workstation displays one of the two messages below at login to Sales or between each transaction in Sales.

1. On the POS Workstation, navigate to CSR Func > Maintenance Menu. Press **\[Perform POS Pairing]**.

2\. A message asking to perform POS pairing displays, press \*\*\[Yes]\*\*.

3\. A message “Rebooting to start the pairing process...” will briefly display. The POS will reboot and then the “Pair POS” screen displays.

4\. At Configuration Client and using the Manager credentials, navigate to Configuration Client > Security > Site Security. 5. An OTP is required to complete the process. Press the \[Generate OTP] button.

6\. The “OTP has been generated. Please read it from the Verifone Commander’s status display.” confirmation message displays. Press \[Ok] to continue.

7\. Read the OTP digits from the Verifone Commander. Enter the four OTP digits into the text box and then press \[OK].

8\. The Site Security form opens. Press \[Start Pairing Service].

9\. A confirmation message stating “Pairing service is started” displays. Press \[OK] to continue.

10\. Go back to the POS Workstation. Press \[Pair POS].

11\. A Pairing OTP dialog box displays on the POS.

12\. Navigate to Configuration Client > Security > Site Security. Press \[Retrieve Pairing OTP].

13\. A “Pairing session OTP” dialog box displays.

14\. Go back to the POS workstation. Enter the 6-digit Pairing session OTP code from Configuration Client into the “Pairing” dialog box.

15\. Press \[OK]. The message “Processing, please wait...” displays and then after a moment, “Successfully Paired” displays.

16\. Press \[OK] to continue. A message “Pairing completed, preparing to start POS application...” displays.

17\. Repeat these steps if: \* Pairing was not successful \* The site has more than one POS Workstation

#### Pairing the POS Workstation after New Installation

After a new installation, the POS Workstation displays the Pair POS screen below after it boots up. Follow steps 4 to 17 above.

#### Revoke All Trust

If a workstation needs to be removed for repair or sent to another store, use the following steps to Revoke All Trust from the Pairing Relationship.

1. On the Site Security form at Configuration Client > Security > Site Security.
2. An OTP is required to complete the process. Press the \[Generate OTP] button.

3\. The “OTP has been generated. Please read it from the Verifone Commander’s status display.” confirmation message displays. Press \[Ok] to continue.

4\. Read the OTP digits from the Verifone Commander, Enter the four OTP digits into the text box and then press \[OK].

5\. The Site Security form opens. Press \[Revoke All Trust].

6\. A confirmation message stating “This action will remove all prior pairing relationships. All POS Workstations will need to be paired again. Are you sure you want to continue?” displays. Press \[Yes].

7\. The “Processing request. Please Wait...” message displays before the successful message. Press \[OK].

8\. Follow the steps in “Pairing after the initial Auto Upgrade, Pairing Expired/Revoked” section to pair the other POS Workstations.

#### Security Log Server

Syslog is a way for network devices to send event messages to a logging server – usually known as a Syslog server. The Syslog protocol is supported by a wide range of devices and can be used to log different types of events. For example, a router might send messages about users logging on to console sessions or a web-server might log access-denied events.

This form is used to report security and OS related events to the configured server. Enter the log server’s IP address in this form.

A one-time password (OTP) is required to open and edit this form. Click Generate OTP and enter the OTP generated on the Verifone Commander display to the One-Time Password form.

The following is how the security logs appear on the server display:

### My Profile

:::note Refer to the Password Reset Feature Reference for more information on this feature. The Feature References is available on Premier Portal. :::

Using this menu, a Config Client user can reset their own password without calling the Helpdesk. The primary benefit of this feature is to reduce the number of calls generated to the Helpdesk.

#### Adding or Modifying Challenge Questions

For the config client users to reset their own password, a set of challenge questions and answers should be added. The questions are chosen from a drop-down list.

If users do not setup the challenge questions, every time they login to Config Client, they get the following reminder:

#### Change Password

After logging in, a user can change password using the Change Password menu that can be assessed from **Security > My Profile**.

#### Forgot Password

“Forgot Password” link on login page of Config Client or Manager Workstation displays a prompt where user must enter the username and click Submit to start the process of resetting password.

If the user doesn’t already have challenge questions set or if the username doesn’t exist, the server shows an error.

If the challenge questions are set, any two of the questions are shown for the user to answer.

On answering the questions right, the user is prompted to enter a new password.

## Initial Setup

\### Date Time The Date & Time Configuration form is used to verify or edit the date, time, and time zone on the Verifone Commander.

Select the date, month and year from the drop-down list boxes.

The displayed time is the current time. To change the time, select the time from the drop-down list boxes.

#### Time Zone

Use to select the time zone in which your site is located.

#### NTP Server

Enable to get the time from the Network Time Protocol (NTP) server instead of the system clock. This section can be used to configure the IP address of the NTP server.

### Registration

The Registration form presents information that must be supplied to the Verifone Technical Support Center in order to obtain a Registration Key.

Call the Verifone Technical Support Center at (888) 777-3536. The Support Center will process the registration while you are on the phone.

:::note Registration is only done once, at the time of installation. :::

#### Registration Key

Enter the Registration Key supplied by the Verifone Technical Support Center.

### View Feature Info

The Feature Information form displays the options installed on the system. To view the entire list, select the last item and press the down arrow on your keyboard. Click Print to print the entire list.

### Maintenance Configuration

Refer to \[`Maintenance Configuration`]

### System Properties

Use to select, update, and save System Properties.

Detailed descriptions of the system properties can be found in the respective feature’s feature reference manuals.

| Field/Button         | Allowable Value/Function               |
| -------------------- | -------------------------------------- |
| System Property Name | Displays the property name.            |
| Value                | Displays the property value.           |
| Save                 | Click to save the selected Properties. |

#### System Properties Description

The following is the list of system properties and their descriptions:

| Field                    | Description                    |
| ------------------------ | ------------------------------ |
| apply.upgrade.forcefully | Opt-in for forced auto-upgrade |
| auto.print.Pd.report     | Auto print reports             |

**Properties that control the daily message display**

| Field                       | Description                                                                                                          |
| --------------------------- | -------------------------------------------------------------------------------------------------------------------- |
| DailyMsg.poll.interval      | The interval in which the system checks for daily messages.                                                          |
| DailyMsg.scroll.interval    | The interval the message pauses before adding another line when the window must be scrolled to display all messages. |
| DailyMsg.server.IP          | IP address of server hosting daily message text.                                                                     |
| DailyMsg.server.Port        | IP port to use on the server hosting daily message text.                                                             |
| DailyMsg.server.URL         | URL to reach the daily message text files                                                                            |
| data.trans.hst.days         | Number of days to keep t-log                                                                                         |
| database.plu.isgempromaster | Sales configuration                                                                                                  |
| disable.pinpad.cardreader   | Disable PIN pad card reader between transactions.                                                                    |

**DVR UDP Multicast properties** _(Refer to the Digital Video Recorder Feature Reference documentation for more information.)_

| Field                                | Description                                              |
| ------------------------------------ | -------------------------------------------------------- |
| dvr.localIPPort                      | DVR local port                                           |
| dvr.multicastEnable                  | Enable multicast                                         |
| dvr.multicastHost                    | DVR multicast host                                       |
| dvr.multicastPort                    | DVR multicast port                                       |
| dvr.ttl                              |                                                          |
| eps.needs.immediate.declined.receipt | EPS Needs Immediate Declined Receipt (Options = yes, no) |

**E-Safe Properties** _(Refer to the Tidel Sentinel E-Safe Interface Feature Reference documentation for more information.)_

| Field                             | Description                                       |
| --------------------------------- | ------------------------------------------------- |
| esafe.coin\_denomination          | E-Safe - Coin Denominations                       |
| esafe.note\_denomination          | E-Safe - Note Denominations                       |
| esafe.retryAttempts               | E-Safe connection retry attempts                  |
| esafe.retryInterval.milliseconds  | E-Safe connection retry interval in milliseconds. |
| esafe.socketTimeout.seconds       | E-Safe - Socket timeout in seconds                |
| event.monitor.history.limit       | How much event monitor history data is shown      |
| extPOS.config.depts               | External POS properties                           |
| fcc.dcrs.test                     | Test Gilbarco DCRs comma delimited                |
| force.InHouse.PayInOut            | Force In\_House for Pay IN and pay OUT            |
| fuel.max.curr.limit               | Set limit for the maximum currency at pump        |
| fuelsys.tankmonitor.tankcapacity  | Enable Fuel Tank Monitoring                       |
| include.cinit.activation.criteria | Show Auto Upgrade notification                    |
| journalPrinter.enabled            | Enable journal printer                            |
| journalPrinter.port               | Journal printer port                              |

**Kitchen Printer Configuration** _(Refer to the Kitchen Printer Feature Reference documentation for more information.)_

| Field                  | Description                                                                                                 |
| ---------------------- | ----------------------------------------------------------------------------------------------------------- |
| kp.svc.list            | Kitchen printer service list                                                                                |
| kp.svc.POS             | Use the exact text                                                                                          |
| kp.svc.POS.CommID      | Indicates which COM port of the POS terminal the kitchen printer is on.                                     |
| kp.svc.POS.host        | Indicates which POS terminal the printer is on.                                                             |
| loyalty.ppg.stack      | Enable Loyalty PPG stacking                                                                                 |
| mobile.feature.enabled | Enable Mobile Feature _(Refer to the Mobile Payment Feature Reference documentation for more information.)_ |

**Money Order Prompt** _(Refer to the Money Order Feature Reference documentation for more information.)_

| Field                               | Description                                                                                                         |
| ----------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| mopayee.prompt                      | Money order prompt                                                                                                  |
| mopayee.swb                         |                                                                                                                     |
| moptr.maxVendorPayment              | Maximum amount for Money Order Vendor Payment.                                                                      |
| mws.response.time                   | Manager Work Station Response Time                                                                                  |
| naxml.config.pluHasCheckDigit       | NAXML input processing _(Refer to the VIP NAXML Mix & Match Feature Reference documentation for more information.)_ |
| pdclose.forcelogout.time.inMins     | AEOD force logout warning time in minutes                                                                           |
| promotions.enableNaxmlDeal          | Enable Naxml promotions.                                                                                            |
| receipt.enterprise.footer.alignment | Receipt Footer Alignment (Options - LEFT, RIGHT, CENTER)                                                            |
| receipt.enterprise.header.alignment | Receipt Header Alignment (Options - LEFT, RIGHT, CENTER)                                                            |
| receipt.print.programName           | Print the promotion program name on receipt                                                                         |

**Remote Log Server properties**

| Field                               | Description                                   |
| ----------------------------------- | --------------------------------------------- |
| remote.server.hostname              | Host where the logs are stored                |
| remote.server.logBuffer.size        | Log server buffer size                        |
| remote.server.openRetry             |                                               |
| remote.server.port                  |                                               |
| remote.server.prefix                |                                               |
| remote.server.socketTimeout.seconds |                                               |
| rsd.useTestHost                     | Use RSD test host                             |
| ruby.fuelsys.driveOffAlert          |                                               |
| ruby.fuelsys.driveOffRepeat         |                                               |
| safeDrop.calculator                 | Calculator appears on screen during safe drop |
| sales.foodorder.expire.minutes      | Expiry minutes for food order                 |
| sales.print.zerovalueitem           | Prints receipts for zero value items          |
| standard.keybd.filename             | POS Keyboard file name                        |

**Amber Alert**

| Field                                       | Description                                                |
| ------------------------------------------- | ---------------------------------------------------------- |
| sys.amber.alertCountUrl                     |                                                            |
| sys.amber.alertDataUrl                      |                                                            |
| sys.amber.compareUrl                        |                                                            |
| sys.amber.enable                            | Enable amber alert                                         |
| sys.amber.pollFreqSecs                      |                                                            |
| ticket.reprint.includeDCRTrans              | Include DCR transactions in ticket reprint                 |
| topaz.enablevirtualkeyboard.expresspanel    | Enable or disable virtual keyboard button on express panel |
| topaz.safedrop.numbLines                    | Number of blank lines on safe drop receipt                 |
| topaz.sales.allowDismissalOfGroupedItemMenu | Grouped item menu configuration                            |
| topaz.sales.allowDismissalOfModifierMenu    | Grouped item menu configuration                            |
| topaz.sales.print.printTaxLines             | Print separate tax lines on receipt                        |
| topaz.sales.showPluModifiers                | Enable or disable display of plu modifier list             |
| upgrade.token.timeout                       | Auto Upgrade - timeout value for token in seconds          |
| viper.custom.feecode                        | Viper custom fee product codes                             |

#### Local Area Network Configuration

Local Area Network Configuration provides UI for configuring the LAN. Use to configure Global Routes, Device Specific IP Configuration, Device specific Routes and DNS.

#### VHQ Configuration

The customers can choose from the following VHQ options:

1. Sign a SOW - Verifone performs services to customer PIN pads through VHQ.
2. VHQ Administered – Verifone does the estate management for a fee.
3. VHQ Own Instance – Customers want to own their own instance and move all their PIN pads to their own instance.

The objective of having all Petro PIN pads on VHQ is the ability to remediate and resolve issues found in the field faster.

:::note Refer to the VHQ User Reference documentation for more information on this feature. The User Reference is available on Premier Portal. :::

POS sends following VHQ data to EPS:

* Enable/Disable (VHQ)
* VHQ Address
* Customer ID
* Store ID
* Lane ID
* Service ID
* Customer Profile
* Pinpad ID

Enable/Disable VHQ, Customer ID and VHQ Address is configured through VHQ Configuration form.

EPS sends the same information to PIN pad as part of the diagnostic message when the POS logs in. VHQ extracts the information from PIN pad.

Inorder to view and update VHQ Configuration, new user role functions should be created to view and update “VHQ Configuration”.

* vvhqconfiguration – View VHQ Configuration
* uvhqconfiguration – Update VHQ configuration

A person having the role “manager” have these (view and update) functions enabled by default. All other roles have view function enabled by default.

Refer to \[`Configure Roles`] for more information to configure roles.

After you enable VHQ, the form allows you to edit Customer ID and VHQ address.

On save, the form validates customer ID and VHQ address. VHQ address can be a URL or an IP address. Customer ID can be Alphanumerical characters up to 64 characters. If validation is not successful, an error message is displayed.

### Service and Maintenance (SAM)

Beginning with ViperPAY version 4.06.xx, an additional Service and Maintenance (SAM) feature will be available for Mx9xx Series PIN pads. The objective of having all Petro PIN pads connected with the Service and Maintenance feature is the ability to remediate and resolve issues found in the field faster. The SAM feature is included as part of ASM entitlement for Verifone Commander locations and includes improved Verifone Helpdesk support functions, such as:

* Review general configuration of the device, including network and system configuration.
* Review PIN pad diagnostic logs.
* Correct some operating system and application issues.
* Perform diagnostics remotely on the PIN pad, such as screen calibrations.

The SAM feature can be enabled after each PIN pad has the ViperPAY application loaded/upgraded. Enablement is performed by selecting "Accept" on the Terms & Conditions prompt that appears after the PIN pad application is loaded/upgraded. The SAM feature is PIN pad specific, therefore the prompt will appear on all PIN pads once the application is loaded/upgraded.

Rejecting the Terms & Conditions will disable SAM functionality. Verifone strongly encourages our customers to enable the Service and Maintenance feature.

Should a customer reject the agreement after updating the ViperPAY version and want the Service and Maintenance feature later, they can enter into System Mode on the PIN pad, navigate to “Enable VHQ default” and change the value to 1. They will then need to run the application from the PIN pad home screen and accept the Terms & Conditions prompt. This must be completed for each PIN pad.

:::note The above process is same when user changes from SAM to No SAM on PIN pad. ::: :::note Some PIN pads have Accept and Reject soft keys. Use these keys for SAM enablement. ::: :::note SAM is only available for PIN pads that are not a part of a client managed instance of VHQ. :::

### Verifone Commander Console

The Verifone Commander Console is a cloud-based enterprise application on which the Verifone Commander transactions and reports can be viewed. In order for Verifone Commander transactions and reports to be viewed on Verifone Commander

Console, the Verifone Commander Console needs to be configured in Configuration Client.

| Field/Button           | Allowable Value/Function                     |
| ---------------------- | -------------------------------------------- |
| **Enable Cloud Agent** | Select to enable Cloud Agent.                |
| **Verifone Commander** | Enter the Verifone Commander Console URL.    |
| **Console URL**        | (Same as above)                              |
| **Site ID**            | The Site ID of the store.                    |
| **Service ID**         | Verifone Commander Service ID. 7 characters. |
| **Postal Code**        | Enter the postal code of the site.           |

### Cloud Configuration Manager

The Cloud Configuration Manager is a cloud-based enterprise application used to manage Verifone Commander configuration settings for a site or group of sites. All Verifone Commanders that are managed through Cloud Configuration Manager must have the Cloud Configuration Manager agent configured in Configuration Client.

:::note Refer to the Cloud Configuration Manager documentation for information on this feature. :::

### General

| Field/Button   | Allowable Value/Function                                                      |
| -------------- | ----------------------------------------------------------------------------- |
| **Host URL**   | The URL of Cloud Configuration Manager.                                       |
| **Company**    | The company name that was set up when requesting Cloud Configuration Manager. |
| **Custom ID**  | Leave it blank.                                                               |
| **Site ID**    | The Site ID of the store.                                                     |
| **Service ID** | (No description provided)                                                     |

### CM Diagnostics

Use CM Diagnostics to see if Verifone Commander is connected to the Cloud Configuration Manager.

### Cloud Connect

The Verifone C-Site Management application allows to remotely configure data for the POS system through the web. A technician does not have to visit each location to make changes and updates. These updates can be done selectively or all at once for all the POS devices from the web application.

:::note Refer to the Verifone C-Site Management User Reference documentation for more information on this feature. The User Reference is available on Premier Portal. :::

## Store Operations

### Payment

### Currencies

Use to define the common currency, one alternate currency, and the exchange rate of the alternate currency in relation to the common currency.

| Field/Button | Allowable Value/Function                                                                                                                                                                           |
| ------------ | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Name**     | Enter a descriptive name for the currency (alphanumeric, 1 - 14 characters). All transactions use this currency unless the **\[OTHER CURR]** key is pressed. Each currency is selected separately. |
| **Delete**   | Click to delete the selected currency.                                                                                                                                                             |
| **Symbol**   | Select a symbol for each currency. The symbol appears on receipts.                                                                                                                                 |
| **Amount**   | Enter the rate at which the alternate currency is compared to the base currency (0.000000 - 999.999999).                                                                                           |

### Fees

Use to add an additional charge (for example, bottle deposits) to an item or department. The Fees tab can contain up to 99 different fees. The current fees are listed on the left side of the form.

| Field/Button          | Allowable Value/Function                                                                                                                                                                                                                                                                                                                                                                                                        |
| --------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Name**              | Enter a descriptive name for the Fee (alphanumeric, 1 - 9 characters). The name prints on receipts.                                                                                                                                                                                                                                                                                                                             |
| **Delete**            | Select to delete the selected fee.                                                                                                                                                                                                                                                                                                                                                                                              |
| **Department**        | From the drop-down menu, select the department to which fee transactions are charged for report totals.                                                                                                                                                                                                                                                                                                                         |
| **Fee is Refundable** | Select to indicate that the fee is refundable with the cost of the item if it is returned.                                                                                                                                                                                                                                                                                                                                      |
| **Fee Type**          | <p><strong>Percentage</strong>: Percentage Fee will be calculated as the configured percentage of base selling price.<br><br>Example: If Percentage Fee is configured as 4.555 and applied to an item with base selling price $9.98, the Fee applied will be calculated as <code>9.98 * 4.555 / 100 = 0.45</code>.<br><br><strong>Range/Amt</strong>: Fee calculation for sales will be updated to process by Range Amount.</p> |
| **Amount (1)**        | Enter the amount of the first fee (0.00 – 9999.99).                                                                                                                                                                                                                                                                                                                                                                             |
| **Range (1)**         | Enter the ending dollar amount for items to which the first fee applies.                                                                                                                                                                                                                                                                                                                                                        |
| **Amount (2)**        | Enter the amount of the second fee (0.00 – 9999.99).                                                                                                                                                                                                                                                                                                                                                                            |
| **Range (2)**         | Enter the ending dollar amount for items to which the second fee applies.                                                                                                                                                                                                                                                                                                                                                       |
| **Amount (3)**        | Enter the amount of the third fee (0.00 – 9999.99).                                                                                                                                                                                                                                                                                                                                                                             |
| **Range (3)**         | Enter the ending dollar amount for items to which the third fee applies.                                                                                                                                                                                                                                                                                                                                                        |
| **Amount (4)**        | Enter the amount of the fourth fee (0.00 – 9999.99).                                                                                                                                                                                                                                                                                                                                                                            |
| **Range (4)**         | Enter the ending dollar amount for items to which the fourth fee applies.                                                                                                                                                                                                                                                                                                                                                       |
| **Amount (5)**        | Enter the amount of the fifth fee (0.00 – 9999.99). This fee is applied to all amounts higher than the range end for the fourth fee.                                                                                                                                                                                                                                                                                            |

### Merchandise

The Merchandise Manager form is used to add, delete, and restore categories and departments. The Product Code tab displays the current product codes. Product codes cannot be edited.

### Categories

Use to define the categories for your site. The current categories are listed on the left side of the form.

The maximum number of categories that can be configured by platform:

* Ruby Ci - 9999
* Verifone Commander - 9999

| Field/Button | Allowable Value/Function               |
| ------------ | -------------------------------------- |
| **Add**      | Click to add a new category            |
| **Number**   | Enter a unique number for the category |
| **Name**     | Enter a unique name for the category   |

#### Product Code

The Product Code tab contains view-only data and cannot be edited. The fields in this tab are Number, Name, Status and Fuel (Yes or No).

#### Departments

Refer to \[`Department Sales`]

### Restrictions

#### Blue laws

Refer to \[`Blue Laws`].

#### ID Checks

Refer to \[`ID Checks`].

#### PLU Promotions

Refer to \[`PLU Promotions`].

#### Online Age Verification

TruAge is a digital identification solution that enhances current age-verification systems at all retail points of sale and protects user privacy. TruAge was developed by NACS (National Association of Convenience Stores) the global trade association that represents the convenience store industry, and Conexxus, its standards-setting partner.

:::note Refer to the Age Restrictions feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

#### PLUs

Refer to \[`PLU Sales`].

#### Sales

**Sales Configuration**

The Sales Configuration form is used to set up the sales functions and the login/logout messages for the site.

:::note All the Security Level configurations from this form has been moved to **Security > POS Security > Sales Functions Security** form. :::

| Field/Button                          | Allowable Value/Function                                                                                                                                                                                                                                                                                                       |
| ------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Allow Amount Entry for Refund         | Allows amount entry for refund so that the cashier can give the amount entered as refund to the customer as a roundoff figure after taking the difference from the customer.                                                                                                                                                   |
| Canadian GST                          | Select if the site collects Canadian GST tax. Special prompts for Canadian GST appear in the Tax Rate File.                                                                                                                                                                                                                    |
| Cardload Recharge Dept                | Select to assign the department number for cardload recharge.                                                                                                                                                                                                                                                                  |
| Cash Drawers Connected                | Enter the number of cash drawers connected to this register (1 - 2).                                                                                                                                                                                                                                                           |
| Cash Underrun Auto Refund             | If disabled, cashier must complete the underrun transaction by selecting a MOP. If enabled, when cashier claims the fuel sale, amount is automatically refunded.                                                                                                                                                               |
| Check Drawer Amount on Safe Drop      | Select to compare the amount of the MOP entered to the calculated amount currently in the drawer.                                                                                                                                                                                                                              |
| Count Underrun Customers              | When a cashier completes a prepay underrun transaction, the underrun customer count is incremented in the Summary Report, Shift Report, and Daily Report with the attribute “Underrun Customer”.                                                                                                                               |
| Disable Error Correct Key             | “Error Correct” key is not displayed on the POS touch-screen when this parameter is enabled.                                                                                                                                                                                                                                   |
| Discount Denomination                 | Refer to Discount Denominations for configuring discounts.                                                                                                                                                                                                                                                                     |
| Discount Type – Pct or Amt            | <p>Select the type of discount to apply when the [DISC] key is used.<br><strong>Percent</strong> — The discount is calculated as a percentage of the price and then subtracted from the price of the item.<br><strong>Amount</strong> — The discount is directly subtracted as a dollar amount from the price of the item.</p> |
| Display PLU not found Department List | Select to set a department number to assign to PLUs that are not in the PLU department list.                                                                                                                                                                                                                                   |
| Drawer Alarm Timer                    | Enter the number of seconds a cash drawer is allowed to remain open before an alarm is triggered (0 - 99).                                                                                                                                                                                                                     |
| Drawer Open During Sale               | Select to allow the cash drawer to remain open during transactions. (If not selected, the cash drawer must be closed before the next transaction can be started.)                                                                                                                                                              |
| Employee Number Login                 | When this feature is enabled, a cashier can login to the register using their Employee Number instead of their cashier record.                                                                                                                                                                                                 |
| Enable Managed Update                 | Enable to provide an interim approval step during the PLU file update process and to allow updates to take effect within the POS system immediately upon approval. No restart required after approval.                                                                                                                         |
| Enable Receipt Tax Detail             | Enable to print the tax details on the receipt. If disabled, tax details will still be printed if a taxable rebate is in the transaction.                                                                                                                                                                                      |
| Enable Auto Settle Overrun            | Select to determine whether to apply a charge on a prepaid sale in case of an overrun.                                                                                                                                                                                                                                         |
| Error Correction Security Level       | Select to set the security level required to perform an \[ERROR CORR] on an item in a transaction.                                                                                                                                                                                                                             |
| Error Message Prompt Timer            | Enter the length of time (in seconds) that error messages display (2 - 30).                                                                                                                                                                                                                                                    |
| Fixed Discount Rate                   | If “Is Fixed Discount” is selected, enter the percent or amount (set in “Discount Type”) that is automatically applied when the \[DISC] key is pressed.                                                                                                                                                                        |
| Force DOB on ID Check                 | Select to force ID checks by displaying messages, beeping, and restricting sales until a birth date is entered, scanned, or swiped.                                                                                                                                                                                            |
| Force No Sale Print                   | Select to print “No Sale” on the receipt and the journal when the cashier presses \[No Sale] in Sales mode.                                                                                                                                                                                                                    |
| Force Refund Print                    | Select to print a refund receipt when the cashier performs a refund in Sales mode.                                                                                                                                                                                                                                             |
| Force Void Line Print                 | Select to print “Void Line” on the receipt and journal when the cashier voids a line in Sales mode.                                                                                                                                                                                                                            |
| Force Void Transaction Print          | Select to print “Void Ticket” on the receipt and journal when the cashier voids a ticket in Sales mode.                                                                                                                                                                                                                        |
| Fuel Discount                         | Enter the dollar amount per gallon discount that is applied when a fuel discount key is used (0.00 – 99.99).                                                                                                                                                                                                                   |
| Fuel Discount Title                   | To rename Fuel Discount with a descriptive name, enter up to 30 characters.                                                                                                                                                                                                                                                    |
| Idle Prompt Displays Due Sale         | Select to display “No Due Sales” when the terminal is idle, and no fuel transactions are due.                                                                                                                                                                                                                                  |
| Is Cashier # Required for Each Sale   | Select to require the cashier/employee number and password before starting each sale.                                                                                                                                                                                                                                          |
| Is Fixed Discount                     | Select to automatically enter discounts (set in “Discount Type” as a percent or amount) for the amount entered in “Fixed Discount Rate” when the \[DISC] key is pressed.                                                                                                                                                       |
| Is Sub-total Required                 | Select to require pressing the \[TOTAL] key before the MOP is chosen.                                                                                                                                                                                                                                                          |
| Is Total in Double Wide Characters    | Select to print the transaction total in double-wide characters on the receipt and journal.                                                                                                                                                                                                                                    |
| Maximum Till Transaction Amount       | Enter the maximum transaction amount (Max: 9999.99).                                                                                                                                                                                                                                                                           |
| Maximum Amount                        | Enter the maximum amount that any one department item may cost (0.00 – 9999.99).                                                                                                                                                                                                                                               |
| Maximum Discount                      | Enter the maximum discount (either percent or dollar) that can be applied to an item when using the \[DISC] key (0.00 – 99.99).                                                                                                                                                                                                |
| Maximum Quantity                      | Enter the maximum quantity of any one item that may be sold in one transaction (0.00 – 9999.99).                                                                                                                                                                                                                               |
| Minimum Amount                        | Enter the minimum amount that any one department item may cost (0.00 – 9999.99).                                                                                                                                                                                                                                               |
| Minimum Discount                      | Enter the minimum discount that can be applied to an item when using the \[DISC] key (0.00 – 99.99).                                                                                                                                                                                                                           |
| Money Order Low                       | Enter the number of checks remaining before an alarm message indicates that the money order machine needs more checks loaded (0 - 99).                                                                                                                                                                                         |
| One Cashier per Drawer                | Select to limit login to one cashier per cash drawer until totals are closed.                                                                                                                                                                                                                                                  |
| Open Drawer Cashier Close             | Select to close the open drawer before another cashier can use it.                                                                                                                                                                                                                                                             |
| PLU Not Found Department              | Enter a department number to assign to PLUs that are not on the PLU department list.                                                                                                                                                                                                                                           |
| Prepaid Card Activate Department      | Enter the department number for prepaid card activation sales transactions.                                                                                                                                                                                                                                                    |
| Prepaid Card Recharge Department      | Enter the department number for prepaid card recharge sales transactions.                                                                                                                                                                                                                                                      |
| Print Receipt                         | Select to print a receipt for every transaction.                                                                                                                                                                                                                                                                               |
| Print UPC on Receipt                  | When enabled, the actual UPC or PLU will be printed on the receipt along with the description.                                                                                                                                                                                                                                 |
| Prompt Dine In                        | Select to prompt for dine-in orders at a food kiosk.                                                                                                                                                                                                                                                                           |
| Prompt Food Order Name                | Enable to prompt for entering a customer name for food orders.                                                                                                                                                                                                                                                                 |
| Prompt Food Order Phone Number        | Enable to prompt for entering a customer phone number for food orders.                                                                                                                                                                                                                                                         |
| Prompt Loyalty for PLU Not Found      | When enabled, if a scanned barcode or manually entered number is not found in the PLU list, the system prompts the user if it is a Loyalty Card.                                                                                                                                                                               |
| Register Time-Out Timer               | Enter the number of minutes after which an idle terminal automatically switches out of Sales mode (001 – 999).                                                                                                                                                                                                                 |
| Release Terminal During Close         | Select to allow the terminal to return immediately to Sales mode after a shift or daily close.                                                                                                                                                                                                                                 |
| Reminder to Use Imprinter             | Determines whether a message reminds the cashier to use the imprinter after completing a Manual Credit MOP transaction.                                                                                                                                                                                                        |
| Reset Display on Drawer Close         | Idle sales message returns when the drawer closes.                                                                                                                                                                                                                                                                             |
| Reset Display Time-out Value          | Enter the time (in seconds) before the idle sales message returns (2 – 3600).                                                                                                                                                                                                                                                  |
| Stack Manual Discount                 | If enabled, multiple manual discounts can be applied on a line item.                                                                                                                                                                                                                                                           |
| Store Number                          | Enter the store identifier (1 - 5 characters).                                                                                                                                                                                                                                                                                 |
| Value Added Tax (VAT)                 | Select if value-added tax (VAT) is collected at the site.                                                                                                                                                                                                                                                                      |
| Log In Message                        | Enter or edit the message displayed when Sales is entered.                                                                                                                                                                                                                                                                     |
| Log Out Message                       | Enter or edit the message displayed when Sales is exited.                                                                                                                                                                                                                                                                      |
| Register Banner                       | Use to define the message that appears on the customer display when no transactions are in process.                                                                                                                                                                                                                            |
| Register Line 1 and Line 2            | Enter the messages for lines 1 and 2 (up to 80 characters).                                                                                                                                                                                                                                                                    |
| Rotate Display                        | Select a rotation option — None, Line 1, Line 2, Both.                                                                                                                                                                                                                                                                         |

#### Sales Login/Logout Message

Use to enter messages that are displayed when an employee logs in or out of Sales mode.

| Field/Button               | Allowable Value/Function                                            |
| -------------------------- | ------------------------------------------------------------------- |
| **Log In - Show Log-In**   | Select to display the prompt when the user logs on                  |
| **Message to Sales**       | Enter or edit the information displayed when Sales is entered.      |
| **Log Out - Show Log-Out** | Select to display the prompt when the user logs out                 |
| **Message of Sales**       | Enter or edit the information displayed when Sales Lines is exited. |

#### Menu Keys

Refer to \[`Menu Key Configuration`]

#### Register

The Register Configuration form is used to set up banners, logos/slogans, soft keys, and copy registers for the site.

#### Banner

Use to define the message that appears on the customer display when sales transactions are not in process.

\| Field/Button | Allowable Value/Function | |-------------|-------------------------| | Register | Select the register. | | Line 1 and Line 2 | Enter the messages for lines 1 and 2 (alphanumeric, up to 80 characters). | | Rotate | Select a rotation option — None, Line 1, Line 2, Both. |

#### Logos/Slogans

Use to enter the information that prints in the header (logo) and footer (slogan) of receipts.

| Field/Button                  | Allowable Value/Function                                 |
| ----------------------------- | -------------------------------------------------------- |
| **Register**                  | Select the register.                                     |
| **Ticket Logo/Ticket Slogan** | Enter the information that appears on register receipts. |
| **Enabled**                   | Select to enable each logo and/or slogan.                |
| **Mode**                      | Select Single- or Double-wide characters.                |
| **Alignment**                 | Select Left, Right, or Center.                           |

#### Soft Keys

Refer to \[`Soft Keys`]

#### Copy Registers

Use to copy files from one register to another.

| Field/Button                 | Allowable Value/Function                                               |
| ---------------------------- | ---------------------------------------------------------------------- |
| **Select Register - Source** | Select the register to copy.                                           |
| **Register**                 |                                                                        |
| **Destination Register**     | Select the register to which you want to copy files.                   |
| **Select Files to Copy**     | Select the files you want to copy: Banners, Soft Keys, Logos, Slogans. |

### Touch Screen

The Touch Screen Configuration forms allow you to configure fuel keys, assign buttons, define the parked menu panel, and orient the touch screen. :::note Refer to the Base 53 and Higher feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

### Self Checkout

Self Checkout (SCO) is a self-checkout POS application for C-Stores implemented on B53 and Higher UI. :::note Self Checkout will be disabled on future releases except for customers who have licensed it from Verifone separately. :::

:::note Refer to the Self-Checkout feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

### Self Checkout (SCO) Monitoring

Device monitoring is a feature to monitor configured devices from monitoring devices such as Cashier operated POS, Attendant handheld device or any remote machine. Self Checkout devices can be configured to be monitored through the Touch Screen configuration.

#### Self Checkout Monitoring Buttons

The following buttons represent Self Checkout device status:

| Icon | Description                                                                                                                                                                            |
| ---- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
|      | Self Checkout device is offline                                                                                                                                                        |
|      | Self Checkout device is in non-sales mode                                                                                                                                              |
|      | Self Checkout lane is closed                                                                                                                                                           |
|      | Self Checkout device is in Idle mode                                                                                                                                                   |
|      | <p>Transaction suspended.<br><br>Transaction gets suspended either because customer chooses to pay at counter or cashier suspends the transaction. The SCO is moved to idle state.</p> |
|      | Transaction suspend: initial state.                                                                                                                                                    |
|      | Customer checked in to the Self Checkout device                                                                                                                                        |
|      | Customer added items to the cart.                                                                                                                                                      |
|      | The monitoring button shows the number of items and amount.                                                                                                                            |
|      | Customer is making a payment.                                                                                                                                                          |
|      | Customer’s payment failed.                                                                                                                                                             |
|      | Customer requested help.                                                                                                                                                               |
|      | Customer requested help after adding items.                                                                                                                                            |
|      | Customer requested help; but is proceeding with sale.                                                                                                                                  |
|      | Customer requested help; but is proceeding with payment.                                                                                                                               |
|      | Customer requested help; but, proceeded with payment and payment failed.                                                                                                               |
|      | Cashier logged in while Self Checkout device is in Idle mode.                                                                                                                          |
|      | Cashier logged in to Self Checkout device while the device is in “Customer Checked In” mode.                                                                                           |
|      | Cashier logged in to Self Checkout device during sales.                                                                                                                                |
|      | Customer added age restricted item and called for cashier assistance.                                                                                                                  |
|      | Customer had previous items added and then added age restricted item and called for cashier assistance.                                                                                |

#### Self Checkout Monitoring Configuration

:::note Refer to the Base53 and Higher UI user reference documentation for information on how to configure the touchscreen UI. The User Reference is available on Premier Portal. :::

1. From Store Operations > Touch Screen > Panel Configuration select Add Item to an Item Panel.
2. In the new row added, select Monitoring from the drop down.
3. Select Self Checkout as the Device Type and select the device ID of the self checkout.
4. Go to Store Operations > Touch Screen > Screen Configuration and add the item panel containing the Self Checkout monitoring item to a screen panel.

:::note SCO has to be logged in at least once before configuring for SCO monitoring; else the device id will not be listed. :::

5. Go to Store Operations > Touch Screen > Register Configuration and assign the screen to a register.&#x20;

### House Account

A House Account is a non-network, local store account that is set up with credit granted at the discretion of the site manager. House accounts require an account number, which prints on the receipt. Verifone Commander keeps and reports totals for House accounts but does not keep records of individual transactions or balances. Follow store policy to manually record transactions.

:::note Refer to the In-House Accounts feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

**“force.InHouse.PayInOut”** in **ConfigClient > Initial Setup > System Properties** should be set to Yes to enables sites to assign In House Accounts with Pay In and Pay Out.&#x20;

| Field/Button            | Allowable Value/Function                                                                                 |
| ----------------------- | -------------------------------------------------------------------------------------------------------- |
| **Add**                 | Click to add a new account. The account is automatically enabled unless you clear the Enabled check box. |
| **Delete**              | Select to delete the selected account.                                                                   |
| **Account Number**      | Enter the account number (alphanumeric, 1 - 20 characters).                                              |
| **Account Name**        | (Optional) Enter the name of the customer (alphanumeric, 0 - 20 characters).                             |
| **Enabled**             | Select to enable the account.                                                                            |
| **Prompt for Sub Acc#** | Enable to prompt for sub-account number.                                                                 |
| **Trigger Function**    | Select what triggers an "In-House Account? \[Y/N]" prompt.                                               |

### Group Price Change

:::note Refer to the Group Price Change feature reference documentation for information on this feature. The Feature Reference is available on The Feature Reference is available on Premier Portal. :::

Use to change the prices of multiple PLUs assigned to a selected department at the same time.

To change a group of prices:

1. In the department list, select the department that contains the products needing the price change.
2. Click an adjustment type — Increase, Decrease, Make all prices the same.
3. Click an adjustment option — Amount, Percent.
4. Enter the adjustment amount as dollars and cents (0.00 - 9999.99) or percent (000.000 - 9999.99).
5. Select the PLUs to be adjusted.

* Click Select All to select every PLU in the department.
* Select several adjacent PLUs by using SHIFT and click.
* Remove selections by clicking Select None.

6. Click OK.

### Managed Updates

The Managed Updates feature provides an interim approval step during the PLU file update process and allows updates to take effect within the POS system immediately after approval. The business purpose behind the approval step is to allow store management to use a 3rd party system (SAP Retail Store) to identify, print and update shelf labels as needed for price changes prior to those changes being reflected within the POS system.

#### Enable Managed PLU Update

From **Store Operations > Sales > Sales Configuration**, enable “**Enable Managed Updates**”.&#x20;

#### Managed Update Security Level

In **Store Operations > Sales > Sales Configuration > Managed Update Security Level**, enter the security level of the manager who can apply the update.&#x20;

#### "Apply Updates" Touchscreen Button

In **Store Operations > Touch Screen > Panel Configuration**, select “Add Item” and type as “Function”. Select “Apply Updates” to assign this function to a touch screen key or Topaz POS key for easy access to the function.  :::note Refer to the Base 53 and Higher feature reference documentation for information on configuring the touch screen. The Feature Reference is available on The Feature Reference is available on Premier Portal. :::

#### Pending Updates

View Pending Managed Updates from **Store Operations > Managed Updates**.&#x20;

### Fiscal Receipt

This feature is available for LAC countries. In many LAC countries, controlled receipts (e.g. “Facturas”) are printed from the POS. The receipts typically include a controlled sequence number and other POS controlled data.

After all MOPs are processed, the application would determine which of the five types of receipts to print.

The five types of receipts are:

* Fiscal Sale
* Fiscal Refund
* Fuel Voucher
* Non-Fiscal Network
* Pump Test

#### Site

Use this form to configure site-level fiscal receipt configuration.&#x20;

#### Register

This form is used to configure the different types of fiscal receipts. The different types of fiscal receipts that can be configured with this form are Fiscal Sale, Fiscal Refund, Fuel Voucher, Non-Fiscal Network and Pump Test.

#### Fuel Flat Tax

This form allows the configuration of two flat taxes per fuel grade. The flat tax is a fix amount per unit of measure (for example, 11 cents per gallon of a specific fuel product). Depending on the country, the format of this amount is defined as maximum 3 digits to the right and 4 to the left of the decimal point (e.g., ‘XXXX.YYY’).

:::note: Guatemala has only one fuel flat tax per fuel grade. :::&#x20;

| Field/Button             | Allowable Value/Function                                                                                  |
| ------------------------ | --------------------------------------------------------------------------------------------------------- |
| **Fuel Flat Tax Name**   | <p>Tax name. Allows up to 10 characters.<br><strong>Note:</strong> Guatemala only needs 3 characters.</p> |
| **Fuel Flat Tax Amount** | Tax amount.                                                                                               |

The POS prints receipts with the Flat Tax information.

#### Tax Exemption

Use the form to configure tax exemption if a Tax Exemption MOP code is used.

| Field/Button                     | Allowable Value/Function                                                                                                                                                                                          |
| -------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Tax Exemption Type Name**      | This name is associated with the acronym of the government entity that is tax-exempt (e.g., “SAR” = “Servicio de Administración de Rentas” – Revenue Management Department). Alphanumeric, maximum 20 characters. |
| **Tax-Exempt Purchase Order #**  | Alphanumeric, maximum 20 characters. (Description prompt needed)                                                                                                                                                  |
| **Tax-Exempt Customer #**        | Alphanumeric, maximum 25 characters. (Description prompt needed)                                                                                                                                                  |
| **Exempt Merchandise Sales Tax** | Select to exempt merchandise sales tax. This parameter is enabled by default. Greyed out in this screen in base 52.                                                                                               |
| **Exempt Fuel Sales Tax**        | Select to exempt fuel sales tax. Greyed out in this screen in base 52.                                                                                                                                            |
| **Exempt Fuel Flat Taxes**       | Select to exempt fuel flat tax. Greyed out in this screen in base 52.                                                                                                                                             |

#### System Properties

The following system properties should be enabled for Honduras:

* Print Tax-Exempt Total Line: If this is enabled, the system should print the line “Exento Imp.” + \[tax-exempt total amount].
* Print Discounts Line: If this is enabled, the system should print the line “Descuentos y Rebajas ” + \[sum of all amounts discounted].
* Print Subtotal Line Label: If this is enabled, the system should print the label “Subtotal Gravado” in the subtotal line
* Print Line Before Total: If this is enabled, the system should print a line before the total amount

#### Currency Selection

Use this feature if the country is using a different currency than US dollar.

In Verifone Commander Configuration Client, the currency of the country should be selected from **Payment Controller > EPS Configuration > EPS Global Configuration**.

#### Charity Donations

The charity donation feature enables a customer to donate certain amount to a charity.

The system prompts customers during tendering process for charity donation. Customers are asked if they wish to make a charity donation.

When the customer is using Cash as MOP there are two options that can be enabled from configuration client to be presented to the customers on the PIN pad:

* Donate change amount (rest for charity) and is calculated as the difference between the amount due and the amount paid.
* Round to next dollar amount which rounds off their transaction to the next whole dollar. The donation amount is the difference between the total amount of the purchase and the rounded dollar amount.

When the customer is using ‘Credit’ or ‘Debit’ cards as MOP, they will be presented with three preset contribution amounts configured in configuration client or two preset contribution amount and a round to next dollar amount.

The chosen selection is shown on the receipt, where it reflects the contribution. Only one charity can be active for any site.

The following configurations should be done before configuring the Charity Donations Configuration form:

1. Create a department for charity with NACS code 971. Refer to the Department Sales topic in this document for more information on creating departments.
2. For Cash MOP, “Tender Amount Required” parameter should be enabled. Refer to the Method of Payment topic in this document for more information.

#### Charity Donations Configuration

#### Charity Donation Receipts

**Outdoor Receipt**

**Indoor Receipt**

#### Close Lane

This is a Self Checkout feature.

:::note Refer to the Self Checkout feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

## Promos and Discounts

### NAXML Deal

Refer to NAXML Deal

### POP Discount

:::note Refer to the POP Discount feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

### Coupon Scanning Configuration

:::note Refer to the Coupon Scanning Feature Reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

### Discount Denominations

This feature is used to configure various discounts which can be selected by the cashier during a sale. When the cashier selects the discount key (hard key, soft key, or touch-to-modify menu), any configured discounts are displayed as part of the discount overlay.

:::note This feature should be enabled in Configuration Client > Store Operations > Sales Configuration. :::

| Field/Button  | Allowable Value/Function                                               |
| ------------- | ---------------------------------------------------------------------- |
| **Discounts** | Click to add discount name. A total of 16 discounts can be configured. |
| **Delete**    | Select to delete the selected discount and click Save.                 |
| **Name**      | Enter the discount name.                                               |
| **Type**      | <p>- <strong>Percent</strong><br>- <strong>Amount</strong></p>         |
| **Amount**    | Enter the percentage or amount discount.                               |

## Forecourt

### DCR

Refer to \[`Configuring Dispenser Card Readers`]

### Fuel

Refer to \[\`Fuel Configuration']

### Fuel Prices

:::note Refer to Cash Credit Pricing for more information on this feature. ::: The Pricing Manager form is used to set up fuel pricing, including tier pricing. Tier Two pricing can be set up at any time but does not take effect until the appropriate information is entered in the “Start Tier 2 Pricing” and “Number of Tier Hours” parameters in Fuel > Site Parameters > Fuel Site Parameters.

Select the product, then double-click the Price text boxes and enter the price (0.000 - 9.999). The price of all products changes to match the price entered in the top text box after ENTER is pressed. Prices can be edited if necessary.

:::note When entering a price, take care when placing the decimal point. For example, to change a price to 1.159, enter it as written here. To change a price to 1.500, enter the trailing zeros. :::

If you only change fuel prices, for the changes to take effect, initialize Fuel Prices by selecting:

* Forecourt > Initialization > Fuel Prices If you change other fuel parameters as well as prices, you will need to initialize Fuel and DCRs for the changes to take effect. To do this, select both of the following:
* Forecourt > Initialization > Fuel
* Forecourt > Initialization > DCRs

:::note Make sure that your fueling positions are not in use when initializing any Fuel Prices, Fuel, or DCRs. :::

The fuel prices have a limit of four characters and can take only a maximum of $9.999 with three decimal places. This document shows how to configure a site to set fuel prices to 2 decimal places to support price that are greater than $9.999 per gallon in the $xx.xx format.

#### Configuring Fuel Prices for 2 Decimal Places

1. Go to Forecourt > Fuel > Fuel Config Pending > Site Parameters and disable “Force .9 Cents Per Gallon”.
2. Go to Forecourt > Fuel Prices Pending and change all existing product prices with third decimal place to 0 (eg: from $2.152 to $2.150).
3. Go to Forecourt > Fuel > Fuel Config Pending > Site Parameters and change “PPU Decimal Position” and “Total Decimal Position” to “2”.
4. Go to Forecourt > Fuel Prices Pending and change the prices of the product per gallon to the $XX.XX format for both Tier One and Two Prices.

Feature Limitations

* Sites can be configured to take fuel prices with either two or three decimal places; $xx.xx or $x.xxx. Sites cannot have mixed decimal positions while using a single Verifone Commander.
* At two decimal sites, prices that have 3 decimal places (eg. $4.299) will only be calculated at the 2 decimal amount (eg. $4.29).
* By default, sites are configured for 3 decimal places in $x.xxx format.

### DCR Keys

Each DCR should be assigned to a DCR key configuration. If sites have a mix of DCRs with and without alphanumeric capabilities, sites would require to create 2 or more DCR key configurations.

The configuration for DCRs that are alphanumeric should have the “Enable Alphanumeric” checked, and NOT checked for the DCRs that only accept number input.

Use to configure DCR keys for the different DCR positions.

| Field/Button            | Allowable Value/Function                                                                                                                                                                                             |
| ----------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Add**                 | Click Add to configure new DCR Keys layout.                                                                                                                                                                          |
| **Delete**              | Select to delete the selected DCR Keys layout.                                                                                                                                                                       |
| **Label**               | Label the new DCR Keys layout.                                                                                                                                                                                       |
| **Enable Alphanumeric** | The configuration for DCRs that are alphanumeric should have the “Enable Alphanumeric” checked to use the alphanumeric keys layout. This field should **NOT** be checked for the DCRs that only accept number input. |
| **Assign Positions**    | Click assign positions and select the DCR that can be used for entering alphanumeric characters. The DCRs that do not have alphanumeric capabilities are grayed out.                                                 |
| **/#Rows**              | Number of rows for the DCR Keys layout.                                                                                                                                                                              |
| **/#Columns**           | Number of columns for the DCR Keys layout.                                                                                                                                                                           |
| **Assign Positions**    | Select to assign the DCR Keys layout to the DCRs in the site.                                                                                                                                                        |

:::note Click on the keys to configure the values. :::

#### DCR Idle Screen

The DCR Idle Screen Configuration form is used to set up what displays on the DCR screen when not in use.

#### Outdoor TAVE

**Not Implemented for this base.**

### Cash Acceptor

The Cash Acceptor Configuration form is used to set up and edit cash acceptors at the site. Site Information determines the behavior of all cash acceptors at a site. Attributes determines the behavior of a specific cash acceptor at a specific fueling point. Select the Cash Acceptor on the list on the bottom of the form, then select the value check boxes that are applicable for that Cash Acceptor.

#### Fuel Tax Exempt

The Fuel Tax Exemption Configuration form allows taxes to be removed from a post-pay fuel sale by setting up one to five fuel tax exemptions. Each exemption can either be setup by the Amount Per Gallon or the Tax File Entry that is setup in **Store Operations > Payment > Tax Rates**, or Both.

The Fuel Tax Exempt Receipt Lines section is used to enter up to four lines of text that you want to print on the header of Fuel Tax Exemption receipts.

#### Rapid Change Fuel Config

Rapid Change Fuel configuration is configured from **Forecourt > Rapid Change Fuel Config**.

This feature allows the cashier to change the pump’s service level and auto approval rapidly at the pump using the POS without having to change the fuel configuration using Verifone Commander Configuration Client or without manager intervention.

To change the fuel configuration level from the POS, the cashier should access **CSR Functions > Fuel Manager > Rapid Change Fuel Configuration**.

#### Unattended DCR

:::note Refer to the Unattended Fueling feature reference documentation for information on this feature. The Feature Reference is available on the Premier Portal. :::

### Devices

#### Car Wash

Refer to \[`Car Wash Configuration`]

#### Car Wash Paypoint

::::note Refer to the Car Wash Pay Point feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

#### Tank Level Sensor

The TLS Configuration form is used to set up and edit Tank Level Sensor Parameters.

#### Fuel Price Display

The Fuel Price Display Configuration form is used to set up and edit the Fuel Price Display sign to suit the requirements of the site. After configuring or changing Fuel Price Display, initialize fuel prices for the changes to take effect. To initialize fuel prices, select **Forecourt > Initialization > Fuel Prices**.

:::note Make sure that your fueling positions are not in use when initializing Fuel Prices. :::

#### Fuel Price Display Initialize

Fuel Price Display Initialize should only be used after the sign has been repaired or if it is displaying pricing errors after losing power. In these cases, do the following:

Devices > Initialization > Fuel Price Display Vending Machine

:::note This feature is no longer supported. :::

#### Attendant Payment Terminal

Attendant Payment Terminal (APT) is a mini-POS used in the forecourt. Use **Devices > Attendant Payment Terminal** to configure APT. :::note Refer to Attendant Payment Terminal (APT) reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

#### Global

This form is used to enter the configuration that is valid for all APT terminals.

#### Terminal

Use the form to enter each terminal detail.

#### Vista Devices

:::note Vista Devices CSC and CCW are not supported anymore. ::: **Carbon Verifone Commander Workstation (CCW)** is a POS application for retail shops implemented on Carbon 10. The implementation leverages Verifone Commander Site Controller’s capabilities for item management, payment and communication.

Use **Devices > Vista Devices** to configure CCW.

:::note Refer to CCW reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

#### Food Service

:::note Refer to all the iOrder reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

The Food Service form is used to configure the iOrder Kiosk connection parameters.

### Cash Recycler

Refer to the Self Checkout Feature Reference for more information on this feature. The feature reference is available on Premier Portal.

## Payment controller

### POS Configuration

Refer to \[`Configuring Network Functions`]

### Mobile Payment Configuration

:::note Refer to the Mobile Payment feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

#### EPS Prepaid Configuration

The EPS Prepaid Configuration form is used to configure prepaid cards, PIN-based products, and money transfer cards.

* Prepaid card (Stored value card or SVC) – A cash value is placed on the card, which can then be used for purchases until the cash value is used up. The card may be recharged with additional cash value.
* PIN-based product – The customer buys the PIN-based product and uses the PIN (Personal Identification Number) printed on the receipt or card to activate the product.
* Money transfer card – The customer presents the card and cash at the site, designates the payee by number, and the electronic payment is made.

1. Select the InComm in the Network Name dropdown menu.
2. Check the Prepaid Enabled box.
3. Click Add.
4. Select the appropriate prepaid department from the Department dropdown list.
5. Check the Enabled and/or Pre-Validate boxes.

* The Enabled check box is used to enable or disable the prepaid department.
* The Pre-Validate check box is used to specify whether an InComm Pre-Authorization Request needs to be sent to the host when selling items from a prepaid department. The Pre-Authorization Request is used to verify whether the actual transaction can be successfully completed before the payment is tendered.

6. Click on Reprint Security Level column to set security levels for reprinting the receipt at the POS.
7. Three types of message prompts is displayed to cashier during prepaid card activation / recharge process:

* **Guideline message prompt:** Guideline Prompt when enabled, prompts the cashier when a prepaid card activation item (ProdCode: 560 to 575) is added to the ticket. This message instructs the cashier to follow guidelines to avoid fraud. Default message for guideline prompt is “Please ensure you are following AML fraud guidelines by not selling more than $1900.00 in cards to one customer - The limit is $999.00 in the state of Arizona.”
* **Purchase message prompt:** Purchase Prompt when enabled, prompts the cashier if PIN Activation item (ProdCode = 560) is added to the ticket. Purchase prompt appears after the Guideline Message Prompt if guideline prompt is enabled. Purchase prompt is to instruct the cashier not to give PIN numbers for prepaid cards over the phone. The Purchase prompt has YES and NO buttons. If cashier responds YES, then PIN Activation item can be added to the ticket. If cashier responds NO, then PIN Activation item is not allowed for sale and the item is removed from the ticket with an error message. Default message for purchase prompt is “Is this purchase being made by someone on site?”
* **Cancel message prompt:** When cashier responds with a NO to the Purchase Prompt, the PIN Activation item is removed from the ticket and Cancel Prompt message (if enabled) is shown to the cashier. This prompt is to inform cashier that the item is being removed as it cannot be sold. Default message for Cancel Prompt is “PIN numbers are never to be given to anyone over the phone - NO EXCEPTIONS!”

8. Click Save to save the configuration.

#### Third Party Product Configuration

Third Party Product Configuration feature provides the ability to support financial transaction services provided by the Cullinan Group.

:::note Refer to all the Cullinan Feature Reference documentation for information on this feature. The Feature Reference is available on Premier Portal :::

#### EPS Configuration

#### EPS Global Configuration

**EPS**

Refer to \[`EPS`]

**POP**

Refer to \[`POP`]

**PINPAD Message**

Refer to \[`PINPAD Message`]

**Loyalty**

Refer to \[`Loyalty`]

**Trigger Pull Configuration**

The Trigger Pull Function allows the host network to access the site any time for debug, support or application update.

**EMV Configuration**

:::note Refer to the EMV feature reference documentation for information on this feature. The Feature References are available on Premier Portal. There are two feature references for EMV, “Inside EMV Feature Reference” and “Outside EMV Feature Reference”. Refer to both the feature reference documents to understand this feature. :::

**EMV Initialization**

:::note Refer to the EMV feature reference documentation for information on this feature. The Feature References are available on Premier Portal. There are two feature references for EMV, “Inside EMV Feature Reference” and “Outside EMV Feature Reference”. Refer to both the feature reference documents to understand this feature. :::

**Quick Chip Configuration**

Refer to Quick Chip Configuration

#### PTPE

**Not Implemented for this base.**

#### Full-Service Attendant Configuration

:::note Refer to the Full-Service Attendant feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

### FEP

Use this tab to enable Full-Service Attendant (FSA) cards.

1. Select FEP Enabled
2. Click Save

### FEP Card

Use this tab to configure each FSA cards.

### InComm Configuration

:::note Refer to the InComm Configuration feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

**FEP**

1. Check FEP Enabled.
2. Enter Terminal ID.
3. Enter Dealer ID.
4. Enter IP Address (XXX.XXX.XX.XX).
5. Enter Port Number (XXXX).
6. Enter Store ID.
7. Enter Gift Receipt Printing Option: Never, Always, Prompt Cashier
8. Enable Fallback (Y/N): The EPS prompts the enabling or disabling of Fallback Processing. Fallback involves a stand-in approval of activations in the event of network connectivity failure with the InComm host. After connectivity is established, the stored transactions are sent to the host when a response is received or a Daily Close is performed. Timeout reversal will be always supported.
9. Enter Fallback Transaction Limit.
10. Enter Fallback Dollar Limit ($0-9999).
11. Enter SAF Retry Interval (1-15 Minutes).
12. Enter SAF Retry Limit. **Note:** Zero means retry indefinitely.
13. Click Save to save the configuration.

**FEP Card**

1. Click Add
2. Enter Card Abbreviation
3. Enter Card Name
4. Enter Lower ISO
5. Enter Upper ISO
6. Enter Pan Length
7. Enter Send Track 1 Option: Dont Send, Send Primary, Send Secondary
8. Check Card Enabled to enable the card
9. Check Refund Allowed to allow refund on the card
10. Click Save to save the configuration

#### Payware Fleet Configuration

This form is used to enable and configure Payware Fleet Card transactions.

**FEP**

#### FEP Card

#### Loyalty Configuration

This form is used to enable and configure Loyalty Cards. :::note Refer to the Loyalty Sales feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

#### Punch Card Configuration

:::note This feature is yet to be implemented. :::

**Proprietary Fleet Configuration**

:::note Refer to the Proprietary Fleet Configuration feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

**FEP**

**FEP Card**

#### EZ - Receipt Configuration

This feature enables everyday customers to opt for getting receipts emailed instead of printed after a transaction. :::note Refer to the EZ – Receipt feature reference documentation for more information on this feature. The Feature Reference is available on Premier Portal. :::

### Reporting

#### Report Configuration

Refer to Report Configuration

#### Cashier Tracking

Refer to Cashier Tracking

#### Close Car Wash Paypoint Period

Refer to Close Car Wash Paypoint Period

#### Site Asset Data

Refer to Site Asset Data

#### Close Day Now

Refer to Close Day Now

#### Mobile Food Order Report

:::note Refer to the Mobile Food Order Feature Reference for more information on the feature. The Feature Reference is available on Premier Portal. :::

### Tools

#### Rule Manager

Use to configure rules that automatically comply with corporate policies, laws, and regulations, to limit the number of and amount of certain products that can be sold over a period to a customer.

To open Rule Manager, click Tools > Rule Manager.

Rule Manager allows you to:

* Activate/deactivate a rule
* Reorder rules (move up, move down)
* Modify a rule
* Create a copy of a rule, rename it, and modify it
* Create a new rule
* Delete a rule
* Set up fast food orders on POS. See “Fast Food Orders on POS.”

#### Activating or Deactivating a Rule

To make a rule active or inactive

* To activate a rule — Click the “Active” check box in front of the rule and click Save.
* To deactivate a rule — Clear the “Active” check box in front of the rule and click Save.

#### Creating a Rule

1. In Rule Manager, click Add.
2. Enter a name for the rule.
3. Enter a description (optional).
4. Enter Register number.
5. Select the scope of the rule:

* Transaction — The rule is evaluated at the time of sale.
* Line Item — The rule is evaluated when the item is entered as a line item.

4. Select the item that triggers the rule to be evaluated. Depending on the rule you are modifying, select one of the following:

* PLU
* Department
* Payment
* Transaction Begin
* Transaction End

5. Add conditions for the rule. Select the condition type from the drop-down list box.
6. Select the operator to apply to the rule. Operator types “equal to, not equal to, and like” appear for “PLU, Department, Product Code, and MOP” Condition Types. Operator types “equal to, not equal to, greater than, less than, greater than or equal to, and less than or equal to” appear for “Quantity and Amount” Condition Types.
7. Click “Edit” in Set Conditions section to select the PLUs or Departments or MOPs. Or add the quantity or amount for Condition Types, “Quantity” and “Amount”.
8. Click Edit in Available Actions section to determine the actions that occur when the rule is triggered, and the condition evaluates to true.
9. The available actions are:

* Alert Cashier: When the rule is triggered, alert the cashier.
* Apply Blue Law: When the rule is triggered, apply a blue law. **Note:** Blue Laws are set up in Store Operations > Restrictions > Blue Laws.
* Apply ID Check: When the rule is triggered, apply an ID check.
* Apply Min.Security Level Check: When the rule is triggered, check if the cashier has the minimum-security level to perform the transaction.
* Journal Event: When the rule is triggered, journal the event with a message.
* Veto: When the rule is triggered, prevent the transaction from taking place. For example, prevent a credit card MOP from being used when lottery is in the transaction.
* Enter/Select POS Kitchen Printer: When the rule is triggered, send the transaction to the selected kitchen printer.
* Send to Kitchen Display System via iOrder: When the rule is triggered, send the transaction to the Kitchen Display System (KDS).
* Add Receipt Message: When the rule is triggered, add a message on the receipt.
* Change Receipt Header: When the rule is triggered, change the receipt header.
* Add Item: When the rule is triggered, the selected menu key is displayed.
* Restricted Department: Select to add a restricted department.

10. Click Set Attributes to set actions for the selected action type.
11. Click Close
12. In Rule Manager, click Save.

#### Modifying a Rule

Rules can be modified to change:

* whether they act on a line item or a transaction,
* which event triggers the rule,
* which conditions are in effect for the rule,
* which actions occur when the rule is triggered. In Rule Manager, select the rule that you want to modify and click Modify.

#### Copying a Rule

The copy feature can be used to create the basis for a new rule. To copy a rule and rename it:

1. In Rule Manager, select the rule.
2. Click Copy. The copy is added to the end of the rule list, with \_0 appended to the end of the original name.

#### Deleting a Rule

To delete a rule

1. In Rule Manager, select the rule to be deleted.
2. Click Delete. The rule is deleted.

#### Fast Food Orders on POS

:::note Refer to the POS to iOrder Feature Reference documentation for more information on this feature. The Feature Reference is available on Premier Portal. ::: :::note Refer to the POS to iOrder Feature Reference documentation for more information on this feature. The Feature Reference is available on Premier Portal. ::: A kitchen printer can be installed, and the Rule Wizard can be used to create a rule that sends selected PLUs from the POS to the specific kitchen printer and prints a receipt.

1. Create a new rule. See “Creating a New Rule.”
2. Follow the procedure to create the rule. See “Creating a Rule.” Set the following attributes for the rule:

* Scope of the rule — Select Transaction.
* Trigger for the rule — Select Transaction End.
* Conditions — Enter PLUs for the rule and select “Like” as the operator to apply to the rule.
* Action — Select Send to Kitchen Printer and click Add.
* Further define Action — Select or enter the name of the specific kitchen printer.

3. Activate the rule. “See Activating or Deactivating a Rule.”
4. See “Store Operations > Menu Keys” to make the rule part of an Order Menu.

**Entering customer name for food orders taken at POS**

1. In Tools > Managed Modules:
   1. Select Kitchen Printer Service as kp.svc.POS
   2. Set System Hosting Kitchen Printer to 'sitecontroller'
   3. Click on Advanced Settings
   4. Select connection port and save
   5. Check Enable Kitchen Printer Service and save
   6. Click Tools->Refresh Configuration
2. In Tools > Rule manager, create new rule
   1. Select Scope as “Transaction”
   2. Select Trigger Type as “Transaction End”
   3. Select Condition Type as “Department” and Operator Type as “like”
   4. Select the food department
   5. In Available Actions, select “Enter/Select POS Kitchen Printer”
   6. In Set Attributes form, Select Kitchen Printer as “kp.svc.POS”
   7. Reboot Verifone Commander
3. In Store Operations > Sales > Sales Configuration:
   1. Select “Prompt Food Order Name”
   2. Select “Prompt Food Order Phone Number”

#### Managed Modules

Managed Modules is an interface for assigning port numbers and configuring communication parameters for hardware modules connected to the POS or Verifone Commander. The configuration changes do not require a reboot of the Verifone Commander or the POS. Based on the device type selected, the default communication settings are populated.

For any changes to be reflected in the system, select “Tools > Refresh Configuration” from Configuration Client and logout and login back to the POS.

Changes to Fuel Driver and DCR Driver modules need driver initialization from “Forecourt > Initialization > DCR/Fuel Driver”. Changes to Car Wash module need a DCR initialization from “Forecourt > Initialization > DCR”.

#### Current Configuration

The current configuration tab is used for viewing, adding or editing the port and communication parameters of each hardware module.

**Host Name**

Select the host to which the hardware module is connected. The host can be the Verifone Commander, or each POS controlled bfy the Verifone Commander.

**POS**

Use to add the port and enable the hardware module connected to each POS. Select the POS from the Host Name drop-down list. In order to switch ports, disable the device you want to move, as well as the device you want to move it to. Otherwise the Port Name drop-down only shows the port the device is already assigned to. :::note Most of these modules have feature references. Refer to the feature reference documentation for information on these modules. The Feature Reference is available on Premier Portal. :::

**Select Module**

**Check Scanner**

Use to add the port and enable check scanner.

**Coin Dispenser**

Use to add the port and enable coin dispenser.

#### DVR Logging Types

The Digital Video Recorder (DVR) feature provides a DVR interface to the Point of Sales (POS) System to detect and deter attendant fraud. The DVR broadcasts certain transactions performed on the POS terminal and displays these events with video images recorded at the time the events occurred. This provides video images of attendant actions coupled with a journal of events as recorded by the POS terminal. :::note Refer to the Digital Video Recorder Implementation Guide for information on this feature. The Feature Reference is available on Premier Portal. :::

The “DVR Logging Type” configuration allows selecting types or classes of DVR events to be recorded.

#### DVR Journal

Use this form to add the port and enable DVR device.

#### PIN Entry Device

Use to add the port and enable PIN Entry Device.

#### Customer Display

Use to add the port and enable Customer Display of C18 POS.

On the back of the main C18 display are two USB ports located just below where the main display is mounted to the "handle bar". Connect the C18 Customer Display cable to one of the USB ports. :::note Refer to the C18 Customer Display Installation guide for more information. The document is available on Premier Portal. ::: Reboot the C18 system and wait for the main display to show "C18 Press Enter or touch screen to log in".

1. De-select Enable Device
2. For "Port Name", select USB Display. **Note:** If "USB Display" is not shown in the list, make sure to connect the C18 Customer Display and reboot the POS.
3. Click ‘Save'.
4. Select the "Enable Device" checkbox and Click "Save" again.
5. Restart POS

When the application starts, Register Closed is displayed on the Customer Display. After logging in to 'Sales', the phrase "Thank You" should be scrolling across the Customer Display.

#### Scanner

Use to add the port and enable scanner.

#### Secondary Scanner

Use to add the port and enable secondary scanner.

#### Receipt Printer

Use to add the port and enable Receipt Printer.

### Drive Thru Configuration

Use to add the port and enable drive through configuration.

#### Controller

Use to add or edit the port and communication parameters of each hardware module connected to the Verifone Commander. Select the Verifone Commander from the Host Name drop-down list. :::note Most of these modules have feature references. Refer to the feature reference documentation for information on these modules. The Feature Reference is available on Premier Portal. :::

#### Select Module

**Auxiliary Forecourt**

:::note Refer to the Auxilliary Forecourt feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. ::: Use to configure Auxilliary Forecourt devices like Aux Pos, Petro Vend and Wetstock Management Devices.

1. Click Advanced Settings next to Auxiliary Forecourt Channel 1
2. Select Enable to enable Channel 1
3. Select the Device Type: Aux Pos, Petro Vend or Wetstock Management
4. Assigns the Verifone Commander serial port to be used for the Channel
5. Click Advanced Settings of Fueling Positions if the Device Type is Petro Vend. A Petro Vend device on a channel can control 16 fueling positions.
6. Click Save on the Channel 1 Fueling Positions to go back to the Auxiliary Forecourt Channel 1 Configuration form.
7. Click Advanced Settings of Emulated PCTs if the Device Type is Petro Vend.
8. Select PCT 1 for Channel 1 Petro Vend Configuration.

**Car Wash**

:::note Refer to the Car Wash topic in this document for information on this feature. :::

1. From the Select Module list, select Car Wash
2. Select Device Type
3. Click Advanced Settings
4. Select the Serial Port

**DCR Driver**

Note: Refer to the Dispenser Car Reader topic in this document for information on this feature.

1. From the Select Module list, select DCR Driver
2. Select to enable DCR Control
3.  Click Advanced Settings next to DCR Channel 01 a. Click Enable Channel. b. Select IP Enabled for outside EMV DCRs c. Select Port name for serial port DCRs. d. Select DCR Family type: Bennett, Gilbarco, Invenco, Tokheim, VFI SPP, Wayne e. If debit encryption is to be used, click Advanced Settings

    a. Select Debit Encrypt Type

    * DSM: Select if using a Dresser/Wayne DUKPT Security Module (DSM).
    * DUKPT: Select for all US sites not using a GSM or DSM.
    * GSM: Select if using a Gilbarco Security Module (GSM).
    * MS: Select only for non-US sites using Master Session encryption.
    * NONE: Select if not configuring for Debit (no encryption).

    There were complaints that on some Wayne devices, particularly 5-inch and 7-inch models, that the font size was sometimes too small. To fix this issue the new option called "Graphic Enhancer" is included in this form only for Wayne. The parameter contains three levels: LOW, MEDIUM and HIGH. The "LOW" option is the default. "MEDIUM" and "HIGH" is used to increase the font size.

    Using "MEDIUM" and "HIGH" run the risk of the font being too big such that it ends up clipping, especially, if there is another softkey opposite. For example: These clippings can be prevented by switching around some of the softkeys. At present, "MEDIUM" and "HIGH" font size changes are only supported on 5-inch and 7-inch Wayne devices.

    b. Click Save

f. Click Save on DCR Channel 01 window :::note In feature Set 19 or higher for Wayne, there is an option to enable Enhanced CAT used for Secure CAT DCRs. This setting would only be used at Exxon Mobil sites that have Secure CAT DCRs (legacy or Dual CATs with injected secure messages). For both Wayne and SPP, if debit is used at the DCRs for the site a Debit Encrypt Type other than NONE must be selected (failure to do so will result in the keypad not functioning properly). :::

4. Set up additional DCR channels as required using previous steps.
5. Click Advanced Settings at DCR Positions to configure the appropriate channel for each DCR. a. For each DCR, specify the channel to which it is assigned. b. Click Save.

#### DVR Configuration

The Digital Video Recorder (DVR) feature provides a DVR interface to the Point of Sales (POS) System to detect and deter attendant fraud. The DVR broadcasts certain transactions performed on the POS terminal and displays these events with video images recorded at the time the events occurred. This provides video images of attendant actions coupled with a journal of events as recorded by the POS terminal. :::note Refer to the Digital Video Recorder Implementation Guide for information on this feature. The Feature Reference is available on Premier Portal. :::

1. Select the DVR mode: mode of communication for the DVR interface. The values are: a. Multicast: multicast communication is enabled. This is the default value. b. Serial: serial communication is enabled c. Both: serial and multi cast communications are enabled d. Disabled: configures the system to not generate DVR events
2. Multicast IP Address: The default Multicast IP Address is populated
3. Multicast Port Number: The default Multicast Port Number is populated
4. Local UDP port connations are to use: the fully qualified IP address and the multicast address. For example, 230.0.0.1:14001
5. Number of upstream hops allowed for multicast packet: The DVR “Multicast” uses the “Multicast UDP Datagram” broadcasting mechanism to send DVR event info. According to the IETF standard regarding “Multicast UDP Datagram”, the default ‘hop’ (or Time-To-Live - TTL) is ‘1’. The TTL value is used by routers that when they receive a datagram, they decrement the TTL value. If the TTL is still is greater than ‘0’, the datagram is forwarded to the router’s upstream LAN port (WAN). The IETF cautions about using a TTL value grater than 1 for multicast UDP datagram in that they do not want the Internet flooded with these multicast datagrams and only allows use of the TTL value greater than 1 if the routers are kept within an internal network.
6. We supply the ability to specify a value greater than 1 for those customers who have DVR monitoring equipment not in the “VFI Zone” and need to UDP datagram to forward ‘upstream’.
7. Click Advanced Settings to select port
8. Select port
9. Select baud rate
10. “Use Extended Protocol Mode” selects whether the DVR events send prepended byte codes normally used by journal printers. Unselecting this entity does not send the byte codes. Enable this value for backwards compatibility of legacy DVR equipment. For any changes to be reflected in the system, select “Tools -> Refresh Configuration” from Config Client.

#### DVR Logging Types

The “DVR Logging Type” configuration allows selecting types or classes of DVR events to be recorded. For any changes to be reflected in the system, select “Tools -> Refresh Configuration” from Config Client.

#### Fuel Driver

:::note Refer to the Fuel Manager and Fuel Sales topics in this document for information on this feature. :::

1. Enable SPI when running Smart Pump Interface (SPI) at the site.
2. Click Advanced Settings to configure Fuel Channel 01 a. Click to Enable Channel. b. Assigns the Verifone Commander serial port to be used for the Channel. c. Select Dispenser type. d. Specify Total fueling positions on this channel. e. The maximum and minimum delay for communication. :::note Maximum and Minimum Delay are used with Non-Modular Highline pumps only. :::

#### Fuel Price Display

:::note Refer to the Fuel Price Sign Communication document for information on this feature. The document is available on Premier Portal. :::

Click Advanced Settings to select port.

#### Fuel RFID Configuration

:::note Refer to the ORPAK AVI/RFID Fueling System feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

Enter the RFID configuration details.

#### GSM

Click Advanced Settings for each GSM (Gilbarco Security Module) port to assign the port.

**Kitchen Printer Service**

:::note Refer to the Kitchen Printer feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

1. Click to Enable Kitchen Printer Service
2. Select the port for connection

#### MNSP VPN Management Service

Verifone POS systems establishes or enables on-demand secure connections through the Managed Network Service Provider (MNSP) router. This enables the Verifone support personnel to interact with the POS systems through a VPN connection. New PCI requirements do not allow continuous, persistent connections outside of the VFI Zone and that if connections are to be made, they must be initiated by the customer using Maintenance > Help Desk Diagnostics from the POS.

Use this form to configure the MNSP VPN configuration.

#### Money Order Feature

:::note Refer to the Money Order Feature Reference for more information on this feature. The Feature Reference is available on the Premier Portal. :::

1. Select to enable money order feature
2. Reset Totals on Period Close is enabled by default and resets totals on the money order device when a period is closed by the cashier.
3. Select Device Terminal Type: MoneyGram Delta Network, Western Union ICE, or Western Union T7E.
4. Click Advanced Settings to enter the communication parameters.

**MoneyGram Delta Network**

a. Select the Port b. Enter Terminal Id

**Western Union ICE6000**

a. Enter the money order terminal’s IP address b. Enter the Terminal Id of the money order device c. Enter the forwarding IP address for the money order terminal. Typically the WAN side IP address of the Verifone zone router at the site should be entered.

:::note The WAN side IP address of the Verifone zone router is the forwarding IP address that should be used for the standard money order device configuration where the device resides on the store LAN.

**Western Union T7E**

Select the Port

**Speedpass**

1. Click Advance Settings of Wayne Device 1 a. Click to Enable b. Trac Controller Address for device1 is HEX 95 c. Select Port d. Begin DCR #: 1 e. End DCR #: 1- 32
2. Click Advance Settings of Wayne Device 2 a. Click to Enable b. Trac Controller Address for device2 is HEX 96 c. Select Port d. Begin DCR #: 33 e. End DCR #: 33 - 64
3. Click Advance Settings of Gilbarco Device 1

Click to enable DCR Positions.

#### Tank

BIR (Business Inventory Reconciliation) E-DIM is an expansion card in the TLS box that receives transaction data from Verifone Commander fuel sales for reconciliation.

1. Select Tank Model as EDIM
2. Click Advance Settings
3. Change Serial Port name to Port to be used, all other settings should be left default.

#### Tank Level Sensor

1. Select Device Type
2. Click Advanced Settings to select port

#### Receipt Printer

Use to add the port and enable Receipt Printer.

**Order Confirmation System**

:::note Refer to the Outside Confirmation Board feature reference documentation for information on this feature. The Feature Reference is available on Premier Portal. ::: Use to configure the order confirmation system.

* If the "Enable OCS" is selected, de-select and press \[Save].
* For "OCS Type", select Delphi Systems OCS Ethernet
* Select \[Advanced Settings].
* For "Device Network Address”, enter above IP for the device.
* For "Device Network Port”, enter above listening port for the device.
* The “Order Confirmation System" settings should now be displayed
* Select the Enable OCS and press \[Save].

### Pending Configuration

Feature not available.

### System Resources

System Resources tab shows a list of the module names and the ports to which the modules and Channels are assigned.

#### Refresh Configuration

After any changes are made to Car Wash, POP, or Network parameters including Loyalty, the command “Tools > Refresh Configuration” needs to be executed for the new settings to be applied to fuel and DCRs.

After changes are made to DCR parameters, the command “Tools > Refresh Configuration” is executed for the new settings to be applied to DCRs.

Changes to the Receipt Header/Trailer parameters also require a DCR download.

All the DCR position attributes except Pay At Pump, Push To Start Button, Grade Select Button, and Lever On Pump require a Initialize DCR Driver in addition to “Tools > Refresh Configuration”.

#### Ping Utility

Use to ping the devices in the LAN to check the communication status. Enter the IP address of the device and click Ping

\####Image Upload Users can import their own images and logos from Tools > Image Upload. :::note Refer to the Self Checkout User Reference documentation for information on this feature. The Feature Reference is available on Premier Portal. :::

### Event Manager

Enhanced System Monitoring feature provides a mechanism for retailers to remotely monitor certain events that occur at the site. Data required to monitor the site remotely is collected from all the registers at the site and sent to a configured remote server.

:::note This document does not cover information on how to configure the server to receive events and view events. This section only covers the configuration done through the Configuration Client. ::: Events that can be monitored are of two types:

* Real Time Events: A Real Time Event triggers notification to the remote server only when there is an occurrence of a specific activity at the site.
* Scheduled Events: Unlike Real Time Events, Scheduled Events trigger notification to the remote server periodically. We can configure the desired frequency rate at which the remote server should receive notifications.

#### Event Configuration

#### Reboot Commander

This option reboots Verifone Commander. After the user selects “Yes”, an OTP is required to complete the process.

#### Helpdesk Diagnostics

This menu is accessible from Configuration Client and POS. This menu provides diagnostic information. The diagnostics information can be used by both the Helpdesk as well as site users. The screens provide overall Online/Offline/Mixed status for configured devices in each section.

* Online = Device(s) is/are connected and functioning
* Offline – Device(s) is/are not connected or functioning
* Mixed – One or more devices is not connected or functioning.

There is a visual indicator (e.g. green/orange/red) along with the textual status.

#### General Status

The General Status screen reports the general status of the system.

General Status reports overall Online/Offline/Mixed status of:

* Controller (Verifone Commander)
* Zone Router
* Secure Services
* Electronic Check, if configured
* Electronic Safe, if configured
* Food Services, if configured
* Configured Registers
* Configured Register Printers
* Configured Register Scanners
* Configured Pinpads

#### Forecourt Status

This screen reports the last Online/Offline status and Offline time of all configured:

* Pumps
* DCRs
* Car Wash
* Car Wash Paypoint
* Tanks connected to a Tank Level Sensor
* Fuel Price Display
* Vending Machine
* Cash Acceptor

#### POS Status

The POS status screen reports the following:

* The Online/Offline status and time of all configured registers along with their ID.
* The register as the device name (e.g. Topaz, Ruby2).
* The detailed status and time of all configured printers.
* Primary Scanners that are connected to a configured register and if they are enabled or disabled.
* The detailed status and Offline time of all configured Electronic Check services.
* The detailed status and Offline time of all configured Electronic Safes.
* The overall status and Offline time of Verifone Commander Core Services.
* The overall status and Offline time of EZR (connectivity from Verifone Commander devices to EZR).
* The MAC address of EZR.
* The overall status and Offline time of Secure Services (connectivity from Verifone Commander to online support).
  * The status and Offline time of connectivity to Cybera Support
  * The status and Offline time of connectivity to VRSD

#### Payment Status

Reports Online/Offline status and time of all configured Feps, listed by Fep name. These include all configured Payment, Lottery, and Loyalty Feps, as well as Mobile. Reports the following information (if supported) for the Feps:

* Last Batch Closed
* Current Batch Number
* Current Batch Count
* IP Address
* Last Transaction Date
* Current Net Amount
* Current Terminal Batch
* Store and Forward count

#### MNSP Status

Shows the MNSP Status.

### Help

#### About

The About screen in the Help tab displays the versions of the software that the system is running.

#### Support

This screen contains the service ID entered during installation and the help desk phone number. The help desk phone number can be edited on configuration client from Initial Setup > Maintenance Configuration > Telephone & Postal Code.
