# IOS-Checker
Excel file running API calls against Cisco PSIRT Vulnerabilities

Before this file can be used you will need to register an App on the Cisco API Console and obtain a client key and client secret for the Cisco PSIRT openVuln API.
In the visual basic editor update the constants, client_id will be your key, and client_secret will be your secret.

Once opened in Excel, select the Deveoloper tab and select Visual Basic. Alternatively use ALT-F11 shortcut.
Open Module1 and update the below code with your credentials obtained from Cisco API console

    Public Const client_id As String = ""
    Public Const client_secret As String = ""
