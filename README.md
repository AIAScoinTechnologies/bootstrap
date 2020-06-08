# Bootstrap files for AIAS Coin
Here you will find `bootstrap.dat` and `blockchain.zip` files. Use these to sync your wallet or node faster.

## Bootstrap.dat file (recommended)
1. Download `bootstrap.dat`.
2. Place `bootstrap.dat` file inside of your AIAS Core folder:
	- Windows: `%APPDATA%\aias\`
	- Unix/Linux: `~/.aias/`
3. Run your wallet and let it sync using `bootstrap.dat` (blocks will be checked)
4. Once sync is done `bootstrap.dat` file will be renamed to `bootstrap.dat.old` automatically and can be safely removed.

## Blockchain.zip snapshot
1. Download `blockchain.zip`.
2. Extract the contents of `blockchain.zip`to:
	- Windows: `%APPDATA%\aias\`
	- Unix/Linux: `~/.aias/`
3. Run your wallet, since it's a snapshot blocks won't be checked.

**Note:** Don't use any snapshot file from unofficial sources.
