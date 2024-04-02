Random, possibly useful scripts.

### date time utilities

`month` - Writes out a month stamp for a file, in the format `YYYYMM`.

`stamp` - Writes out a time and date stamp for a file, in the format `YYYYMMDD-HHSS`.

### display utilties

`draw-line` - Draw a line of `-`.

`draw-title` - Draw a title in the format `---[ title ]---`.

### git utilities

`git cleanup` - Removes any branches that have been removed upstream; runs garbage collection.

`git diff-list` - Shortcut to just show a list of files added, copied, modified, or removed.

`git post-push` - Runs garbage collection, permission fix script, and remote garbage collection if the remote repo is local.

`gitr` - Run git recursively across subdirectories.  Ignores `vendor/` directories.

`git update` - Literally just `git pull ; git status`.

### image utilities

`archive-wallpapers` - Copy the wallpapers installed on a Debian/Ubuntu/Mint/etc system to subdirectories under the current path, broken up by release.

`guess-aspect-ratio` - Brute force aspect ratio guesser.

`organize-camera-uploads` - Moves the contents of a Dropbox "Camera Uploads" directory into subdirectories based on year and month.

### mailbox utilities

`mbox-splitter` - Splits an mbox file into individual files.

### php utilities

`check-php-files` - Runs a lint checker on all .php files, recursively.

`find-dos-line-endings` - Seeks out files with DOS (CRLF) line-endings.

`generate-php-password` - Runs diceware and then generates a hashed password as a result.

`php-unserialize` - Simple script to unserialize and dump serialized data from PHP.

`spellcheck-php-files` - Simple script to run aspell against PHP files.

### security utilities

`generate-pin [LENGTH]` - Generates random PINs.  Defaults to 4 numbers.  Uses `apg`.

### system utilities

`cleanup-snap-cache` - Cleans up old files in the snap cache on Ubuntu and other systems that use snap.

`drop-caches` - Drops caches in Linux.

`show-disk-write-buffer` - Shows global disk write and dirty buffers.
