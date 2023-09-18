# Linux Tutorial

sudo &rarr; super user do ( root access )

sudo su &rarr; enter root user

## Package Manager

1. apt (must be know package name. eg. telegram-desktop, git, vlc)
2. dpkg (must be have package(.deb) file. eg. viber.deb, discord.deb, code.deb)
3. snap (must be know package name.)

## apt Package Manager

| command                                                | description                                              |
| ------------------------------------------------------ | -------------------------------------------------------- |
| sudo apt --help                                        | check description                                        |
| sudo apt update                                        | refetch repository                                       |
| sudo apt upgrade                                       | update package                                           |
| sudo apt install package-name                          | install package                                          |
| sudo apt remove package-name                           | remove package                                           |
| sudo apt install --fix-broken (or) sudo apt install -f | fix broken dependency after deb file installation failed |
| sudo apt search package                                | search package                                           |

## deb Package Manager

| Command                                                | Description                                              |
| ------------------------------------------------------ | -------------------------------------------------------- |
| sudo dpkg -i package.deb                               | install deb file                                         |
| sudo dpkg -r package.deb                               | remove deb file                                          |
| sudo apt install -f (or) sudo apt install --fix-broken | fix broken dependency after deb file installation failed |

## snap Package Manager

| Command                        | Description         |
| ------------------------------ | ------------------- |
| sudo sanp refresh              | update snap packges |
| sudo snap install package-name | install package     |
| sudo snap remove package-name  | remove package      |

## How to check description of package?

**_--help_** keyword is check description of package.

1. apt --help
2. dpkg --help
3. node --help

## Commands

| Commands | with options (or) usage       | Description                                                      |
| -------- | ----------------------------- | ---------------------------------------------------------------- |
| ls       |                               | show list computer files and directories                         |
|          | ls -l                         | show list computer files and directories with long format        |
|          | ls -a                         | show list computer hidden files and directories                  |
|          | ls -la                        | show list computer hidden files and directories with long format |
| cd       |                               | change directory                                                 |
| touch    | touch file                    | create file                                                      |
| mkdir    | mkdir directory               | make directory                                                   |
| rmdir    | rmdir directory               | only can remove directory                                        |
| rm       | rm file                       | only can remove file                                             |
|          | rm -f file                    | only can remove file with force                                  |
|          | rm -r directory (or) file     | can remove directory & file with recursive                       |
|          | rm -rf directory (or) file    | can remove directory & file with recursive and force             |
| mv       | mv ./source ./destination     | move file or directory                                           |
|          | mv -r ./source ./destination  | move file or directory with recursive                            |
|          | mv -rf ./source ./destination | move file or directory with recursive and force                  |
| cp       | cp ./source ./destination     | copy file or directory                                           |
|          | cp -r ./source ./destination  | copy file or directory with recursive                            |
|          | cp -rf ./source ./destination | copy file or directory with recursive and force                  |
| ping     | ping 192.168.0.1              | testing network                                                  |
| nslookup |                               | DNS checking tool                                                |
| df       |                               | show display amount of file system                               |
| grep     | cat note.txt \| grep remove   | filter keyword                                                   |
| netsat   |                               | display active tcp connection                                    |
| kill     | kill pid                      | kill process running services                                    |
| pwd      |                               | check current directory                                          |
| whoami   |                               | check user                                                       |
| whereis  | whereis packagename           | check packge location                                            |
| cat      | cat note.txt                  | display content in terminal                                      |
|          | cat note.txt \| grep hello    | display content with filter word                                 |
| head     | head note.txt                 | display top 10 line in terminal                                  |
| tail     | tail note.txt                 | display last 10 line in terminal                                 |
