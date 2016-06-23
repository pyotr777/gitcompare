# Gitcompare

Compare changes in one file between last N commits of a git repository.

Requires diffuse (http://diffuse.sourceforge.net).

## Usage

Save gitcompare.sh to any folder from $PATH.
Run in git repository directory:

```gitcompare.sh <filename> <number of commmits>```

For example:
```gitcompare.sh install_kpserver.sh 5```

Screenshot:
![alt text](screenshots/diffuse5.png "diffuse with last 5 file revisions.")