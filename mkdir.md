# Linux mkdir Command
### Command Introduction (命令介绍)
-------------------
> **mkdir - make directories**

### Command Format and Options (命令格式和选项)
```
#mkdir --help
Usage: mkdir [OPTION]... DIRECTORY...
Create the DIRECTORY(ies), if they do not already exist.

Mandatory arguments to long options are mandatory for short options too.
  -m, --mode=MODE   set file mode (as in chmod), not a=rwx - umask
  -p, --parents     no error if existing, make parent directories as needed
  -v, --verbose     print a message for each created directory
  -Z                   set SELinux security context of each created directory
                         to the default type
      --context[=CTX]  like -Z, or if CTX is specified then set the SELinux
                         or SMACK security context to CTX
      --help     display this help and exit
      --version  output version information and exit

GNU coreutils online help: <http://www.gnu.org/software/coreutils/>
For complete documentation, run: info coreutils 'mkdir invocation'
```
### Command Example (命令范例)
-------------------
**Creates a directory.**

- Create a directory in current folder or given path:

  ` mkdir directory`

- Create directories recursively (useful for creating nested dirs):

  ` mkdir -p path/to/directory`



