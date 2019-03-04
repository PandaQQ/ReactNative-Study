# Node.js Installtion & Version Control Management Tool: NVM
After terrible expericnce with install node with brew & install node directly. I strongly suggest using nvm to manage node version.

### Step 1: If already install node, please delete node on your mac
 - First you need to check what kind of methoud you install node, and then you find the way you install node
```bash
$ which node
/Users/scott/.nvm/versions/node/v4.1.2/bin/node
```
- Install by NVM (Node Version Manager)
```bash
$ nvm uninstall <version>
```
- Install by Homebrew
```bash
$ brew uninstall node
```
- Install by Manual
```bash
rm -rf <path>
Delete /usr/local/lib  node & node_modules folder
Delete /usr/local/include node & node_modules folder
Delete /usr/local/bin  node, node-debug, node-gyp folder
Delete ~/  .npmrc, .npm, .node-gyp, .node_repl_history file
Delete /usr/local/share/man/man1/  node*, npm* file
Delete /usr/local/lib/dtrace/ node.d folder
Delete /opt/local/bin/ node folder
Delete /opt/local/include/ node folder
Delete /opt/local/lib/ node_modules folder
Delete /usr/local/share/doc/ node folder
Delete /usr/local/share/systemtap/tapset/ node.stp file
```

### Step 2: Install NVM
```bash
 $ brew install nvm
```

#### Reference
- http://phoeshow.github.io/2017/05/15/Mac%E5%88%A0%E9%99%A4nodejs%E7%9A%84%E6%96%B9%E6%B3%95/
- http://seyvoue.com/manual/9e29d568.html
