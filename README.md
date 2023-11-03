# homebrew-m1mac

## Installation Steps
1. Open a terminal window (it should be zsh). <a href="https://support.apple.com/zh-sg/guide/terminal/trml113/mac#:~:text=The%20default%20shell%20is%20zsh,windows%20and%20tabs%20open%20with.&text=In%20the%20Terminal%20app%20on,shell%20you%20want%20to%20use." target="_blank">Source</a>

2. Run the following command in the terminal:
```
  $ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```
3. Press RETURN/ENTER to continue or any other key to abort
 
Terminal will feedback:

Next steps:
- run these two commands in your terminal to add Homebrew to your PATH:

```
  *Replace quyencodes with the your filepath. To find your filepath please type pwd in your terminal.*
  $ (echo; echo 'eval "$(/opt/homebrew/bin/brew shellenv)"') >> /Users/quyencodes/.bash_profile
  $ eval "$(/opt/homebrew/bin/brew shellenv)"
```

4. To check if it's installed: run the command

```
  $ brew install postgresql
  * after postgresql is installed*
  $ brew services list
  $ brew help
```

Sources:
<a href="https://stackoverflow.com/questions/66666134/how-to-install-homebrew-on-m1-mac" target="_blank">How to install Homebrew on M1 mac</a>

<a href="https://stackoverflow.com/questions/64963370/error-cannot-install-in-homebrew-on-arm-processor-in-intel-default-prefix-usr" target="_blank">Cannot install in Homebrew on ARM processor in Intel default prefix</a>
