# setup

Bun Setup
```bash
sudo dnf install git -y
sudo dnf module list nodejs
sudo dnf module enable nodejs:20 -y
sudo dnf install nodejs -y
npm config set registry https://registry.npmmirror.com
npm install -g bun
npm install -g pm2
```

SSH Key Creation
```bash
ssh-keygen -t ed25519
cat ~/.ssh/id_ed25519.pub
```
