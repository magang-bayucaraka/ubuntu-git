# Ubuntu & Git

## Ubuntu Basic Command
Berikut adalah beberapa perintah atau command yang umum digunakan pada sistem operasi Linux.

### **Perintah Navigasi File dan Direktori**

| Command            | Usage                               |
| ------------------ | ----------------------------------- |
| `cd`               | pindah direktori                    |
| `ls`               | melihat isi direktori               |
| `ll`               | melihat isi direktori dengan detail |
| `pwd`              | melihat direktori aktif             |
| `find <nama file>` | mencari file                        |
| `locate`           | mencari file                        |

### **Perintah Manipulasi File dan Direktori**

| Command               | Usage                  |
| --------------------- | ---------------------- |
| `cp <asal> <tujuan>`  | menyalin file          |
| `mv <asal> <tujuan>`  | memindahkan file       |
| `rm <file>`           | menghapus file         |
| `rmdir <nama folder>` | menghapus folder       |
| `touch <file>`        | membuat file           |
| `mkdir <nama folder>` | membuat folder         |
| `cat`                 | melihat isi file       |
| `echo`                | menampilkan baris teks |
| `nano <nama file>`          | membuka dan mengedit file di nano editor |

### **Perintah User dan Permission**

| Command           | Usage                                     |
| ----------------- | ----------------------------------------- |
| `sudo <perintah>` | melakukan perintah lain dengan super user |
| `su`              | mengganti user                            |
| `passwd`          | mengganti password                        |
| `who`             | menampilkan user                          |
| `chmod`           | mengganti hak akses                       |
| `chown`           | mengganti hak milik                       |

### **Perintah Lainnya**

| Command                     | Usage                        |
| --------------------------- | ---------------------------- |
| `history`                   | melihat riwayat perintah     |
| `grep`                      | mencari kata                 |
| `sort`                      | mengurutkan                  |
| `ps`                        | menampilkan proses berjalan  |
| `kill`                      | menghentikan program         |
| `tar`                       | mengumpulkan file            |
| `zip`                       | mengkompres file             |
| `unzip`                     | mengekstrak file             |
| `ssh`                       | akses jarak jauh             |
| `ifconfig`                  | melihat ip                   |
| `date`                      | menampilkan tanggal          |
| `clear`                     | membersihkan terminal        |

### **Notes**

Untuk detail dari tiap command, dapat menggunakan `--help` pada bagian belakang dari command seperti `<command> --help`.

## Git
### Getting & Creating Projects
| Command           | Usage                                      |
| ----------------- | ------------------------------------------ |
| `git init`        | initialize a local Git repository          |
| `git clone <url>` | create a local copy of a remote repository |

### Staging and Committing
| Command                            | Usage                             |
| ---------------------------------- | --------------------------------- |
| `git status`                       | check repository status           |
| `git add <filename>`               | add a file to the staging area    |
| `git add .`                        | add all files to the staging area |
| `git commit`                       | commit changes                    |
| git commit -m "[commit message](https://gist.github.com/nyancodeid/63f19941c81252bb0cca9c14497cf9f7#file-commit-message-md)" | commit changes & add a message |

### Branching
| Command                                              | Usage                                                                        |
| ---------------------------------------------------- | ---------------------------------------------------------------------------- |
| `git branch`                                         | display all local branches, current branch is indicated with an asterisk (*) |
| `git branch -a`                                      | display all branches (local and remote)                                      |
| `git branch <branch name>`                           | create a new branch                                                          |
| `git checkout -b <branch name>`                      | create a new branch and switch to it                                         |
| `git checkout -b <branch name> origin/<branch name>` | clone a remote branch and switch to it                                       |
| `git branch -m <old branch name> <new branch name>`  | rename a local branch                                                        |
| `git checkout <branch name>`                         | switch branch                                                                |

### Merging and Stashing
| Command                                     | Usage                                        |
| ------------------------------------------- | -----------                                  |
| `git merge <branch name>`                   | merge branch into the current branch         |
| `git merge <source branch> <target branch>` | merge branch into a target branch            |
| `git stash`                                 | stash current changes in a temporary storage |

### Remote Operations
| Command                                    | Usage                                                                      |
| ------------------------------------------ | -------------------------------------------------------------------------- |
| `git push origin <branch name>`            | push a branch to your remote repository                                    |
| `git push`                                 | push changes to remote repository                                          |
| `git pull`                                 | update the local repository with the latest changes from the remote branch |
| `git diff <source branch> <target branch>` | preview changes before merging                                             |


### [Commit Message Guidelines](https://gist.github.com/nyancodeid/63f19941c81252bb0cca9c14497cf9f7#file-commit-message-md)
