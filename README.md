# AutopilotV2BulkImport
## Description
Adding enrolled devices in Intune to Device Identifiers, which will improve the Device Preparation process after a device factory reset

## Requirements

- Windows 10/11
- Minimum 5MB of disk space
- Internet access
- Microsoft.Graph.Authentication powershell module

## How it works?
### Bulk import of serial numbers to Device Identifiers
1. Launch the AutopilotV2BulkImport application
2. Connect to Graph API
   
   ![image](https://github.com/user-attachments/assets/2f71b049-b516-482b-b181-2176ec7765f1)
4. Please wait for the device list to be downloaded from Intune
5. Select objects manually or use the available buttons to import serial numbers in Device Identifiers
   
   ![image](https://github.com/user-attachments/assets/390398d9-6dde-45fb-8eaf-421421442c3d)
7. Select the Import Selected button to import serial numbers to Device Identifiers
8. Wait for the devices to be added to Device Identifiers
9. Disconnect from Graph API
   
   ![image](https://github.com/user-attachments/assets/c4b64ce1-ce46-44e4-81bb-2ebaac374cb1)

#### Example:
![AutopilotV2 - Copy](https://github.com/user-attachments/assets/9adfc1e7-f84c-468e-94dc-8df30d8019e4)


## Reporting problems

Bug reports and improvement suggestions are welcome! You can do this by using (https://github.com/rafallz10100/AutopilotV2BulkImport/issues).

## Status

The project is actively developed and updated.
