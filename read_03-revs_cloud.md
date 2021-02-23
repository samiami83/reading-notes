# Version Control System
## What is a VCS?
- VCS is a system used to revisit older versions of a file or set of files by keeping a record of changes to those files.
### Local Version Control
- A local VCS uses one database on hard disk to store changes to files.
### Centralized Version Control CVCS
- The need for collaboration on development projects led to the creation of the CVCS.
- In this system a single server stores all changes and file versions, this server can be accessed by various clients.
### Distributed Version Control System DVCS
- This system addresses the major vulnerability of the CVS: the server as a single point of failure.
- A DVCS allows users to create a mirrored repo. These backups can easily replace any lost information on the server.

# Git: What is it?
- A DVCS that stores data in a file system made up of snapshots.
- Each time you save (commit) Git creates a snapshot of the file and stores a snapshot of it.
- If the file has not changed, Git only stores a reference to the already-stored identical version of it.
- Git mainly relies on local ops because most necessary info can be found locally. Allowing for expediency and to continue working on a project even when not online.
- Every change applie to any file or directory is tracked. As the gatekeeper Git will detect file corruption or loss of info in transit.
- Git is set up to minimize risk of irreversible damage to files. It also makes it difficult to lose a snapshot of any committed files.
### States
- Committed: Data is securely stored in a local database.
- Modified: File has been changed but not committed to the database.
- Staged: Flagged changed version of a file to be committed in the next snapshot.
