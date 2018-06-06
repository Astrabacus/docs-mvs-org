title: SuperNova Upgrade Manual
---

# SuperNova Upgrade Manual

The Metaverse network will be undergoing a planned hard fork at block number 1.27mil (1,270,000), which will likely occur on Monday, June 18, 2018.

What is a hard fork in Metaverse?

A hard fork is a change to the underlying Metaverse protocol, creating new rules to improve the system. The protocol changes are activated at a specific block number. All Metaverse clients need to upgrade, otherwise they will be stuck on an incompatible chain following the old rules.

Please follow the following steps to upgrade your client.

**CAUTION: PLEASE BACKUP YOUR ACCOUNT’s MNEMONIC-PHRASE OF MASTER-KEY AT FIRST.**

## Upgrade on desktop
1. Download SuperNova wallet from <https://mvs.org/wallet.html>
1. Install SuperNova(v0.8.0) wallet.
2. Waiting for sync compeleted (a few mintues).
3. Done.

## Upgrade for platforms

### Backup Accounts (Optional)
Use cli command `dumpkeyfile` to backup your account information.
```
$ ./mvs-cli dumpkeyfile account_name password last_word path_of_backup_keyfile
$ ./mvs-cli importkeyfile account_name password path_of_backup_keyfile
```
Refers to [Backup Accounts](https://docs.mvs.org/docs/backup-account.html).

### Upgrade
Stop running the old client and unstall, then download and install Super Nova client.

1. [Download](https://mvs.org/wallet.html)
```
# Eg: Linux
$ wget http://newmetaverse.org/mvs-download/mvs-linux-x86_64-v0.8.0.tar.gz
$ tar -zxf mvs-linux-x86_64-v0.8.0.tar.gz
```
2. Installation
```
# Eg: Linux
$ cd mvs-linux-x86_64-v0.8.0
$ ./mvs-install.sh
```
References: <https://docs.mvs.org/docs/setup-linux.html>

### Sync
Run SuperNova wallet, sync blocks from Metaverse mainnet, **Please do not exit before syncing compeleted!**
User command `getinfo` to check and see <https://explorer.mvs.org>.

