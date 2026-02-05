# Shake N Steak Tip Jars

Now that businesses are accepting bitcoin over the lightning network, I dusted off this old idea I had that was a little too early for it's time: The Nostr Tip Jar. The nostr protocol has something called NIP-57 zaps. This feature allows anyone with a lightning wallet to look up the ligntning address of a nostr user and send fractions of a whole bitcoin using the NIP-57 specification. We can use this to make a tip jar.

## For A Single Employee
A single employee with lightning address can create a QR code using the following format

`lightning:address@wallet.com` where the address is a ligntning address.

For example, my address is fullreserve@getalby.com. I made a lightning address out of this by entering it into [Libreqr.com](https://libreqr.com/qr/text). Since this is a public address, sharing it on the Internet is secure, but never enter your private key or nsec into a website. You want to protect your secret keys, but public keys can and should be shared freely. You can click on lightning:fullreserve@getalby.com to send fractions of a bitcoin called satoshis(or sats for short) to my address. I put this QR code generated from libre Qr onto the back of my business card. I got the cute lightning accepted here logo from [CryptoCloaks](https://www.cryptocloaks.com/).(Used With Permission)

<img width="343" height="360" alt="image" src="https://github.com/user-attachments/assets/e85e8da2-ccea-4b66-85ec-944d7458b4e8" />

You will need a lightning address. There are a lot of options these days. Choose one that fits your [threat model](https://owasp.org/www-community/Threat_Modeling).

[Lightningaddress.com](https://lightningaddress.com/) has a great list of various lightning wallets available, but I have been writing about this stuff for 7 years now so I'll add a few others.
- Minibits.cash: This is an **experimental** Cashu Wallet. It is very early. It still has bugs. It is custodial so I wouldn't keep more than you are willing to lose on it. I still like it because It allows me to do some interesting things like give people little pieces of paper with QR codes that let sends them small amounts of bitcoin. I wrote a blogpost about making greeting cards with [Cashu](https://cashu.space) for my kids, nieces, and nephews, but I don't draw very well so this and an artist drew up some cool characters and [Gandolf made this website](https://brrr.gandlaf.com/). It's pretty cool.
- [Rizfull](https://rizful.com/): 
 I have only tried this once because I run my own cloud lightning node on the cloud using [albyhub](albyhub.com). I have run it on my own computer, but I like to support the awesome work they are doing and my computers don't work when the power goes out. Rizfull is a easy way to get a free ligtntning address, but keep in mind, this is custodial bitcoin so don't trust much money on them. The thing is your  Here is mine: fullreserve@rizful.com
-[Zuess Wallet](https://zeusln.com/): Thus is a great wallet that allows you to start with custodial cashu, but prompts you to take self-custody of your bitcoin once you reach 10,000 sats. This aligns most wit my values. The name of my website is fullreserve.xyz because my goal is to teach people how to use bitcoin in self-custody and not take on the fractional reserve leverage that gets people wrecked. As I write this, I noticed many people apparently did not heed this advice and they are getting wrecked.

TODO: Make Video Tutorial

### Tip Jar For Multiple Employees.

The thing about tip jars is people tend to pool the tips at the end of the night. The way to do that with bitcoin is to use a protocol named [nostr](https://nostr.how/en/what-is-nostr), specifically [NIP-57](https://nostrhub.io/57) if you must know. You will need a nostr key. [Here is a tutorial](https://nstart.me/en). If you need help, send me a message.

TODO: Make Tip Jar Tutorial.
