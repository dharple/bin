Excerpts from my personal bin directory.

### cleanup utilities

`cleanup-cache` - Removes cache entries safely.

`cleanup-dev-cruft` - Removes patch files and patch leftovers.

`cleanup-history` - Removes history files.

### disk utilities

`disk-create-random-files` - Creates random files at random intervals until terminated.

`disk-fill` - Slowly fill up a disk.  Writes files to the current directory.

`disk-metadata-fill` - Slowly fill up a disk's metadata/inode tables.  Writes files to the current directory.

`disk-remove-random-files` - Removes random files at random intervals until terminated.

`disk-show-write-buffer` - Shows global disk write and dirty buffers.

### git utilites

`gitr` - Run git recursively across subdirectories.  Ignores `vendor/` directories.

`git cleanup` - Removes any branches that have been removed upstream; runs garbage collection.

`git diff-list` - Shortcut to just show a list of files added, copied, modified, or removed.

`git post-push` - Runs garbage collection, permission fix script, and remote garbage collection if the remote repo is local.

`git update` - Literally just `git pull ; git status`

### misc utilities

`archive-wallpapers` - Copy the wallpapers installed on a Debian/Ubuntu/Mint/etc
		       system to subdirectories under the current path, broken
                       up by path.

`generate-pin` - Generates random PINs

`mbox-splitter` - Splits an mbox file into individual files

`organize-camera-uploads` - Moves the contents of a Dropbox "Camera Uploads"
			    directory into subdirectories based on year and
                            month.

### php utilities

`check-php-files` - Runs a lint checker on all .php files, recursively.

`generate-php-password` - Runs diceware and then generates a hashed password as a result.

`php-unserialize` - Simple script to unserialize and dump serialized data from PHP.

`find-dos-line-endings` - Seeks out files with DOS (CRLF) line-endings.

### wsl utilities

`cleanup-ssh` - Cleans out SSH agent sockets and directories.  tmpreaper doesn't touch them.

`start-all` - Starts services and runs basic cleanup.

`stop-all` - Stops services started by `start-all`.
