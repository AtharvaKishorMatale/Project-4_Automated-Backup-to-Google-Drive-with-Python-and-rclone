# Project 4: Automated Backup to Google Drive with Python and rclone

## Project Title
**Automated Backup and Rotation System with Google Drive Integration**

## Objective
Automate the backup of project folders using Python and rclone, with features like:

- **Zipping folders**
- **Uploading to Google Drive**
- **Backup rotation**
- **Cron job scheduling**
- **Webhook notifications**

## Key Components & Tools
- **Scripting:** Python
- **Cloud Storage:** Google Drive
- **File Transfer:** rclone
- **Automation:** cron
- **Utilities:** zip/unzip, curl
- **Configuration:** python-dotenv

## Implementation Highlights

### Automated Zipping
- Compresses folders into `.zip` files

### Secure Cloud Upload
- Uploads files to Google Drive using rclone

### Backup Rotation
- Deletes older backups beyond retention limit

### Daily Scheduling
- Executes daily via cron job

### Success Notifications
- Sends notification via curl/webhook
