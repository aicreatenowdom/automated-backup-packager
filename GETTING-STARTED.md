# Automated Backup Packager: schedule and check a ZIP backup

## Create a scheduled Windows backup

1. Download and install the application from the [official product page](https://aicreatenow.com/backupsoftware.html).
2. Select the individual files and folders to include in your backup plan.
3. Choose a schedule and an available destination with enough free space for the ZIP archive.
4. Review the plan, then choose **Run Backup Now** for the first backup.
5. Read the activity log and open the finished ZIP. Confirm that representative files are present and can be opened before relying on the schedule.

## Pick a useful destination

Use a local folder, external drive, or a folder managed by a desktop cloud-sync application. The destination must be available when the scheduled backup runs. With OneDrive or Google Drive, Backup Packager creates the archive locally; the separate sync application performs the upload according to its own settings.

## Common questions

**How many scheduled plans can I keep?** Version 1.0 supports one active automatic backup plan through Windows Task Scheduler.

**Are source files moved or deleted?** No. The program copies them into a standard ZIP while preserving their original drive and folder paths inside the archive.

**Are ZIP archives password-encrypted?** No. Choose storage appropriate for the sensitivity of the files you back up.

**Why is a file missing?** Review the log for unreadable or locked files. Windows must allow the program to read a file for it to be copied.

**What happens when the trial expires?** Existing ZIP archives are not deleted. Visit the official product page for activation details.

For a support request, include the backup time, destination type and relevant log entries, with private paths and file names removed as appropriate.

[Back to product overview](README.md) · [Support](SUPPORT.md)
