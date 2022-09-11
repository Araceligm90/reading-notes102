

# Git tutorial

## Key concepts to undertanding Git:

1. Version Control: Version Control is a system that allows you to revisit past versions of a file or set of files by recording changes as if you were taking a picture of them. This means that you can easily revert a file to a previous version, track modification and avoid mistakes.

2. Centralized Version Control: CVS allows different users to work on the same file at the same time without the hassle of modifying someone else's work as they go. CVS also allows different users or team members access all changes and versions and keep track of another team member's activity with certain file.

3. Distributed Version Control: DVCS addresses the major ulnerability of the CVS, which is the loss of information if the server was to fail at a given point. DVCS avoid this by allowing their users to clone their repositories into their computers and place them on the server to replace any loss of information. And because DVCS allow multiple mirrored or clones repositories, programmers working in teams can collaborate with each other in various ways to complete a joint project.

Now that this two basic concepts have been explained...

## What is Git?

1. Snapshots: Git is a DVCS that stores fata in a file system made up of snapshot. Each time that you save a changed version of your project -called commit-, Git creates a snapshot of the file and stores it with a reference for future understanding of the commitment.

2. Local Operations: Git mostly relies on local operations, which means that a user can continue t work on a project even when not online.

3. Loss of Data: Git makes ir very difficult for a snapshiot of yur file that is commited to be lost.

4. States: Files in Git can reside in three different states:

    - Committed: data is securely stored in a local database.
    - Modified: file has bee changed but not committed to the database.
    - Staged: flagged a file's changed version to be committed in the next snapshot.


## How to send files from VS Code to GitHub:

1. git add selectedfile.md

2. git commit -m "Description you want to give it"

3. git push origin main 