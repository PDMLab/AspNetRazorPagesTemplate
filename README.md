# AspNet (Core) Razor Pages Template

This is a GitHub Template for ASP.NET Core Razor Pages using .NET 6.

It contains

* a .NET Solution
* a ASP.NET Core Razor Pages project
* TailwindCSS 3 including hot reload (JIT)
* tmux/tmuxinator windows / panes for development

## Usage

### Create a new Repository

* Create a new Repository from this Template as described [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).
* Clone your new repository locally

### Run the solution

#### First time 

```
yarn install
cd src/AspNetCoreRazorPages
yarn install
```

#### Development

```
yarn start
```

`tmuxinator` starts a new session with three windows:

##### Workspace
![](assets/screenshot_iterm_workspace.png)

##### App (.NET output)
![](assets/screenshot_iterm_app.png)

##### Frontend (tailwind build)
![](assets/screenshot_item_tailwind.png)

Browse https://localhost:5001

![](assets/screenshot.png)

## Known issues

* Not tested on Windows
* JetBrains Rider code completion does not work for TailwindCSS 3 JIT mode in `.cshtml` files [currently](https://youtrack.jetbrains.com/issue/RIDER-58725).