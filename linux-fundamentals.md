# Linux Fundamentals

A reference guide for navigating and managing a Linux-based system via the Command Line Interface (CLI).

## Navigation and File Management

pwd: Print Working Directory - shows your current location.

ls -la: Lists all files, including hidden ones, with detailed information.

cd <directory>: Changes the directory.

mkdir <name>: Creates a new directory.
rm -rf <name>: Forcefully removes a file or directory.

## Permissions and Security

chmod 400 <key.pem>: Sets read-only permissions for the owner (required for SSH keys).

chown <user>:<group> <file>: Changes the owner and group of a file.

sudo <command>: Executes a command with administrative (root) privileges.

## System and Connectivity

ssh -i <key.pem> <user>@<ip-address>: Connects to a remote server securely.

cat <file>: Displays the contents of a file in the terminal.

grep "search_term" <file>: Searches for a specific string within a file.
