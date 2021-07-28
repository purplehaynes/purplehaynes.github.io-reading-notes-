### What is Git?

Git is softwasre for tracking changes in any set of files, usually used for coordinating work amond progreammers
collaboratively developing source code during software development.

### Files in Git reside in three main states:

- Committed
  - Data securely stored in a local database
- Modified
  - File has been changed but has not yet been committed to the database
- Staged
  - Flagged a file's changed version to be committed in the next snapshot

### How to track and stage a new file

Single file - track one file by using
`git add filename`

All files
`git add *`

After adding or changing a new file, you can see what information needs to be committed by using the 
`git status` command.

### How to commit a file

Use `git commit -m filename` to commit changes. If multiple files, use `git commit -a`

### Pushing changes

`git push origin master`

### Cloning

`git clone [repository URL]

