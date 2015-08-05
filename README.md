# bash_lib
Some handy bash functions and commands.

## Script Files
- scpy is a handy command for lazy man. It's usage syntax is like **scp** but does not require full ip address and password. Instead you use host id for ip and password and user name is configured in **scpy_account** file.

Example:
   To copy from remote to local, you can 'scpy 29:/path/to/file /local/path'.
   To copy local file to remote, you can 'scpy /local/path 29:/path/to/file'.

You should first eidt **scpy_account** file located at the same directory of **scpy**, add info of host id '29'.

- cpy_rpl is used to copy file and replace content of the file.

## Learned

- Range in bash
  {1..N} is used to generate a list of numbers.

- Replace substring of a file
  sed -i -e 's/old/new/g' <file>


