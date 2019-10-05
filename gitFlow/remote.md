# Learning Git
## Remote 

The git remote command lets you create, view, and delete connections to other repositories.

The git remote command is essentially an interface for managing a list of remote entries that are stored in the repository's ./.git/config file.

## Add

**Syntax:** git remote add `<name> <url>`

This command allows you to create a new connection to a remote repository. After adding a remote, you’ll be able to use `<name>` as a convenient shortcut for `<url>` in other Git commands.

## Remove 

**Syntax:** -  REMOVE `<NAME>`

This can also be done by using : RM `<NAME>`

This command modifies  ./.git/config and removes the remote named <NAME>. All remote-tracking branches and configuration settings for the remote are removed.