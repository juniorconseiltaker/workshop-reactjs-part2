# Problems <img src="../.assets/problems-icon.png" width=20>

## Update Node.js with NVM (Node Version Manager)

Start by updating the package repository with the command:
```shell
sudo apt update
```

Install curl if you don't have it:
```shell
sudo apt install curl
```

Install NVM using the curl command:
```shell
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.38.0/install.sh | bash
```

Close and reopen the terminal for system to recognize the changes or run the command:
```shell
source ~/.bashrc
```

Then, verify if you have successfully installed NVM:
```shell
nvm --version
```

Now you can check for newly available releases with:
```shell
nvm ls-remote
```

To install the latest version, use the **nvm** command with the specific Node.js version:
```shell
nvm install [version.number]

[example] nvm install v0.1.27
```


---

<div align="center">

<a href="https://github.com/juniorconseiltaker" target="_blank"><img src="../.assets/taker-icon.png" width="50"></a>

</div>