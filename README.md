# ArchiveTeam-Deploy
A simple ansible script for deploying ArchiveTeam scripts.

## Usage
The basic usage is to add the machines you wish to use for ArchiveTeam duty to /etc/ansible/hosts under the appropriate group, and run ansible-playbook. The script will handle updating the OS, installing the prerequisites, pulling the code from GitHub, compiling wget-lua, and starting the process in screen.

## Contributing
Feel free to fork and make pull requests.

## Contact
I'm available on IRC, #archiveteam and #archiveteam-bs on EFNet under the nick phuzion.
