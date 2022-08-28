# Linux Commands
## Pop quiz 1!

This quiz will test your knowledge of these Linux commands:
* `ssh` - connecting to remote servers
* `cat` - displaying content of files
* `grep` - searching/filtering for text
* `shuf` - randomly printing lines from files
* `sort` - sorting
* `|` - piping (or chaining) output of multiple commands together
* `>` - redirecting command's output to a file
* `man` - displaying manual for a command
* `mkdir` - creating a directory
* `cd` - changing directory
* `wc` - word count (`-l` for line count)


Tasks:

1. Use the `ssh` command to log into a remote server running linux. Hint: the syntax is
```
ssh basically.me
```

2. Create a new folder called `pop-quiz` and go into it. You will save all the output into this folder.
3. Select 30 random lines from `/usr/share/dict/words` that contain the word `dog`. Save the output to a file called `dogs.txt`.
4. Sort the `dogs.txt` file and save into `dogs.sorted.txt`.
5. Sort the `dogs.txt` file in reversed order and save into `dogs.rev.txt`.
6. Do the same for `butt`.