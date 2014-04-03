## zuliptrack

#### Installation
```
git clone https://github.com/thomasballinger/zuliptrack && cd zuliptrack
chmod +x zuliptrack
echo "alias zuliptrack=$(pwd)/zuliptrack" >> ~/.bashrc && source ~/.bashrc
```
Replace `.bashrc` as necessary.

#### Usage

```
zuliptrack repo_name [repo_name ...]
```

`zuliptrack` should be given the name(s) of one or more GitHub repositories that you own. The tool has no knowledge of local repositories, and does not need to be issued in the directory containing a repository that you wish to track.

For instance, assuming that I've already entered my own credentials, I could track a few repositories that I own with the following:

```
zuliptrack relative periphery.illogic am-interested connect-foe
```
