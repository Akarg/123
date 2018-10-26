# 123
ls: Show directory contents, lists names of files.
mkdir: Creates a directory of the specified name.
mkdir foo creates a directory called "foo".
cat: Display contents of a file.
cd: Change directory. Change to certain directory name if provided.
cd foo takes you to the directory foo.
Changes to home directory if no directory specified.
pwd: Displays the name of the working directory.
touch: Creates a blank file with a specified name.
less: View contents of specified file, page by page.
head/tail: Displays the first/ last 10 lines of a file.
rm: Removes a specified file. This action is permanent. There is no recycle bin.
rmdir: Removes a directory.
history: Display a listing of the last commands you've run.
cp: Copy specified file to a new named file. Use -r flag to copy a directory.
mv: Rename a specified file or directory.
find: search files and directories. Can use with wildcards (* ? [ ]).
quota: Print the amount of space available and used on all shares for the current user.
scp: Secure/ SSH copy. Copies from either the local filesystem to a remote filesystem, or vice versa. This will not work if both arguments are on remote systems. The remote system must be specified as user@remote.fqdn:/where/to/put. The user part is optional and only needed if the remote account name doesn’t match the local one. remote.fqdn is the remote machine, the colon afterwards tells scp that you’re giving it a path, and the path tells it where to place the file.
