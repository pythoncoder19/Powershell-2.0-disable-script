# Powershell-2.0-disable-script
this script disables powershell 2.0
# README: PowerShell 2.0 Removal Script

## Overview

This PowerShell script is designed to permanently disable Windows PowerShell 2.0 from a Windows 11 system. PowerShell 2.0 is an older version of PowerShell that is included as part of the Windows Management Framework. Disabling this version helps ensure that only more secure and updated versions of PowerShell are used.

## Features

- **Checks Installation**: Verifies if PowerShell 2.0 is currently installed.
- **Disables PowerShell 2.0**: Permanently disables PowerShell 2.0 if it is installed on the system.
- **Confirmation**: Provides feedback on whether the operation was successful or if PowerShell 2.0 was not installed.

## Prerequisites

- **Operating System**: Windows 11 Home or Pro.
- **Administrative Privileges**: The script must be run with administrative rights.

## Instructions

1. **Open PowerShell as Administrator**:
   - Press `Win + S` to open the search bar.
   - Type `PowerShell`.
   - Right-click on "Windows PowerShell" and select "Run as administrator".

2. **Execute the Script**:
   - Copy the script provided into the PowerShell window.
   - Press `Enter` to run the script.

3. **Verify Results**:
   - The script will output messages indicating the status of PowerShell 2.0 installation and whether it has been disabled successfully.

## Notes

- **Testing**: It's recommended to test the script in a controlled environment before deploying it broadly.
- **Recovery**: If you need to re-enable PowerShell 2.0 in the future, you will need to use the Windows Features dialog or other system management tools to re-enable it.

## Support

For any issues or questions regarding the script, please refer to the [official Microsoft documentation](https://docs.microsoft.com/en-us/powershell/scripting/) or seek support from your IT department.

