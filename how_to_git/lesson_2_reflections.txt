> How is the staging area different from the working directory and the repository? What value do you think it offers?

The staging area seems like a tool for organization. It only contains what it put into it, and the slate is wiped clean after each commit. This helps separate the wheat from the chaff.

After this reflection, there's a quiz which asks for the differences between git diff, git diff --staged, and git diff commit1 commit2. The difference between 'git diff' and ' git diff --staged' helps illustrate the staging area. The first shows the differences between the working directory and the staging area, while the latter shows the differences between the staging area and the most recent commit/repo.

> How can you use the staging area to make sure you have one commit per logical change?

Before commiting, I can run 'git diff' and 'git diff --staged' to make sure I'm committing all the changes I need to make, but also make sure that I'm not committing unnecessary changes.

> What are some situations when branches would be helpful in keeping your history organized? How would branches help?

Branches make it easier to work on features that require multiple commits and a longer development period, before being merged with the master. It could also help when working on multiple features at the same time (e.g. multiple people working on the same codebase).

Yeah, as Mike Wales says in the video, it's great for keeping the master safe.

> How do the diagrams help you visualize the branch structure?

They show how the code is growing out into different directions, what features and fixes are being worked on, etc. It helps keep this known and tracked.

> What is the result of merging two branches together? Why do we represent it in the diagram the way we do?

The result is one branch with features and fixes of both parents. I don't understand the second question. When the commits follow one after another, then when drawn out, they look like a branch. When the two are joined, they merge back together.

> What are the pros and cons of Git’s automatic merging vs. always doing merges manually?

On the plus side, Git's automatic merging identifies changes which could be tedious to thoroughly do manually. It also highlights the changes and gives you the different versions so you don't have to go searching (as often). However, talking about the changes and what everyone is thinking could help keep folks on the same page.