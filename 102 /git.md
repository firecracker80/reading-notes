# Version Control

> In a simple sentence, version control is like a registry of all the changes made to a file in one place, without overriding the original file. This list of file versions, allow you the opportunity to recover from unwanted changes.
>
> a. Local Version Control
>
>This is basically a database on your computer. You can still make changes and store them on there, but those changes will not reflect in the database the team is working from.
>
> b. Centralized Version Control
>
> It is exactly what it's name says, a centralized place where all the files are stored and can be accessed by others. 
>
>It does have one drawback, if the system goes down, no one can work with each other. That means the changes won't be saved, ergo, no new versions. Additionally, if the hard disk becomes corrupted, ALL work is lost. The only work available will be the portions on individual computers (local machines).
>
> c. Distributed Version Control
>
>  This is the answer to the CVCS drawback, because it allows us to create multiple mirrored copies of a repository. This allows collaborators to work simulatneaously.


# What is *Git*?

> Git is a distributed version control system, made up of snapshots stored as a file system. It depends on local operations, allowing collaborators to work offline without having to pull information from the server.
>
> Every time a change is made to a file, Git tracks it. This enables Git to detect corruption or information loss in transit. This feature, helps to reduce possible irreversible damage.
>
> - Git Command:
>   - 'git add' stages your file or changes made to the file.
>   - 'git commit -m"message"' begins tracking. It's the 'save as...'.
>   - 'git push' or git push origin main' creates the new version.
>   - 'git clone + url' clones the repository to your local machine.
>   - 'git status' checks the status of your file or changes made to the file.