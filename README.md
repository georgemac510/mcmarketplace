<h1>McMarketplace Ethereum dApp</h1>

McMarketplace is one of my initial Ethereum blockchain projects created in August 2019.  My intention is to improve the user interface to be more appealing, add better functionality and new features to the dApp as well as improve the inventory of products.  

<h1>Installation</h1>

<h3>Step 1:</h3> In the command line, create a git repository:

    git init

<h3>Step 2:</h3> Clone the github repository:

    git clone https://github.com/georgemac510/mcmarketplace.git

<h3>Step 3:</h3> Install app:

    npm install

<h3>Step 4:</h3> Cd into directory and start app:

    cd mcmarketplace  
    npm start

The app will show an error, since you do not have a Kovan Testnet wallet with KETH tokens.

<h3>Step 5:</h3> Setup up your Metamask Ethereum wallet
Go to https://metamask.io , click on GET CHROME EXTENSION , then Get Started .  Click on Import wallet , then I agree .  We're almost there!

Copy and paste the Mnemonic seed that you have from Ganache in Step 1 into the Wallet seed section, then click Import.

Set your "Network" to Kovan Test Network at the top of the Metamask app page using the drop down menu. It is important to note that since we are using a test network that it is not critical to keep your Mnemonic seed phrase private, but when using the Main Ethereum Network, YOUR TOKENS WILL BE STOLEN IF YOU REVEAL YOUR MNEMONIC SEED PHRASE.  Keep them safe, secret and stored where they cannot be compromised when operating in the wild!

VERY IMPORTANT! You must change your Metamask Privacy Mode to Off. This is done by clicking on the icon for your account in the upper right-hand corner of the Metamask app, then Settings, Security & Privacy, then set the Privacy Mode button to the left.

<h3>Step 6:</h3> Fund Your Wallet: A zero balance is no fun. Go to https://gitter.im/kovan-testnet/faucet every 3 days and paste in your Ethereum address under the account name on Metamask or go to https://faucet.kovan.network/ if you have a Github account that will send you 1 Kovan Ethereum every 24 hours if requested.

<h1>Happy Shopping!</h1>
