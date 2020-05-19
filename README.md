Excerpts from my personal bin directory.

### cleanup utilities

`cleanup-cache` - Removes cache entries safely.

`cleanup-dev-cruft` - Removes patch files and patch leftovers.

`cleanup-history` - Removes history files.

### disk utilities

`disk-create-random-files` - Creates random files at random intervals until terminated.

`disk-fill` - Slowly fill up a disk.

`disk-remove-random-files` - Removes random files at random intervals until terminated.

`disk-show-write-buffer` - Shows global disk write and dirty buffers.

### git utilites

`gitr` - Run git recursively across subdirectories.  Ignores `vendor/` directories.

`git cleanup` - Removes any branches that have been removed upstream; runs garbage collection.

`git diff-list` - Shortcut to just show a list of files added, copied, modified, or removed.

`git post-push` - Runs garbage collection, permission fix script, and remote garbage collection if the remote repo is local.

### misc utilities

`generate-pin` - Generates random PINs

### php utilities

`php-unserialize` - Simple script to unserialize and dump serialized data from PHP.

### wsl utilities

`cleanup-ssh` - Cleans out SSH agent sockets and directories.  tmpreaper doesn't touch them.

`start-all` - Starts services and runs basic cleanup.

`stop-all` - Stops services started by `start-all`.
