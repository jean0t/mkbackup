**mkbackup 📁**
================

**Backup Made Easy! 💻**

mkbackup is a simple yet powerful shell script that helps you create compressed backups of your important files and directories. With just a few commands, you can safeguard your data and store it in your `$HOME` directory.

**Getting Started 🚀**
---------------

### Installation

1. Clone the repository: `git clone git@github.com:jean0t/mkbackup.git`
2. Give executable permissions to the script: `chmod +x mkbackup.sh`
3. Run the script: `./mkbackup.sh` (or add it to your system's PATH for easy access)

**Usage 📝**
------------

To create a backup, simply run the script and provide the directories and files you want to include:
```bash
./mkbackup.sh [OPTIONS | FILES] # you can use -h or --help to get a menu with the usage
```
The script will create a compressed backup file in your `$HOME` directory.

**Compatibility 🎉**
------------

mkbackup is compatible with both **zsh** and **bash** shells, so you can use it regardless of your preferred shell.

**Features 🎉**
------------

* Easy to use: just provide the files and directories you want to backup
* Compressed backups: reduces the size of the backup file, saving you space
* Flexible: works with any type of file or directory

**Tips and Variations 🤔**
------------

* To backup multiple directories or files, separate them with spaces: `./mkbackup.sh /dir1 /dir2 /file1 /file2`

**License 📜**
---------

Feel free to use and modify.

**Author 👋**
-----------

* [Jean0t](https://github.com/jean0t)

**Contributing 🤝**
------------

If you'd like to contribute to mkbackup, please open a pull request on GitHub. I'd love to hear your ideas and feedback! 💬

**To-Do List 📝**
------------

- [ ] Add option to select a custom output file name
