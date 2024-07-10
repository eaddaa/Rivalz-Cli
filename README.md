# Rivalz-Cli
# Update and upgrade the system
```
sudo apt update -y && sudo apt upgrade -y
```
# Install NVM (Node Version Manager)
```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
```
# Load NVM
```
source ~/.bashrc
```
# Install Node.js version 20.0.0
```
nvm install 20.0.0
nvm use 20.0.0
```

# Start a new screen session named 'rivalz'

```
screen -S rivalz
```
# To reattach later, use:
```
screen -r rivalz
```
# Install the rivalz-node-cli package globally
```
npm i -g rivalz-node-cli
```
# Run the rivalz node
```
rivalz run
```
