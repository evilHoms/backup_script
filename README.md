# Description

Backup script for specified directory, also upload backup to google drive.
~/imp dir is currently selected.

Temporary backup files are removed after backup finish.  
Downloaded backups are moved to ./downloaded-backups dir.

# Usage

### At first start:

https://github.com/evilHoms/node-backup
node-backup have to be configured and placed inside dir with backup_script to work.

### Then:

`./backup_script [ls | get]`  
Create backup if no options provided.  
ls - shows list of uploaded backups.  
get - download chosen backup.
