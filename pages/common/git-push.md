# git push

> Push commits to a remote repository.
> More information: <https://git-scm.com/docs/git-push>.

- Send local changes in the current branch to its remote counterpart:

`git push`

- Send local changes in a given branch to its remote counterpart:

`git push {{remote_name}} {{local_branch}}`

- Publish the current branch to a remote repository, setting the remote branch name:

`git push {{remote_name}} -u {{remote_branch}}`

- Send changes on all local branches to their counterparts in a given remote repository:

`git push --all {{remote_name}}`

- Delete a branch in a remote repository:

`git push {{remote_name}} --delete {{remote_branch}}`

- Remove remote branches that don't have a local counterpart:

`git push --prune {{remote_name}}`

- Publish tags to remote repository. If tag already exists in remote, push gets rejected:

`git push --tags`

- Publish tags that aren't yet in the remote repository (and all things that would be pushed with plain `git push`):

`git push --follow-tags`
