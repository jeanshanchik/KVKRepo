# Learning Git
## Remote 

The git remote command lets you create, view, and delete connections to other repositories.

The git remote command is essentially an interface for managing a list of remote entries that are stored in the repository's ./.git/config file.

## Add

**Syntax:** git remote add `<name> <url>`

This command allows you to create a new connection to a remote repository. After adding a remote, you’ll be able to use `<name>` as a convenient shortcut for `<url>` in other Git commands.

## Show

By default, the git remote command will list previously stored remote connections to other repositories. This will produce single line output that lists the names of "bookmark" name of remote repos.

Invoking git remote with the -v option will print the list of bookmarked repository names and additionally, the corresponding repository URL. The -v option stands for "verbose"

## Remove 

**Syntax:** -  REMOVE `<NAME>`

This can also be done by using : RM `<NAME>`

This command modifies the ./.git/config and removes the remote named `<NAME>`. All remote-tracking branches and configuration settings for the remote are removed.


