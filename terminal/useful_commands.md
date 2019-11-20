## Useful terminal commands

`ls` - show the contents of the directory (folder) you are in

`mkdir` - create a directory.

`cd` - move to a directory.

Special uses of `cd`:
`cd ..` - takes you to the directory which is the parent of the directory you are in (`..` always means "parent directory")
`cd .` - takes you to the directory you are in (`.` always means "current directory")
`cd ~` - takes you to your home directory ( `~` always means the "home directory"; this is the directory where the `Documents`, `Downloads`, `Desktop`, etc. directories are located)
`cd /` - takes you the root directory (`/` always means root directory; this is the top-level directory in your computer; it has no parent).


------------

### Examples
For example, let's say you have a folder called `c_folder`, which is located within a folder called `b_folder`. And `c_folder` has a folder inside of it called `d_folder`.

If you're in `c_folder`, then running `cd d_folder` will take you inside of `d_folder`. Since you are now inside of `d_folder`, running `cd ..` will take you back to `c_folder`.

Let's say you're still in `d_folder`. Running `cd ../..` will take you to `b_folder`. And now that you're in `b_folder` then running `cd c_folder/d_folder` will take you into `d_folder`. 

Note that running `cd ..` will take you to a different folder depending on which directory you are running it from, whereas running `cd ~` or `cd /` will always take you to the same place (home directory and root directory, respectively) regardless of where you are running the command from.