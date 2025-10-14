# Elite Striping

## Wiki

### Getting Started

1. [Open the VSCode terminal](#open-the-terminal) in the Elite Striping root folder.

2. Change directory to the Elite Striping Wiki folder using the following command in the terminal.

   ```bash
   cd wiki
   ```

3. Follow the steps in [Elite Striping Wiki](./wiki/README.md) to install the dependencies and run the website.

## Git

Git is a version control software that allows you to track changes in your code. It is commonly used in software development to manage different versions of your code.

> _Note: For simplicity: Git is your local state of your code._

## GitHub

GitHub is a web-based platform that allows you to store remotely and manage your Git code [repositories](#definitions).

> _Note: For simplicity: GitHub is your remote state of your code._

## VSCode: Git and GitHub

VSCode is a popular code editor that supports Git and GitHub integration. It provides a user-friendly interface for managing your code repositories.

### Update GitHub with local changes

1. Click on `Source Control` icon button in the [Activity Bar](#vscode-ux).
2. Find the collapsible `Changes` section in the [Primary Sidebar](#vscode-ux). This has about 4 icons, and a number representing the number of files that have been changed.
3. Click on `+` (Stage All Changes) icon button.
   > _Note: This will stage all changes in your [local](#common) Git repository. You will see all the files are now listed under the `Staged Changes` header._
4. Find the Message input box in the [Primary Sidebar](#vscode-ux) and type in a [commit message](#git-1).
5. Click on the `Commit` button.
   > _Note: This will commit all staged changes in your [local](#common) Git repository._

## VSCode: Terminal

### Open the terminal

`` Ctrl+` ``

Or

`Terminal` > `New Terminal`

## VSCode: UX

Get to know the [VSCode layout](https://code.visualstudio.com/api/ux-guidelines/overview#containers).

- [`Activity Bar`](https://code.visualstudio.com/api/ux-guidelines/activity-bar)
- [`Command Palette`](https://code.visualstudio.com/api/ux-guidelines/command-palette)
- [`Context Menus`](https://code.visualstudio.com/api/ux-guidelines/context-menus)
- [`Primary Sidebar`](https://code.visualstudio.com/api/ux-guidelines/sidebars#primary-sidebar)
- [`Sidebars`](https://code.visualstudio.com/api/ux-guidelines/sidebars)
- [`Status Bar`](https://code.visualstudio.com/api/ux-guidelines/status-bar)

## Definitions

### Common

- `local`

  Simply: Your computer. Not so simply: Actions or systems that occur on the same machine or within the immediate environment of the user.

- `remote`

  Simply: Not your [local](#common) computer. Not so simply: Actions or systems that occur on a remote machine or not within the immediate environment of the user, achieved via a network connection.

### Git

- [`commit`](https://git-scm.com/docs/gitglossary#Documentation/gitglossary.txt-commit)
- `commit message` A short message that describes the changes made in a commit.
  > _Note: Do not spend too much time on this, just use 'updates' if you're not sure what to write._
  >
  > _Examples:_
  >
  > - _update how-to.md_
  > - _add new wiki pages_
  > - _fix typos_
- [`push`](https://git-scm.com/docs/gitglossary#Documentation/gitglossary.txt-push)
- [`repository`](https://git-scm.com/docs/gitglossary#Documentation/gitglossary.txt-repository)

### GitHub

- [`repository`](https://docs.github.com/en/repositories/creating-and-managing-repositories/about-repositories)

## Resources

- [Markdown Cheatsheet](./wiki/markdown-cheatsheet.md)
