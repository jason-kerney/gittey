# Gittey #

Gittey is a Git tool to help simplify the task of unifying a team git strategy. The vision of this tool is to augment the Git work done at the command line, rather than simply wrapping it.

Coming and current features:

- [x] Branch annotations
    - [x] Branch prefixing
    - [x] Branch key visualization
    - [x] Branch name validation
- [ ] Local branch cleanup
    - [ ] Easy merge and delete of a branch
    - [ ] Easy delete for multiple local branches
- [ ] Commit prefix annotations
    - [ ] Provide canned Arlo-style annotations
    - [ ] Custom annotation prefixing
- [ ] Pre-hook hooks
    - [ ] Pre-push hook to allow actions which require a commit (e.g. version bumps)
    - [ ] Allow flag-driven hook disabling
- [ ] Configuration
    - [x] Configure branch prefix annotations
    - [x] Clear Gittey configuration
    - [ ] Configure commit prefix annotations

## CLI Options ##

Current options at the command line for Gittey:

- `--configure-branch-annotations` - Configure branch prefix annotations
- `--clear-configuration` - Clear current configuration
- `--branch-prefixes` - Display a table of branch prefixes and descriptions
- `--new-branch` - Create a new branch using the annotation rules