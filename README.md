
# License Management System

## Introduction
The **License Management System** is designed to help businesses manage their users, licenses, and roles efficiently using Google Apps Script and Google Sheets. The system tracks user information, assigns licenses, and manages permissions for users based on their roles.

## Features
- **User Management**: Ability to add, update, deactivate users with roles.
- **License Management**: Ability to assign, revoke, and monitor licenses.
- **Web Interface**: Easy-to-use interface for administrators to manage users and licenses.
- **Google Sheets Integration**: All user and license data is stored in Google Sheets.

## System Requirements
- **Node.js**: Version 14.x or higher.
- **NPM**: Installed with Node.js.
- **@google/clasp**: Google Apps Script CLI.
- **Google Account**: Access to Google Apps Script and Google Sheets.

## Setup and Installation

### 1. Clone the Repository
```bash
git clone https://github.com/your-repo/license-management.git
cd license-management
```

### 2. Install Google Apps Script CLI (clasp)
Install **clasp** if you don’t have it already:
```bash
npm install -g @google/clasp
```

### 3. Login to Google Apps Script
Login to your Google account:
```bash
clasp login
```

### 4. Create or Clone an Apps Script Project
#### Create a New Project:
```bash
clasp create --title "License Management" --type sheets
```

#### Or Clone an Existing Project:
```bash
clasp clone <script-id>
```

> **Note**: The `script-id` can be found in **Project Settings** in Google Apps Script.

### 5. Configure `.clasp.json`
Ensure the `.clasp.json` file has the correct script ID and root directory:
```json
{
  "scriptId": "<YOUR_SCRIPT_ID>",
  "rootDir": "./src"
}
```

### 6. Push the Code to Google Apps Script
Once everything is configured, push the code:
```bash
clasp push
```

### 7. Deploy the Web App
1. Open your project in Google Apps Script Editor.
2. Navigate to **Deploy > New Deployment > Web App**.
3. Configure:
   - **Execute as**: Me (your account).
   - **Who has access**: Anyone with the link.
4. Click **Deploy** and copy the Web App URL.



## Support
If you need assistance or have any questions, please contact:
- Email: `devpham@hotmail.com`
- GitHub Issues: [License Management Issues](https://github.com/pamtrg-vn/license-management/issues)

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
