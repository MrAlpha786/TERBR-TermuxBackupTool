# TERBR - A TERMUX BACKUP/RESTORE TOOL

### Created by [MrAlpha786](https://github.com/MrAlpha786)

_Backup Termux and Restore with just one command. Choose a directory to save backup and easily find them._

## Installation

Just enter following commands in respective order:

1.
```bash
apt-get update && apt-get upgrade -y
```
2.
```bash
apt-get install wget curl tar -y
```
3.
```bash
wget https://raw.githubusercontent.com/MrAlpha786/TERBR-TermuxBackupTool/master/terbr && chmod u+x terbr && mv terbr $PREFIX/bin/
```
or
```bash
curl -O https://raw.githubusercontent.com/MrAlpha786/TERBR-TermuxBackupTool/master/terbr && chmod u+x terbr && mv terbr $PREFIX/bin/
```
## Usage

***On first run it will ask you to choose a Backup destination. You can choose a custom directory or use the default.*** 


| __Command__ | __Description__ |
| :-----: | :-----: |
| `terbr -h` or `terbr --help` | Print Help and exit |
| `terbr -v` or `terbr --version` | Print Version |
| `terbr -b` or `terbr --backup` | Take Backup |
| `terbr -r` or `terbr --restore` | Restore Backup |
| `terbr -c` or `terbr --change-dir` | Change Backup Directory |
