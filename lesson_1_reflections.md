> How did viewing a diff between two versions of a file help you see the bug that was introduced?

By using the command "fc" on Windows I was shown snippets of the two files which included differences between the two versions. It seems like this could be useful for finding typos and changes, but not logical errors in a design.

> How could having easy access to the entire history of a file make you a more efficient programmer in the long term?

It can help prevent having to do the same thing twice. If the old file is there, then it's easy to remember how it used to work. It's easier to return to old code. It's easier to re-use old code (because it wasn't thrown away).

> What do you think are the pros and cons of manually choosing when to create a commit, like you do in Git, vs having versions automatically saved, like Google Docs does?

Manual commits allow users to save at logical points, which in turn creates organization in the history. The utility of this depends on the user. Automatic saving is easier, but can't understand the intent of the changes.

> Why do you think some version control systems, like Git, allow saving multiple files in one commit, while others, like Google Docs, treat each file separately?

The ability to save multiple files in one commit would be useful in Google Docs, too. However, it would be confusing for most users. There's no reason to assume that any of the user's files are related in such a way that changes to one file would be part of the same logical step as changes to another, because we don't know how the user of Google Docs intends to use it. So it'd have to be an optional, additional feature. Git needs commits, if only because that's how it works. If you add a new widget to a website, that may involve a small change to the HTML, another small change to the CSS, and so forth. So it makes sense to lump those together into one "project/task/commit."

> How can you use the commands git log and git diff to view the history of files?

The 'git log' lets users read the comment, which shows why it's important to put clear informtion in there: Next time you have to find this version, that's what you'll have to find it with. The 'git diff' still seems somewhat abstract, so I can't say much more than that it shows the differences...

> How might using version control make you more confident to make changes that could break something?

If something is broken, then it must have previously worked (a tautology?). So yeah... Going back and seeing how it used to work will allow me to compare the two states and figure out which change did the breaking.

> Now that you have your workspace set up, what do you want to try using Git for?

First, let me say that the commit ID seems like a major asset to have configured. This is cool. As for the question: I want to use Git to keep track of my progress in various MOOCs, as well as the code I write along the way. Now that I'm slowing getting the idea, I'll probably also use it for other projects and stop losing them to history.