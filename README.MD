
# Introduction

you you disagree, or want to extends this documentation, pull requests are welcomed

# Browser
Prefer
1. chrome: more resistant to malware
2. firefox
3. Safari

## DO
* Visit only service you use
* Check URL for mispelling
* Browse only in anonymous mode
* Only use HTTPS so nobody can eavesdrop your activities
* Always check the URL bar and make sure you’re on the website you think you are before you enter in any information
* Check certificate to avoid DNS poisoning
  * DNS cache poisoning, also known as DNS spoofing, is a type of attack that exploits vulnerabilities in the domain name system (DNS)
 to divert Internet traffic away from legitimate servers and towards fake ones. 

# DON'T
* Install ANY browser extensions
On dedicated computer you dont need them
  * even adblock
  * even ghostery
* run any exe downloaded from browser, if its legitimate, check PGP signature FIRST

#Accounts
##Username
* one username (not obvious name) per service/exchanges

##Password
* One per service, no reuse
* Use a password manager
  * keepass https://keepass.info/
  * password safe https://pwsafe.org/
  * Trezor https://trezor.io/

##security questions 
Always LIE!
* You may have leak this answer somewhere
* Hackers "may" found the response in google
* Don’t use an obvious answer to obvious question: favorite Town: Paris/New York 


## Emails
###provider
* gmail.com (prefered)
* use 2FA
  * more powerful
* outlook.com
  * use 2FA
  * can not log off existing sessions across devices!

###Adapt your behavior

If 
* you receive a link or an attachment from someone you KNOW, don’t click or open it
* If you receive a link or an attachment from someone you don’t know and aren’t expecting, don’t click or open it
* use extreme caution when clicking on any links or opening any attachments in emails that you receive


* A hacker can build 
a social attack:
1. identifying your friends
2. infecting them / impersonating your friend

* do NOT keep any confidential
emails in your mailbox, if it get compromised...



###use PGP for any confidential email
* flowcrypt in chrome
* mailvelope in chrome

# use 2FA

# type
* TOTP stands for "Time-based One Time Password" every 60s
* HOTP password may be valid for an unknown amount of time (until your next login)
* Check the 2FA list to see if your providers are supported.

# device
* dedicated phone
* nano ledger S support 2FA
* get a yubikey USB security key with NFC for Mobile


# Online services

golden rules: do not re-use password

* activate 2FA for login, refuse online service not using it
* secure master keys / recovery keys on a non computer medium


# Backup
* Against hardware failure, human mistakes, flood, theft, fire
* In an external location,
* On multiple medium type: usb, dvd
* ALWAYS encrypted with a well known and secure encryption scheme
## Test your backup regularly


# Documents
Secure document using encrypted container
* veracrypt https://veracrypt.codeplex.com/

# Wallets

## Private keys
* do not save them unencrypted on any medium
* do not save in any cloud 
  * provider: they can also 
  * be hacked there
* do not take any picture 
  * with ios/android camera: apps can read your photos!

* keep them in an hardware wallet


### Hardware wallet type

####hardware wallet
+ portable devices designed specifically for storing cryptocurrency
- slow access compare to hot wallet for trading

**Some examples**
* Ledger Nano S
* Keepkey
* Trezor

#### How it works
1. you can buy coins anywhere & then transfer to your hardware wallet's address.
2. your private keys stay in device & only you have access to it.
3. If you lose the device or it gets stolen, nobody can access your private keys without PIN code
4. You can buy a new one & restore your private keys by entering some of the 24 secret words in the correct order

###Cold storage wallet
a device that is never connected to the Internet, like an old offline laptop or a USB stick


###Software wallet
As secure as the computer they run on...

**Different types**
* light wallet
  * Jaxx, Myetherwallet, Electrum, ...
* full node
  * Mist, Parity, Bitcoin Core, ...
* hot wallet
  * online wallet on exchanges for day to day transactions
  * fast access but vulnerable
* paper wallet
  * safe only if in safes and safe deposit boxes
  * can be loss and stolen
  * can be splitted ex: requiring X of Y shares 



































