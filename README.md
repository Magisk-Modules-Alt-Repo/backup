# Backup
An android CLI partition backup tool without custom recoveries.

# Usage
```
Usage: backup [OPTIONS] [PARTITIONS]
Options:
  -h                    Show usage
  -d                    Backup path (default: /sdcard/backup)

Partition Examples:
  all
  boot[_a,_b]
  persist[_a,_b]
  system[_a,_b]
  userdata[_a,_b]
  vendor[_a,_b]
```
