# Configuration Client

The Verifone Commander can receive configuration changes using Configuration Client. Configuration client is a web-based utility that allows store personnel, Verifone Authorized Service Contractors, and Verifone Helpdesk to modify site information. To utilize Configuration Client you must be using a supported web browser.

The supported Web Browsers are:

* Chrome versions 60 or higher
* Firefox versions 53 or higher
* Internet Explorer versions 8 or higher

1. Key in the URL https://192.168.31.11/ConfigClient.html into the Web Browser and press \[Enter].

2\. Enter User Name and Password. 3. Click Login.

## One-Time Password (OTP) Prompt

In Base 47 and higher, there is an additional prompt for a one-time password (OTP) implemented into Configuration Client. As part of PCI/DSS v3.2 Requirement 8.3.1, this incorporates a multi-factor authentication for all non-console access into the Cardholder Data Environment (CDE) for personnel with administrative access.

Menus that have this prompt include:

* Security > Manage Users (Includes Roles)
* Initial Setup
* Date & Time
* Local Area Network Config
* VHQ Configuration
* Payment Controller > POS Configuration
* EPS Configuration > EPS Global Configuration
* Full Service Attendant Configuration
* InComm Configuration
* LINQ3 Lottery Configuration
* Payware Fleet and Loyalty Configuration
* PCATS Loyalty Configuration
* Proprietary Fleet Configuration
* Punch Card Loyalty Configuration
* Network Configuration (network references the name of the network installed, such as Buypass)
* Loyalty Card Configuration

While the preceding is the list of functions In Base 47 that include the OTP prompt within Configuration Client, it may be expanded to other areas and new features in future releases.

Clicking on **Guidelines to generate an OTP** (see image above) will display the 3 different ways to obtain the OTP.

The OTP is 4 digits in length. When generated using any of the 3 methods above, it will appear on the 7- Segment status display of the Verifone Commander (displaying 2 numbers at a time; the period indicates the first set of numbers). If generated from the POS/register, it will also display on the POS screen.

The OTP is directly tied to the user’s Configuration Client login session. If the OTP is generated and correctly entered, the OTP will be active until the user logs out or the Configuration Client session times out for inactivity (15 minutes). The OTP does not require re-entry after it has been saved for the session, meaning the user can go between menus that require entry, without being prompted.

:::note The OTP requirement applies to backing up and restoring files to the Verifone Commander using SMS Import/Export. Files that require an OTP may not be restored to the Verifone Commander, and an error message (“One Time Password Required”) appears when attempting to do so. Clicking OK on the error prompt allows the rest of the import or export to proceed. Clicking Abort aborts the remainder of the import or export. In newer versions of SMS Import/Export, items that require OTP are removed from the backup and restore list. :::
