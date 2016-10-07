# ElysiumCoin
ElysiumCoin is a new cryptocurrency with great potential!

# What is Elysium?
   Elysium (ESM) is a new cryptocurrency created by Livithian and was created as a means to try and raise money for charities and a way to help people understand the potential of Cryptocurrencies. ElysiumCoin is fairly new so we need people to download our wallet and start mining. Our current value of Elysium is around $1 per ESM. Our cryptocurrency was created with the aid of WalletBuilders. We pay around 0.05BTC to keep our currency up so we can assure you that we want the best for you.

# How do I start mining?
   Open your wallet, and make sure you are connected to another wallet.
You are connected if you see the icon Wallet Connections in the lower right corner of your wallet.
The message "No block source available" will disappear once you mine your first block.
Close your wallet and create the file Yourcoin.conf in the folder "%APPDATA%\Yourcoin\". (replace "Yourcoin" with the name of your coin)
Paste the following text into yourcoin.conf and save the file.
        rpcuser=rpc_user
        rpcpassword=7b12772957f0032b305ea8c50
        rpcallowip=127.0.0.1
        rpcport=4210
        listen=1
        server=1
        addnode=node.walletbuilders.com
Download the latest version of cpuminer from https://bitcointalk.org/index.php?topic=55038.0 and extract the zip file.
Create a .bat file named mine.bat and paste the following text into mine.bat.
        minerd --url=http://127.0.0.1:4210 --userpass=rpc_user:7b12772957f0032b305ea8c50
Save the file inside the extracted cpuminer folder.
Open your wallet and execute mine.bat to start mining your first coins.

# Do you support other mining options other than just CPU Mining?
   No, not currently but because we are a very new cryptocurrency it will not be hard at all to mine with CPU.
   
# Can I make a Mining Pool for your currency?
   Yes you may under the condition that you give us credit for the currency that you are supporting we are more than happy to let you.
