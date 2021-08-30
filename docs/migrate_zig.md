# How to migrate ZIG from Ethereum Mainnet to Binance Smart Chain

![zignaly-bridge](.images/migrate_zig/zignaly-bridge.png)

All you need to know on migrating your ZIG from Ethereum Mainnet to the Binance Smart Chain is described in the guide below.

We committed to it, and now is the time to deliver! ZIG supports [BSC](https://www.binance.org/en/smartChain) (Binance Smart Chain), which means the doors to a super-efficient network are open to the ZIG Holders & Traders!

BSC has a few inherent advantages over the Ethereum Mainnet. One of the main advantages is **remarkably lower gas fees**, which makes transactions and operations efficient to an unparalleled level. The BSC ecosystem is flourishing with more assets added each passing day. To take full advantage of the BSC ecosystem, you’ll need to convert your ZIG tokens from the Ethereum side of[ ](https://www.binance.org/en/bridge)the [ZIG Token Bridge](https://bridge.zignaly.com/) and then claim them on the BSC side.

To start exploring ZIG on BSC, head over to [ZIG Token Bridge](https://bridge.zignaly.com/) and follow the guide below:

## **Setting up and funding MetaMask browser extension**

### Step 1) Install MetaMask

Go to [www.metamask.io](http://www.metamask.io/) and select Android or iOS for mobile application and select Chrome for desktop. 

*(Source:* [*https://metamask.io/faqs.html*](https://metamask.io/faqs.html)*)*

![Step1-add-MM](.images/migrate_zig/gifs/Step1-add-MM.gif)

### **Step 2) Add Binance Smart Chain to MetaMask, if you haven’t already** 

Since BSC network is not available by default on MetaMask, this step will demonstrate how to add it manually.

Open the **MetaMask** browser extension to begin.

Expand the **Networks** selection menu and select **Custom RPC**.

![Step2-RPC](.images/migrate_zig/gifs/Step2-RPC.gif)

Use the configurations shared below to populate the custom RPC form and click **Save** button:

```note
Network Name: Smart Chain

New RPC URL: https://bsc-dataseed.binance.org/

Chain ID: 56

Symbol: BNB

Block Explorer URL: https://bscscan.com
```

*(Source:* [*https://academy.binance.com/en/articles/connecting-metamask-to-binance-smart-chain*](https://academy.binance.com/en/articles/connecting-metamask-to-binance-smart-chain)*)*

![Step2-bsc](.images/migrate_zig/gifs/Step2-bsc-0247583.gif)

Once done, **Smart Chain** should appear in the **Networks** list.

### **Step 3) Adding ZIG to Ethereum Mainnet ** 

```note
ZIG ERC20 Contract address: 0x7bebd226154e865954a87650faefa8f485d36081

Token symbol: ZIG

Decimal: 18
```

*(Note: ‘Token symbol’ and ‘Decimal’ should be automatically detected upon entering the correct token contract address)*

![Step3-add-zig-eth](.images/migrate_zig/gifs/Step3-add-zig-eth.gif)

**ZIG** should now appear under the asset list on Ethereum Mainnet.

### **Step 4) Adding ZIG to the BSC Mainnet** 

Switch to BSC, and add ZIG using the following configuration:

```note
ZIG BSC Contract address: 0x8C907e0a72C3d55627E853f4ec6a96b0C8771145

Token symbol: ZIG

Decimal: 18
```

*(Note: ‘Token symbol’ and ‘Decimal’ should be automatically detected upon entering the correct token contract address)*

![Step4-add-zig-bsc](.images/migrate_zig/gifs/Step4-add-zig-bsc.gif)

**ZIG** should now appear under the asset list on BSC Mainnet.

### **Step 5) Connecting MetaMask to Bridge**

Go to: https://bridge.zignaly.com/

![Step5-url](.images/migrate_zig/gifs/Step5-url.gif)

Click **Connect Wallet** button in the top right corner, and select **MetaMask**.

![Step5-connect-wallet](.images/migrate_zig/gifs/Step5-connect-wallet.gif)

Accept connection in MetaMask wallet:

![Step5-accept-connection](.images/migrate_zig/gifs/Step5-accept-connection.gif)

At this point, the wallet is connected to the Bridge. However, there is a one-time setup that we’ll demonstrate in the next step.

### **Step 6) Approve MetaMask/Bridge permissions to spend ZIG**

One-time setup cost included for ERC20 and BSC networks, hence the wallets should have sufficient ETH and BNB, respectively, to cover the gas fees.

ERC20 — Make sure you are on the Ethereum Mainnet:

![Step6-ethmainnet](.images/migrate_zig/gifs/Step6-ethmainnet.gif)

Click **Approve Now** button to grant required permissions to the bridge and MetaMask.

![Step6-approve-eth](.images/migrate_zig/gifs/Step6-approve-eth.gif)

Upon clicking **Confirm** button, the gas fee should be deducted, granting the required permissions.

Next, switch the network to BSC:

![Step6-switch-bsc](.images/migrate_zig/gifs/Step6-switch-bsc.gif)

Click **Approve Now** button to grant required permissions to the bridge and MetaMask.

![Step6-approve-bsc](.images/migrate_zig/gifs/Step6-approve-bsc.gif)

Upon confirming the transaction, you will be ready to proceed with the ZIG ERC20-BSC transfer.

## **Let’s jump ships from ERC20 to BSC**

Enter the amount of ZIG you would like to transfer to BSC, and click **Convert Now**. 

Make sure to have sufficient ETH to cover the gas fee.

![Start-transfer-eth-bsc](.images/migrate_zig/gifs/Start-transfer-eth-bsc.gif)

Click **Confirm** to pay the ETH gas fee and approve the transaction. At this point, the chain switch will commence.

![Confirm_eth](.images/migrate_zig/gifs/Confirm_eth.gif)

**Switch to BSC** in order to claim the transferred ZIG tokens.

![Switch-bsc](.images/migrate_zig/gifs/Switch-bsc.gif)

Once the network is switched to BSC, proceed to **Claim** the tokens against the BSC network gas fee.

![Claim-zig-bsc](.images/migrate_zig/gifs/Claim-zig-bsc.gif)

At this point, your ZIG tokens are successfully migrated to the BSC network.

## In case you want to move your ZIG to the the Ethereum Mainnet

Moving your ZIG back to ERC-20 is as easy as moving them to BSC.

To initiate the process, go to the [Bridge](https://bridge.zignaly.com/).

Enter the amount of ZIG that you would like to transfer to ERC-20, and click **Convert Now**.

Make sure to have sufficient BNB to cover the gas fee.

![Transfer-bsc-eth](.images/migrate_zig/gifs/Transfer-bsc-eth.gif)

Confirm the transaction and pay the BSC gas fee to switch to the Ethereum Mainnet.

![Switch-eth](.images/migrate_zig/gifs/Switch-eth.gif)

Right now you’re back to the Ethereum Mainnet.

Proceed to **Claim** the tokens and **Confirm** the transaction.

![Claim-eth](.images/migrate_zig/gifs/Claim-eth.gif)

At this point, your ZIG tokens are successfully migrated to the Ethereum Mainnet.