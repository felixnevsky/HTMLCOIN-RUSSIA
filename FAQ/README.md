# HTMLCOIN FAQ - Часто задаваемы вопросы.
  * Цель данного форка, донести информацию до Русскоговорящего сообщества HTMLCOIN RUSSIA
  * Русскоговорящее сообщество в телеграм https://t.me/htmlofficialrussia
  
  * Anyone interested in forking my repo and work on it, please work on the dev or create a new branch after the fork and work on it. This page gets updated quite frequently and it can take longer time for me to review your pull request.  new branch should be `<your-github-username>_dev` For exmaple: richardjoo_dev.  Thanks!
  * If any pull request was made to the master, it might not be approved.
  * Please make sure to update the fork before you update if you are planning on merging
    - [How to update forked git from the original repo](https://richardjoo.wordpress.com/2012/12/03/how-to-update-forked-git-from-the-original-repo/)
  * If you want to update continuously, please let me know, I can add you as a collaborator.

## Table of contents
  * [Important Message](#iimportant-message)
  * [Troubleshooting (new one I am workng on)](https://github.com/richardjoo/HTMLCOIN/blob/master/FAQ/troubleshooting.md#troubleshooting)
  * [POMA](#proof-of-mass-adoption)
  * [Which is the new coin?](#which-is-the-new-coin)
  * [What is htmlcoin?](#what-is-htmlcoin)
  * [Whitepaper](#whitepaper)
  * [Swap](#swap)
  * [Roadmap](#roadmap)
  * [Кошелёк (Wallet)](#wallet)
  * [Paper Wallet](#paper-wallet)
  * [PoS](#pos)
  * [Майнинг, добыча монеты (Mining)](#mining)
  * [Total supply](#total-supply)
  * [Lightning](#lightning)
  * [Мобильный кошелёк (Mobile wallet)](#mobile-wallet)
  * [На каких биржах торгуется (Exchange)](#exchange)
  * [HtmlBusiness](#htmlbusiness)
  * [Blockchain Explorer and API](#blockchain-explorer)
  * [Current Ranking](#current-ranking)
  * [Ссылки (Links)](#links)
  * [Coin burn](#coin-burn)
  * [Telegram groups](#telegram-groups)
  * [Telegram admin members](#telegram-admin)
  * [Contributors](#contributors)
  * [Important Message Archive](https://github.com/richardjoo/HTMLCOIN/blob/master/FAQ/important-message.md)

<br/><br/>

## IMPORTANT MESSAGE
### Wallet v.2.0.1.0 has been released!
  - It IS a mandatory update!!!! You MUST update!
  - https://github.com/HTMLCOIN/HTMLCOIN/releases
    - Hard fork on block 106,000, approximately Friday 13:00 GMT, this is to stabilise the eHRC difficulty adjust.
  - Go to [How to update to v.2.0.1.0?](#how-do-i-update-to-2010) and follow the instruction!

### Wallet v.2.0.1.0 will be released and is mandatory!
  - Peter Bushnell tweeted that this is going to be the mandatory update
  - Q: what happens if we don't upgrade wallet, ie. staying at 2.0.0.4 or earlier ?  Need to know to tell #HTML clan the bad things that could happen.
    - A: Your chain will stop downloading the blockchain, Automatic Checkpointing will tell your client to follow the updated chain, but the old client will be unable to do so due to a change in the difficult rules. If that happens just upgrade and all will be well.
  - Q: I appreciate you utilizing all the different features in QT. You're the only one I've seen use error messages & bitmessage. :) Is this the diff adjust?
    - A: It is the accumulative work that's gone into the chain, if the client finds that the current tip has less work than nMinimumChainWork it considers itself to still be in the initial block download. It is to speed up initial sync until chain work is greater than the min.


<br/><br/>


## WHICH IS THE NEW COIN?
### HTMLCOIN LESSON 101
  - Old Coin = HTML5
  - New Coin = HTML
  - Bleutrade = new coin
  - Yobit = SUCKS and has an old coin
  - Tradesatoshi = has both new and old coin, the old coin will close around January 10th, 2018
  - Can I send HTML5 to HTML coin?
    - no you cannot.  You will lose your coins permanently.

### WHY SHOULD I INVEST IN HTML COIN?
  1. Why BitCoin Going So High in price ?
    - Because it has best Blockchain Algorithm in the world
  2. Why Ethereum Price is Going Higher?
    - Because it can handle smart Contracts and ICOs
  3. Why Qtum is valued as Emerging BEST Crypto?
    - Because it is Crypto for Business and Mobile Devices
  4. Why RIPPLE Gone So High being 100Billion Coins?
    - Because it is Designed for Business and Banks

  - **Why HTMLcoin is Going to Go Higher than Expected ?**
    - **Because it has got All of the Above FEATURES !!**


<br/><br/>

## Whitepaper
### HTMLCoin Official Whitepaper
  - https://htmlcoin.com/whitepaper/
  - You can also download this [pdf file](https://github.com/richardjoo/HTMLCOIN/blob/master/FAQ/pdf/Htmlcoin-White-Paper-V.5-For-Public-Release.pdf)
    - click right button and select "save link as"



<br/><br/>


## SWAP
### swap dates

   PERIOD   | RATIO | DATE
  ----------|-------|------------
   1 - 60   | 1:1   | 2018-02-12
   61 - 90  | 1:2   | 2018-03-12
   91 - 105 | 1:3   | 2018-03-27
   106      |       | End of Swap

### Yobit swap process
  * there is a pdf file
  * also this
    - 6 Step easy to swap
      - [Download desktop wallet new HTML v2.0.0.4](https://github.com/HTMLCOIN/HTMLCOIN/releases)
      - Make a new HTMLcoin v2.0.0.4 address on menu request payment
      - [Fill the form](https://htmlcoin.com/swap-form/)
      Copy and paste the new wallet address,email and submit
      - After submit you will get old HTML5 address
      - Open Yobit / HTML5 coin wallet and do the withdraw,  sent it to address you get in step number 4
      - Just wait swap process
        - This process has a human labor.
        - It can take up to 72 hours after you send HTML5 to the swap address to process your swap transaction. If it has been more than 72 hours, please contact us via email at dev@htmlcoin.team
  * Yobit Swap youtube guide
    - https://www.youtube.com/watch?v=Q7f2ykh1okQ&feature=youtu.be

### I moved my html5 from yobit into my HTML wallet... I did this twice using the same payment address not knowing I needed to generate a new payment address... will this still go through?
  - Answered by @QuidProCrypto
    - You mean you sent two separate withdrawals from Yobit to the HTML5 address generated by the swap form? that’s perfectly fine, the HTML5 address is unique and will last as long as the swap form operates; you could send as many transactions as you want, and any transaction over 1 HTML5 will be swapped


<br/><br/>


## ROADMAP
  * Do you have an updated roadmap?
    - not yet, but we've been discussing internally and think we now know what is in/out of the foundation budget now.  Expect an update to be isssued in the new year...... that said, we are working on the solo miner, explorer and API, android and ios wallets.... and going through the research/planning for lightning. (SimonT)



<br/><br/>


## WALLET
### How do I update to 2.0.1.0?
  - If you fnd any issues or error, please ask community.
  - **Make sure to backup your wallet.dat to the multiple locations first!**
  - download correct file from the site [click this](https://github.com/HTMLCOIN/HTMLCOIN/releases)
  - Windows:
    - download v.2.0.1.0
    - install on top of existing software.
  - Mac:
    - download the v.2.0.1.0 dmg file
    - double click the .dmg file or click the dmg file from the browser download is completed
    - when the new Finder opens up with HTMLCOIN app, drag new wallet to Application folder
    - when prompted to replace, click `replace`
    - Open up the Finder, go to Applications
    - Right click on HTMLCOIN app
    - You will see the warning "HTMLCOIN is from an unidentified developer. Are you sure you want to open it?"
    - Click "OPEN"
    - Wait until sync.
    - You are good to go!
  - Linux: (untested and confirmed from other members)
    - cd to HTMLCOIN folder
    - git pull
    - follow the README instruction again to make file.
      - `./autogen.sh`
      - `./configure`
      - `make -j2`
    - I updated mine and worked just fine

      ```
        rjoo@htmlcoin-miner:~/HTMLCOIN$ src/htmlcoin-cli getinfo
        {
          "version": 2000100,
          "protocolversion": 70002,
          "walletversion": 130000,
          "balance": 0.00000000,
          "stake": 0.00000000,
          "blocks": 103259,
          "timeoffset": 0,
          "connections": 1,
          "proxy": "",
          "difficulty": {
            "proof-of-work": 51.72773577691995,
            "proof-of-stake": 4909914730.290439
          },
          "testnet": false,
          "moneysupply": 79928076250,
          "keypoololdest": 1512111373,
          "keypoolsize": 100,
          "paytxfee": 0.00000000,
          "relayfee": 0.00400000,
          "errors": ""
        }
        rjoo@htmlcoin-miner:~/HTMLCOIN$
      ```



### How do I update to 2.0.0.4?
  - I wrote this without testing any and simply based on my previous update to v.2.0.0.2.  If you fnd any issues or error, please let me know.
  - **Make sure to backup your wallet.dat to the multiple locations first!**
  - download correct file from the site [click this](https://github.com/HTMLCOIN/HTMLCOIN/releases)
  - Windows:
    - install on top of existing software.
  - Mac:
    - double click the .dmg file and drag new wallet to Application folder
    - when prompted to replace, click `replace`
  - Linux: (untested and confirmed from other members)
    - cd to HTMLCOIN folder
    - git pull
    - follow the README instruction again to make file.
      - `./autogen.sh`
      - `./configure`
      - `make -j2`

### How do I update to 2.0.0.3?
  - I wrote this without testing any and simply based on my previous update to v.2.0.0.2.  If you fnd any issues or error, please let me know.
  - **Make sure to backup your wallet.dat to the multiple locations first!**
  - download correct file from the site [click this](https://github.com/HTMLCOIN/HTMLCOIN/releases)
  - Windows:
    - install on top of existing software.
  - Mac:
    - double click the .dmg file and drag new wallet to Application folder
    - when prompted to replace, click `replace`
  - Linux: (untested and confirmed from other members)
    - cd to HTMLCOIN folder
    - git pull
    - follow the README instruction again to make file.
      - `./autogen.sh`
      - `./configure`
      - `make -j2`

### My wallet is not synchronizing! Stuck with 0 connections and nothing works. What should I do?
  - John R (bonchien), [Jan 5, 2018 at 10:04:15 AM]:
    - I have found that people get stuck on headers sometimes
    - when this happens, they repeatedly try to reinstall or clear the folder and start over but it doesn't work, sticks at the same spot
    - I have found that if they had an initial problem they may end up with a background process that keeps being reconnected to even after uninstall reinstall and they continue to fail at the same spot
    - to solve the problem (since I don't have a linux box atm) I am doing the following, 100% success rate
      - Backup wallet.dat
      - Clear user folders for HTMLCOIN and uninstall app
      - REBOOT.  (This gets rid of the background process)
      - Reinstall
      - Run wallet.  I have seen it have to be started stoped and started again or wait a few minutes to get stable peers.
      - Restore the wallet after sync.

### My Anti-virus software says the wallet software has a virus!!
  - Some antivirus software will complain that this download is a virus, but don’t worry
  — it’s a false positive. You can scan the file with 45 antivirus programs on virustotal.com

### Assertion error is keep happening and not going away.  what should I do?
  * Delete everything in your roaming profile datadir except wallet.dat and let the chain resync. If that doesn’t fix it, you may need to delete everything and use your backup wallet/keys. (QuidProCrypto)
    - If you are worried about this, simply copy the entire HTMLCOIN folder to HTMLCOIN_old and delete everything from the HTMLCOIN except wallet.dat
    - Start the wallet app and let it resync.

### Do you have a video on how to backup and restore?
  - [QT wallet how to backup and restore](https://www.youtube.com/watch?v=YdFPfDTCLhQ&t=4s)
    - this is for DOGE but since it is QT wallet, they work the same.

### Do I have to encrypt my wallet?
  - No you do not have to, but it is strongly recommended to encrypt your wallet.
  - If anyone can access your unecrypted wallet.dat file, they can steal your coin.

### Do I need to backup the wallet?
  - yes, it is very important to backup your wallet frequently and save backup files to multiple locations. And also it is important to make multiple backup files.
  - for example:
    - name your backup wallet file to something like
      - html-wallet-backup-2017-12-30-0430pm.dat
      - html-wallet-backup-2017-12-31-0500pm.dat
      - html-wallet-backup-2018-01-01-0100am.dat
  - Your wallet.dat can get corrupted due to multiple reasons and same to your backup files.  That is why you want to make multiple backups like this and save them to multiple locations like this:
    - backup to your usb stick - at least two of them
    - backup to your hdd disk
    - backup to your external hdd disk
    - backup to cloud storage (not recommended unless you have encrypted your wallet.)

### Why do I need to backup my wallet?
  - It contains all of your private keys
  - It is easy to restore your wallet to other computer or to your existing wallet when your wallet is corrupted or reinstalled and accidentally wiped your wallet.dat.

### Can I open my same wallet.dat to multiple locations?
  - yes you can, but it is not recommended because it can cause some unknown issues. You can open one for pure minotring purposes, but do this at your own risk.

### How to import / export private keys?
  - To export a private key from your qt client:
    - launch your htmlcoin client as usual and wait for it to load the blockchain and start up
    - click on 'help' in the menu bar (top right)
    - click on 'debug window'
    - select the 'console' tab
    - type: `walletpassphrase your-walletpassphrase-here 600`
    - type: `dumpprivkey your-address-here`
    - this will return the private key, you can copy it now; ensure you clear your clipboard/history afterwards
    - type: `walletlock`
    - when dumpprivkey fails for no reason, restart your wallet and try again.  this was tested :D

  - To import a private key
    - launch your htmlcoin client as usual and wait for it to load the blockchain and start up
    - click on 'help' in the menu bar (top right)
    - click on 'debug window'
    - select the 'console' tab
    - type: `walletpassphrase your-walletpassphrase-here 600`
    - type: `importprivkey privatekey`
    - type: `walletlock`
    - when importprivkey fails for no reason, restart your wallet and try again.
      - also check to see if you mistakenly used the address instead of private key :D

### How to restore wallet.dat?
  - Close your wallet software
  - You must find where your wallet.dat is located.
    - For windows: it is usually under `%APPDATA%\Roaming\HTMLCOIN\`
    - For Mac: it is usually under `Library/Application Support/HTMLCOIN/`
    - For Lunux: wherever you installed.
  - Rename your current `wallet.dat` to something like `wallet-original.dat`
  - Copy your backup wallet data file to where the `wallet-original.dat` is at.
    - DO NOT MOVE your backed up file.  make sure to copy and paste.
  - Rename your backup wallet data file to `wallet.dat`
  - Start your wallet software.

### Can I recover my coins if my wallet.dat is corrupted?
  - only way you can restore is either you have working backup wallet.dat or by importing your private keys to your newly installed wallet.

### Why peers get banned?
  - Sharing what your wallet interprets as old or incorrect data or a prefork source. Happens often, especially when syncing.

### Guys how long does it take for coin to show up on core wallet?
  - 8 hours staking or after 501 confirmations

### whats the immature in the HTML desktop wallet mean ?
  - means your coin needs to be matured and will take about 501 confirmations (8+ hours)

### Is there a way for us to see number of confirmation?
  - go to Transactions
  - bring your mouse cursor over the circle left to the date from the list.  you will see how many confirmations from received/mined coins.
  - You can also enable coin control in settings, then go to send, select inputs.  Then you can see the age of every block.

### Says 0 active connections to HTML coin network.
  - you will need to wait a bit and see you get more connections.  the worst case, restart the computer and before starting anything else, start the wallet and see if it works or not.  One of my newly downloaded OTHER coin is doing the same thing
  - I find if I kill banlist.dat and peers.dat and restart I get connections immediately

### I am mining 1 million coins or mining a lot a lot, is this normal?
  - Not a fake wallet, it can certainly be a genuine copy, but if the program can’t find a copy of the blockchain from another node, it starts it’s own. Hence the 100M+ coin blocks. Those are the swap premine.
  - Peter Bushnell:
    - The wallet should not allow solo mining without connections, however it does, which causes people to mine coins that are not part of the main blockchain. Next update will make sure that at least one other connection is required as set by the `fMiningRequiresPeers` in chainparams.
    - Q: So if it errors like this it’ll just die off once it reconnects? We won’t get fake blocks on the network..?
      - Peter Bushnell:
        - When the client connects to the mainnet it will switch chains to the longer chain which is also checkpointed. Next update will stop this situation from occuring to anyone except RegTest users but then you'd expect them to know what they are doing anyway.
      - QuidProCrypto:
        - That’s the beauty of the UTXO model and DLT generally, one user can’t override the consensus.

### The staking expected time to earn reward is not working.
  - This is happening because of QTUM wallet is having the staking calculation issue.
  - The indept technical note can be found the link below:
    - [Staking is correct](https://github.com/HTMLCOIN/HTMLCOIN/issues/5)

### Is there any manual for this wallet?
  * You can download this [pdf file](https://github.com/richardjoo/HTMLCOIN/blob/master/FAQ/pdf/HTML_Wallet-Quick-guide_beta.pdf)
    - click right button and select "save link as"

### I am on 2.0.0.4 and having issues connecting to nodes.
  - Answered by Peter Bushnell
    - Restart your router and try again.
      - Seems that nodes that previously seen are ignored by other network nodes, run a new client on a different port and it connects. Restarting the router may give you a new IP or map your client to a different port and appear as a different node to the network.
    - This answer can be found [here](https://github.com/HTMLCOIN/HTMLCOIN/issues/4#issuecomment-356858426)

### CreateNewBlock: TestBlockValidity Failed: bad-version (code 17) (#12)
  - Answered by Peter Bushnell
    - I only see the errors shown while the blockchain is still syncing with the network. Make sure that your block height is the same as shown in the explorer.
      - https://html.mastercalls.io/

    - This answer can be found [here](https://github.com/HTMLCOIN/HTMLCOIN/issues/12)


<br/><br/>



## PAPER WALLET
### Does HTML coin have a paper wallet?
  - paper wallets
    - https://walletgenerator.net/?currency=HTMLCoin



<br/><br/>


## POS
### What is PoS and How does it work?
  - HTMLCOIN uses PoS3.0
  - POS generates 1 block every 120 seconds, whilst POW generates 1 block every 120 seconds.  The two processes run 60 seconds out of sequence so we effectively have a 60 second block time witheach process throttled back to 1% pa each.
  - The block reward is currently 1250 coins, and growth in supply is managed at the network level which is why there appears to be a lumpy/luck based element to rewards.  This is a feature of the more modern POS3.0 coins and I am trying to explain is simply and mathemetically in a document for everyone to understand at the moment.



<br/><br/>


## What is Staking? by SimonT
### What is staking?
  - There are two major methods of securing a network which incentivize participation by generating new funds. The first method is "Proof of Work" and the second is "Proof of Stake".

  - The theory behind Proof of Work is to hold a mathematical competition. The first computer to solve the puzzle receives the coins. This makes distribution of coins a completely fair process. However, this also creates a problem of wasted energy.

  - Proof of Stake is a competition between shareholders, where based on connectivity to the network and random/lottery chance, you can receive new coins.

  - In Proof of Stake, you first prove you have access to coins and from that point compete to win blocks randomly. The more people competing, the more secure the block. Its original intention was to incentivise a wallet (node) to stay connected to the network and reduce the risk of a 51% (replay) attack.

### How do I start staking?
  - Once the coins are in your HTMLCOIN 2.0 wallet, it is always best to encrypt it, and create a secure backup somewhere safe. To start staking, unlock your wallet and check the "for staking" tick box.

### How long before my coins start to stake?
  - If you hover over (for a second or two) the lightning bolt icon (next to the HD icon) at the bottom-right of the wallet you'll notice the staking message.  The message "Not staking because you don't have mature coins" may appear. This is because you must wait 500 blocks for your coins to mature.  At the current block time of 60 seconds this means your coins will take approximately 8hr 20min to mature.

### How do I know when I am staking?
  - Once you are eligible to stake, the lightning bolt icon will turn solid and the following message will be displayed when you hover over the solid lightning bolt:
  - Staking:
    Your weight is <your staked coin amount>
    Network weight is <total network weight>
    Expected time to earn reward is <time>
    Once you've received a staking reward (currently 1250 coins), you must wait 500 blocks for the reward to mature to be usable.

### What is the expected time to reward, and why is it always wrong?
  - The Expected time to earn reward is a rough calculation based on:
      - `(network_weight / your_weight) * block_time_in_minutes / 60 minutes / 24 hours`.
  - This is a statistical expected time and you could get a stake reward much sooner, or much later than the expected time.  In general, it is best to ignore it as it doesn’t include the time for the stake reward to mature.

### How many coins can I expect to get?
  - The network is set up to generate approximately 1% of POW and 1% of POS coins.  We chose POS as is provides a true decentralized system in which the more nodes that connect, the better the security as it shifts trust from a limited number of miners to the whole network itself.

  - For HTML, the block reward is a constant 1250 coins per block (1% pa. approx.).   Only one person generates a block, the person that does gets the block reward, there's only one PoS block per two-minute interval. This does leave quite a level of ‘lottery luck’ in receiving a reward but over an extended period the random nature of staking does flatten things out, particularly when not all coins are being staked and a higher proportion is available to stakers.

### Why don’t I get a reward?
  - Reward is generated at the network level, there is a lot of luck involved.

### How long do I need to wait for my coins to mature?
  - The little tick mark at the very bottom right of the wallet will tell you how many blocks have been created.  As mentioned, you will need to wait for another 500 blocks (8hr 20min +) for the new coins to mature and be available to your wallet.

### What happens if I switch off or disconnect my computer?
  - If you shut down (put your PC/laptop to sleep, or get disconnected from the network), you will no longer be staking your coins and will have start the whole process again.

### Where can I find out more?
  - HTML uses an implementation of POS3.0 originally used by Black Coin:
    - https://bravenewcoin.com/assets/Whitepapers/Blackcoin-POS-3.pdf
      - click right button and select "save link as"

  - QTUM uses the same staking method:
    - https://medium.com/@jb395official/an-introduction-to-qtum-proof-of-stake-mining-a-racing-story-f11a3f48009f



<br/><br/>



## MINING
### HTML Foundation Official youtube video
  * 02 : Getting Started HTMLCOIN v2 : Generating Blocks
    - https://www.youtube.com/watch?v=xCcNfFRkDEA

### How to do wallet mining
  - from your wallet, go to `HELP` --> `DEBUG WINDOW`
    - click `CONSOLE`
    - type
        `generate 100`
      for a quick test
   - you will see
      ```
       [
       ]
      ```
    - when you see this, it means you found nothing
  - when you see this￼
      ```
       [
         "0000000006b9b5aec68faf150e6cbc9ce71653a622f25b977a4835a57498a8e1"
       ]
      ```
    - then you just found a block and earned 1250 HTML coins!
  - now you want to type something like
    - `generate 100 999999999`
      - this will create 100 blocks and repeat 999999999 times.  It takes about one hour to complete.
    - press UP arrow.  you will see your previous comment shows up again.
      hit Enter
    - repeat these two lines above like 100 times.

### how to run multiple wallets in a single pc
  * Youtube video:
    - https://www.youtube.com/watch?v=oinNy5iMfC0&list=PLMBhLSjNGMAi0FrYwlYUS01JtOzlgadnw&index=3&t=13s

  * For Windows example: Three shortcuts
    ```bash
      "D:\Program Files (x86)\HTMLCOIN2\htmlcoin-qt.exe" --datadir=D:\Users\MyName\AppData\Roaming\HTMLCOIN_1

      "D:\Program Files (x86)\HTMLCOIN2\htmlcoin-qt.exe" --datadir=D:\Users\MyName\AppData\Roaming\HTMLCOIN_2

      "D:\Program Files (x86)\HTMLCOIN2\htmlcoin-qt.exe" --datadir=D:\Users\MyName\AppData\Roaming\HTMLCOIN_3
    ```

### HTML coin mining with CLI for windows
  - You just download the zip file and uncompress, and close your windows QT wallet fully, and click start_mining.cmd
    - go to the site
      - https://github.com/HTMLCOIN/HTMLCOIN/releases
    - and download the 4th one `htmlcoind-2.0.0.4-win32.zip`
      - or click this link below to download the file
        - https://github.com/HTMLCOIN/HTMLCOIN/releases/download/v2.0.0.4/htmlcoind-2.0.0.4-win32.zip
    - uncompress
    - Read the README file and follow the instruction.

### HTML coin mining with CLI for linux
  - go to this site
    - https://github.com/richardjoo/HTMLCOIN/tree/master/mining/htmlcoin-cli-mining
  - follow the README instruction
  - you can download `htmlcoin-cli-mining.sh` file by right button on that file link and save as.
  - You can save the file to the wallet folder or one above.
  - When I use this script on multiple sessions, it only uses 4 cores even if I have 32 cores.  Why?
    - As an external miner is slow coming a better internal miner is something that I can work on, when you can set it to keep mining and allow you to set the thread count. When I get the time I'll get on to this but I'm stretched very thinly at the moment, not taken any days off now for months. This is on my to-do list.
      - Peter Bushnell (2018-01-08)
  - Korean community member created instruction in Korean!
    - [다중채굴.pdf](https://github.com/richardjoo/HTMLCOIN/blob/master/FAQ/pdf/%EB%8B%A4%EC%A4%91%EC%B1%84%EA%B5%B4.pdf)
      - Click Right Button and select `Save Link As` to download.

### HTML coin mining with multiple sessions
  - One of our contributors worked on this multi-session linux CLI mining script!  Thanks!
  - Please go to his github and follow his README.  He definitely made your life easier to do the mining! :D hahaha
    - https://github.com/cl04ker/HTMLCOIN-Scripts

### HTML coin mining with raspberry pi3
  - This is not completed, but you can follow this link below:
    - https://github.com/richardjoo/HTMLCOIN/blob/master/wallet/raspberry-pi3/how-to-install-htmlcoin-wallet-on-rpi3.md

### Where is the mining pool?
  - No mining pool is available at the moment.
  - Currently wallet CPU solo mining only.
  - External miner is slow coming in that it does not yet exist and I've not been able to pin down a miner developer. Internal mining only at the moment.
    - Peter Bushnell (2018-01-08)

### Can I mine with my graphics card?
  - No, you can't.
  - It is ASIC sha-256 only.
  - and mining pool is not available yet. Dev is actively working on it.


<br/><br/>



## TOTAL SUPPLY
### what is the max supply?
  - As of Thursday, January 18th, 2018 4:16PM PST
    - Current Rank: 139
    - Market Cap: $154,488,098 USD / 13,556 BTC
    - Volume: $1,077,340 USD / 94.53 BTC
    - Circulating Supply: 49,962,193,185 HTML

  - Where to get this info?
    - https://coinmarketcap.com/currencies/html-coin/

  * In the spirit of transparency, this number will be fully auditted against the swap number after the 106 day window and decisions taken on what we do. (SimonT)



<br/><br/>


## LIGHTNING
### what does the lightning do?
  - https://lightning.network/
    - Scalable, Instant Bitcoin/Blockchain Transactions
    - Transactions for the Future
      - Instant Payments.
        - Lightning-fast blockchain payments without worrying about block confirmation times. Security is enforced by blockchain smart-contracts without creating a on-blockchain transaction for individual payments. Payment speed measured in milliseconds to seconds.

      - Scalability.
        - Capable of millions to billions of transactions per second across the network. Capacity blows away legacy payment rails by many orders of magnitude. Attaching payment per action/click is now possible without custodians.

      - Low Cost.
        - By transacting and settling off-blockchain, the Lightning Network allows for exceptionally low fees, which allows for emerging use cases such as instant micropayments.

      - Cross Blockchains.
        - Cross-chain atomic swaps can occur off-chain instantly with heterogeneous blockchain consensus rules. So long as the chains can support the same cryptographic hash function, it is possible to make transactions across blockchains without trust in 3rd party custodians.

    - Powered by Blockchain Smart Contracts
      - Lightning is a decentralized network using smart contract functionality in the blockchain to enable instant payments across a network of participants.

      - How it Works
        - The Lightning Network is dependent upon the underlying technology of the blockchain.
          - By using real Bitcoin/blockchain transactions and using its native smart-contract scripting language, it is possible to create a secure network of participants which are able to transact at high volume and high speed.

        - Bidirectional Payment Channels.
          - Two participants create a ledger entry on the blockchain which requires both participants to sign off on any spending of funds. Both parties create transactions which refund the ledger entry to their individual allocation, but do not broadcast them to the blockchain. They can update their individual allocations for the ledger entry by creating many transactions spending from the current ledger entry output. Only the most recent version is valid, which is enforced by blockchain-parsable smart-contract scripting. This entry can be closed out at any time by either party without any trust or custodianship by broadcasting the most recent version to the blockchain.

        - Lightning Network.
          - By creating a network of these two-party ledger entries, it is possible to find a path across the network similar to routing packets on the internet. The nodes along the path are not trusted, as the payment is enforced using a script which enforces the atomicity (either the entire payment succeeds or fails) via decrementing time-locks.

        - Blockchain as Arbiter.
          - As a result, it is possible to conduct transactions off-blockchain without limitations. Transactions can be made off-chain with confidence of on-blockchain enforceability. This is similar to how one makes many legal contracts with others, but one does not go to court every time a contract is made. By making the transactions and scripts parsable, the smart-contract can be enforced on-blockchain. Only in the event of non-cooperation is the court involved – but with the blockchain, the result is deterministic.

### why not Masternode?
  - MN is on the list of things to investigate, and we have discussed it before, but there needs to be an economic business case other than making free coins.  There is a room to discuss in our ryver/slack site, and i see us kicking things off again in Jan.  The problem we have is that we are very fast, very secure and with lightning we can do TOR style micropayments.  If you do research MN coins they are generally all pre-segwit bitcoin based, whereas we are 0.14 and don't need to make any compromises.



<br/><br/>



## MOBILE WALLET
  * SimonT answered on 2017-12-28
    - iOS is in progress whilst Android is in alpha at the moment.  Teams are working on this (we were discussing on xmas day) and it will be one of the most important things we deliver in Jan/Feb 2018, although iOS will be all very hard work as soon as we submit to Apple and their listing processes.


<br/><br/>



## EXCHANGE
### Why CMC hasnt yet updated their market cap?
  - HTML Foundation sent request and waiting for them to update.

### How the exchange works.
  - by SimonT
    > We apply to them, some of them charge money for the application.  Then they asses the coin and we do not hear back unless we are accepted.
    >
    > Large exchanges are generally free, but often insist on a promotion programme of anything between 3-6btc
    >
    > Medium exchanges generally charge a lot of money, between 5 and 45btc. With these we pay upfront and they then consider our application before returning our money o we don't succeed
    >
    > Smaller exchanges are generally quite different and are responsive and helpful.
    >
    > To date we have 26 applications in flight.  I don't expect many responses until early Jan and even then we will probably have to reapply multiple times.
    >
    > Finally, this is not unusual.  I have applied to exchnages for much larger projects and brand names and been similarly ignored

### Where can I buy HTML coins?
  * Current Exchanges
    - If you find any missing pairs, please let me know.
    - [Bleutrade](https://bleutrade.com)
      - [HTML/BTC](https://bleutrade.com/exchange/HTML/BTC)
      - [HTML/DOGE](https://bleutrade.com/exchange/HTML/DOGE)
      - [HTML/ETH](https://bleutrade.com/exchange/HTML/ETH)
    - [Trade Satoshi](https://tradesatoshi.com/)
      - [HTML/BTC](https://tradesatoshi.com/Exchange?market=HTML_BTC)
      - [HTML/DOGE](https://tradesatoshi.com/Exchange?market=HTML_DOGE)
      - [HTML/LTC](https://tradesatoshi.com/Exchange?market=HTML_LTC)
      - [HTML/BCH](https://tradesatoshi.com/Exchange?market=HTML_BCH)
      - [HTML/USDT](https://tradesatoshi.com/Exchange?market=HTML_USDT)
    - [CryptoBridge](https://crypto-bridge.org)
      - [wallet](https://wallet.crypto-bridge.org)
      - [HTML market](https://wallet.crypto-bridge.org/market/BRIDGE.HTML_BRIDGE.BTC)
      - [HTML/BTC](https://wallet.crypto-bridge.org/market/BRIDGE.HTML_BRIDGE.BTC)
      - [HTML/MONA](https://wallet.crypto-bridge.org/market/BRIDGE.HTML_BRIDGE.MONA)
      - [HTML/ZNY](https://wallet.crypto-bridge.org/market/BRIDGE.HTML_BRIDGE.ZNY)
      - [HTML/LTC](https://wallet.crypto-bridge.org/market/BRIDGE.HTML_BRIDGE.LTC)
      - [HTML/BCH](https://wallet.crypto-bridge.org/market/BRIDGE.HTML_BRIDGE.BCH)
    - [FXCBit](https://fxcbit.com/)
    - You can always check CCMC too!
      - [CCMC HTMLCOIN Markets](https://coinmarketcap.com/currencies/html-coin/#markets)

  * Announced and Coming Soon!
    - [Openledger DEX](https://openledger.io/welcome)
      - [HTML/USD](https://openledger.io/market/HTML_USD)
      - [HTML/BTC](https://openledger.io/market/HTML_OPEN.BTC)
      - [HTML/CNY](https://openledger.io/market/HTML_CNY)
      - [HTML/BTS](https://openledger.io/market/HTML_BTS)
      - [HTML/OBITS](https://openledger.io/market/HTML_OBITS)
    - [Next.Exchange](https://next.exchange/)
    - [C-Patex](https://c-patex.com/)

  * Unannounced but confirmed
    - 2 Decentralized Exchanges

  * Waiting for voting results
    - [KuCoin](https://www.kucoin.com/#/)
    - [Cobinhood](https://cobinhood.com/home)
    - [fatBTC](https://www.fatbtc.com/)



<br/><br/>


## Html.business
### PHASE I
  - Medical data processing: We are creating a Private Healthcare Data Blockchain Solutions to support logdata.
    - For updates, you can follow this page. You can also sign up to receive updates by mail as soon as they arrive.
    - https://htmlcoin.business/dapp-playground/medical-data-processing/
  - The Brasil Token: The Brasil Token (BRSIL) is created to build a bridge between startups, creatives and corporates in Brasil
    - For updates, you can follow this page. You can also sign up to receive updates by mail as soon as they arrive.
    - https://htmlcoin.business/dapp-playground/brasil-token/

  - Merchants: Proof-of-Delivery
    - Simplifying the transport industry with blockchain technology!
    - For updates, you can follow this page. You can also sign up to receive updates by mail as soon as they arrive.
    - https://htmlcoin.business/dapp-playground/merchants-proof-of-delivery/

  - New Token Creation Platform.
    - On our platform any creative idea for services or products will have a chance to become a reality!
    - For updates, you can follow this page. You can also sign up to receive updates by mail as soon as they arrive.
    - https://htmlcoin.business/dapp-playground/token-creation-platform/
  - Create your own Gaming website.
    - At the request of many among you! As promised:  Gaming websites!
    - For updates, you can follow this page. You can also sign up to receive updates by mail as soon as they arrive.
    - https://htmlcoin.business/dapp-playground/create-your-own-gaming-website-htmlcoin-payments/
  - Smart Contracts
    - There is no need for physical meetings and signatures anymore. Legal agreements for your clients can be made quickly and efficiently with a few clicks!
    - For updates, you can follow this page. You can also sign up to receive updates by mail as soon as they arrive.
    - https://htmlcoin.business/dapp-playground/smart-contracts/
  - THE HTMCOIN.BUSINESS REWARD PROGRAM
    - You can earn money, tokens and coins by simply telling the world about the services and ICO’s conducted by our Token Creation platform!
    - For updates, you can follow this page. You can also sign up to receive updates by mail as soon as they arrive.
    - https://htmlcoin.business/dapp-playground/business-reward-program/



<br/><br/>


## Blockchain Explorer
  * Un-official HTML blockchain explorer
    - https://html.mastercalls.io/
    - http://html.altexplorer.co/

  * API
    - what is API?
      - A software intermediary that allows two applications to talk to each other.
    - http://api.htmlcoin.com:3001/htmlcoin-api/status?q=getInfo
    - https://github.com/HTMLCOIN/htmlcoin-api
      - it has a manual!!!
      - example:
        - http://api.htmlcoin.com:3001/htmlcoin-api/addr/YOUR-ADDRESS-HERE



<br/><br/>




## LINKS
  * HTMLCoin releases
    - Wallet downloads
      - https://github.com/HTMLCOIN/HTMLCOIN/releases

  * cmmandline example:
    - https://github.com/ChristopherA/Learning-Bitcoin-from-the-Command-Line/blob/master/bitcoin-cli-commands-help.md

  * Cointracking
    - https://cointracking.info/?ref=A190981

  * export private key
    - https://bitcoin.stackexchange.com/questions/4203/how-can-i-export-the-private-key-for-an-address-from-the-satoshi-client

  * HTML coin track
    - Cryptocurrency Market Capitalizations
      - https://coinmarketcap.com/currencies/html-coin/
    - bitscreener
      - https://bitscreener.com/coins/html-coin

  * HTML Reddit
    - https://www.reddit.com/r/htmlcoin_community/

  * Bitcointalk
    - The "HTMLCOIN Swap Delay At Yobit Exchange" topic
      - https://bitcointalk.org/index.php?topic=2610554o

  * HTMLCOIN & HTML Blockchain: First Live Stream
    - https://www.youtube.com/watch?v=HMo77gPd1a0&t=35s

  * HTML Coin News (Youtube)
    - https://www.youtube.com/channel/UCkfOL_6jmmF__A-31CgrKNQ



<br/><br/>



## COIN BURN
  * Coinburn planned at anytime?
    - Please feel free to burn yours ;)
    - Dont burn it, sell to me for 1 sat



<br/><br/>



## TELEGRAM GROUPS
  * Main
    - https://t.me/htmlcoinofficial
    - 9032 members as of 2018-01-27

  * Non-official news
    - https://t.me/htmlcoinnews
    - 653 members as of 2018-01-27

  * Non-official HTMLCOIN Mining
    - https://t.me/HTMLmining
    - 650 members as of 2018-01-27
    - @AleZanello created a bot for the mining community!
      - `/diff` - Get current Difficulty
      - `/hash` - Get current Hashrate
      - `/blocks` - Get last block found
      - `/checkpoint` - Get Checkpoint
      - `/blocktemplate` - Get Blocktemplate (Dont use it in Group)
      - `/mining` - Get Full Mining Current Info (Dont use it in Group)
      - `/staking` - Get Full Staking Current Info (Dont use it in Group)
      - More Commands coming!!!
      - Tips: HsmBsnRqr15uAxWtNETVm1BtV4nsTRn1cs

  * Brazil
    - https://t.me/htmlcoinbrasil
    - 684 members as of 2018-01-27

  * China
    - https://t.me/HTMLcoin_China
    - 44 members as of 2018-01-27

  * France
    - https://t.me/htmlcoinfr
    - 199 members as of 2018-01-27

  * Germany
    - https://t.me/htmlcoinde
    - 74 members as of 2018-01-27

  * Japan
    - https://t.me/HTMLcoin_Japan
    - 566 members as of 2018-01-27
    - https://t.me/HTMLcoinJapan
      - Announcements in Japanese

  * Korea
    - https://t.me/HTMLcoin_Korea
    - 1635 members as of 2018-01-27
    - https://t.me/HTMLcoinKorea
      - HTML코인에 관한 정보들을 공유하는 곳입니다.

  * NL/BE
    - https://t.me/HTMLCOINDUTCH
    - 546 members as of 2018-01-27

  * Russia
    - https://t.me/htmlofficialrussia
    - 103 members as of 2018-01-27

  * Turkiye
    - https://t.me/HTMLcoin_Turkey
    - 107 members as of 2018-01-27

  * Vietnam
    - https://t.me/HTMLVIETNAM
    - 181 members as of 2018-01-27

  * if anything missing, please report to the main group.



<br/><br/>



## WHAT'S APP
  * the Brazilian community is divided into telegram and whatsapp, it is much bigger than here in the telegram, today we already have 4 groups in whatsapp and 1 in the telegram.
    - 730 members in whatsap and we are close to reaching 1000 users in whatsapp or even more.
    - groups 1 and 2 are full and 3 and Hold are free I will pass you the links
    - GROUP 1,2,4 = FULL
    - GROUP 3. HOLD = OPEN
      - htmlcoin hold
        - https://chat.whatsapp.com/A33IY09u1xj2y1bhZYjd19
      - group 3
        - https://chat.whatsapp.com/Joh5hgVGTgFHJYBf0Gnw4S

    - HTMLCOIN GRUPO 1
      - https://chat.whatsapp.com/9JzAUDq8jJwI7BysZvkNC5
      -256 members

    - HTMLCOIN GRUPO 2
      - https://chat.whatsapp.com/1yzRhCVDBMiAX6eliMWFyk
      - 257 members

    - HTMLCOIN GRUPO 3
      - https://chat.whatsapp.com/Joh5hgVGTgFHJYBf0Gnw4S
      - 221 members

    - HTMLCOIN HOLD
      - https://chat.whatsapp.com/A33IY09u1xj2y1bhZYjd19
      - 181 members

    - Facebook
      - Fanpage
      - https://www.facebook.com/Htmlcoinbrasil/
      - 7914 followers

    - Grup Htmlcoin Brasil
      - https://www.facebook.com/groups/HtmlcoinBR/
      - 723 members

    - Grup HTMLCoin Brasil
      - https://www.facebook.com/groups/754974114589033/
      - 913 members



<br/><br/>



## TELEGRAM ADMIN
  * scammers are out there and trying to steal your coins. When anyone contacts you with admin name and photo, check their user names. ask other admins and verify the user before giving out any sensitive information.
  * Admins will NEVER EVER ask anyone for donation or ask private keys. That is the red alert right there!




<br/><br/>



## CONTRIBUTORS
  * Miwand Najafe (miwand)
    - https://github.com/miwand

  * sunk818
    - https://github.com/sunk818

  * cl04ker
    - https://github.com/cl04ker/HTMLCOIN-Scripts
      - Automate your usage of the HTMLCOIN software on Linux.

  * @nyangduck
    - Telegram user
    - Wrote multiple session mining instruction for Linux in Korean! thanks!!!
