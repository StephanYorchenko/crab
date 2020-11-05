# crab

CRAB - Create Regular Amiable Backup


Key opportunity:
---

1. The utility takes at the specified path all files with the specified extension (for example,.db), places them in a single archive (e.g. .zip) and saves this archive to the specified path;

2. The integrity of the finished backup is checked

3. Provides the ability to specify the frequency of backup;

4. Ousting the oldest backup, to eliminate the disk filling ( storage of no more than a given n copies)

---
    ---------------------------------------------
    |        _____ ______   ___  ______         |
    |       /  __ \| ___ \ / _ \ | ___ \        |
    |       | /  \/| |_/ // /_\ \| |_/ /        |
    |       | |    |    / |  _  || ___ \        |
    |       | \__/\| |\ \ | | | || |_/ /        |
    |        \____/\_| \_|\_| |_/\____/         |
    |                                           |
    |   CRAB - Create Regular Amiable Backup    |
    ---------------------------------------------
    usage <\$path_to_script>/crab [-v | --version]
                                 [-h | --help]
                                 [-i | --init]
                                 [-m | --make]
                                 [-c | --config]
                                 [-e | --ecron]
                                 [--set-text-editor] PARAM
                                 [--set-number-backups] PARAM
                                 [--set-file-type] PARAM
                                 [--set-destination-folder] PARAM
    ---------------------------------------------
    -v --version             (show version of the script)
    -h --help                (show this tutorial)
    -i --init                (create crabrc file in dirrectory for backup
    -m --make                (create backup manually)
    -c --config              (open text editor to rewrite configuration file)
    -e --ecron               (change crontab config)
    --set-text-editor        (change text editor (default: vim))
    --set-number-backups     (change number backups (default: 5))
    --set-file-type          (set type of files to save in backups)
    --set-destination-folder (set the path where backups will be stored)
    --set-origin-folder      (set the path where the original files are stored)
