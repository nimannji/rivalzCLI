# rivalzCLI
Installing Rivalz cli rclient 

first go to rivalz dashboard and activate your address you could use my referral code if you want
https://rivalz.ai?r=nerevarine427
then start installing rclient

1. update vps
```
sudo apt update
```

2. Install NVM
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash
```

3. Activate NVM in your current shell session
```
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"

export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"


source ~/.bashrc   # or ~/.zshrc
```

4. Verify NVM Installation
```
command -v nvm
```

5.  Install Node.js Version 22
```
nvm install 22
```

6. Upgrade npm
```
npm install -g npm@latest
```
```
npm --version
```

7. Install Rivalz rclient and enter your wallet address then choose the drive(I had one drive, so I just pressed enter) and the select the space(at least 50GB)
```
npm i -g rivalz-node-cli
```
8. Open a new screen
```
screen -S rivalz
```
```
rivalz run
```
you could minimize screen by ctrl+A+D

For the list of screen
```
screen -ls
```
For resuming the rivalz screen you should enter the screennumber you see in screen -ls
```
screen -r screennumber
```
