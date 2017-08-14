# CounterCoin
A bitcoin ATM without a cash dispenser.  Shop owners handle the cash manually.

There are 3 separate parts.  
1. A $100 paper wallet private key printer, with no memory and not connected to the internet.
2. A $400 customer internet PC.
3. Shop owner's existing PC.  $50 QR scanner only.

### Private Key Printer
- Based on $35 Raspberry Pi 3
- I found a free Linux Private key generator tool, https://github.com/grondilu/bitcoin-bash-tools , that might work.
- Need to find a Raspberry Pi compatible printer that prints QR codes.  $90?
- This should be under $100 and work with a single push button.
- If Raspberry Pi 3 doesn't work, we can use a $179 Win10 PC intead.  I already have this working MINIX NEO Z83-4 http://minix.com.hk/en/products/neo-z83-4 It requires a monitor, keyboard, mouse which bumps the cost to $250 over the Raspberry Pi

### Customer Web PC
This is similar to a PC you'd find for free use at the library.  It will have minimal custom software with hyperlinks to crypto coin websites.  It will also have a simple conversion calculator, QR scanner, and printer for public keys.  Windows 10 or tablet/phone based.  Touch screen desired.
It would cost about $400 for a Win10 PC, http://minix.com.hk/en/products/neo-z83-4 , touch monitor, printer for public keys and customer desired conversion amount, and QR Scanner.  Writing the software there should be super easy since it will be web connected and Windows 10.
Customers can choose to use their own Phone instead of this Public PC if they wish.
Need to find software that clears last user's changes and resets the PC for each use.
Need warning popup software to warn customers not to store passwords / private keys from this PC.  Not responsible, etc.
HTML 5 could be used for the User Interface.  Need to find a popular/easy HTML 5 library.  open source.  Goal is to make it easy for others to help through GitHub.

### Shopkeeper PC
Shop owners will use existing software like Coinbase, MyEtherWallet, and Trezor.  
No custom software.  
The only hardware would be a $50 QR scanner.
Need to find or write training materials.  Find links to the best existing training for CoinBase for instance. 
