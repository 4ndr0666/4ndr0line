# Hugo Theme: 4ndr0line
Minimal commandline style navigation based on Yukuro's [hugo-theme-shell](https://github.com/Yukuro/hugo-theme-shell): 

## Features
- Terminal interface w autocompletion
- Custom cmds/actions 
- Compatibility with [Mayccoll/Gogh](https://github.com/Mayccoll/Gogh) for colors:
  - `Molokai`  
  ![Molokai](https://raw.githubusercontent.com/Yukuro/hugo-theme-shell/master/images/v0.1.6/Molokai.png)

  - `shell-retro`  
  ![shell-retro](https://raw.githubusercontent.com/Yukuro/hugo-theme-shell/master/images/v0.1.6/shell-retro.png)

  - `Material`  
  ![Material](https://raw.githubusercontent.com/Yukuro/hugo-theme-shell/master/images/v0.1.6/Material.png)
        
## Requirements
- Hugo Version 0.85.0 or higher
    - **Hugo extended version is required**.

### Usage
4ndr0line is compatible with the [Mayccoll/Gogh](https://github.com/Mayccoll/Gogh) color themes.
1. Select one you like from the [Goph](https://mayccoll.github.io/Gogh/) repo.
2. Append the theme name in your config.toml:
  ```toml
  [Params.Terminal]
  scheme = "THEME_NAME"
  ```
## Quick Setup
### Create a new website from scratch
```bash
hugo new site myportfolio
cd myportfolio
git init
git submodule add https://github.com/4ndr0666/4ndr0line.git themes/4ndr0line
hugo server -t 4ndr0line -w -D
```

### Apply to an existing site
```bash
cd myportfolio
git submodule add https://github.com/4ndr0666/4ndr0line.git themes/4ndr0line
hugo server -t 4ndr0line -w -D
```


#### Documentation
See Yukuro's [write-up](https://github.com/Yukuro/hugo-theme-shell/blob/master/docs/shell_to_gogh.md) for details on configuratoin setup and deprecated themes.  
