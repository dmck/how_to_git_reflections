
> When would you want to use a remote repository rather than keeping all your work local?

When multiple people are working on the project, and maybe as a backup. It's also easier than carrying around a tower, or laptop. So convenience is another reason.

> Why might you want to always pull changes manually rather than having Git automatically stay up-to-date with your remote repository?

When making fried chicken, it's best to have a wet hand and a dry hand. If the two were always synced, then the remote repo would be as messy as the working directory, or the opposite would be true and it would be difficult to get much done.

>Describe the differences between forks, clones, and branches. When would you use one instead of another?

Branches are series of commits, and given names. Clones are copies of repositories. A fork is a clone on GitHub which lets them associate one repository with another. A clone would be sufficient to run and use the code, but forking would be better when making changes.

> What is the benefit of having a copy of the last known state of the remote stored locally?

Differences arise between local and remote, and from time to time need to be reconciled. Since it’s usually easier to do that merge locally and then push the result, a local copy of the remote in needed. Having it locally also allows this to be done offline which can be faster and more convenient. If the local copy of the remote branch is out of date, then it wouldn’t do much good, because you might just get another merge conflict.

> How would you collaborate without using Git or GitHub? What would be easier, and what would be harder?

Without both, I would lose significant ability to do version-control and collaboration. It would involve keeping track of which files and which parts of files have been changed, then communicating that to one another. This could be done by email, chat, in person, phone, etc. however each means of communication are removed from the code itself. The pull requests let collaborators talk to each other within code, and lets folks literally read between the lines.

[As an aside, I notice that adding a blank line prevents the prior line from being shown as changed, which the substance of it really wasn't.]

> When would you want to make changes in a separate branch rather than directly in master? What benefits does each approach have?

A separate branch is almost like a spare computer. I can almost instanciate another laptop, slap a label on it naming what I'm working on with it, then set it aside without messing up the master. I'd venture to say it almost always makes sense to use a separate branch, as long as the project is big enough to warrant this. It's just a couple lines in the command prompt, but offers a lot of organization and safety. Then when using GitHub and pull requests, that's a whole aspect that wouldn't be possible if I were just making changes to master. However, working in master is probably a good starting point to initially frame everything out.
