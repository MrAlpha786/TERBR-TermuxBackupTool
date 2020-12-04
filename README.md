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
apt-get install wget curl pigz tar -y
```

Install __pigz__(recommended) to reduce time in backup and restore

3.
```bash
wget https://raw.githubusercontent.com/MrAlpha786/TERBR-TermuxBackupTool/master/terbr && chmod u+x terbr && mv terbr $PREFIX/bin/
```
or
```bash
curl -O https://raw.githubusercontent.com/MrAlpha786/TERBR-TermuxBackupTool/master/terbr && chmod u+x terbr && mv terbr $PREFIX/bin/
```
## Usage
Run
```bash
terbr
```
for detailed usage
