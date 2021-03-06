<p align="center">
  <img src="/securedrop/static/i/logo.png" width="175" height="120">
</p>

## Google Slide Presentation

Google Slides Presentation    https://docs.google.com/presentation/d/1CpIUT4XsVqSVjscQvQEbTajm-Is8KLvTGO01f5PW5sE/edit?usp=sharing
## Youtube Video
Youtube Video Explanation https://www.youtube.com/watch?v=YqrTLVSeTFY&t=12s

## How UpTechAfrica Works
Provides Secure , Anonymous whistleblowing platform with an incentive to encourage reporting of issues

1. Whistlblower - Creates Blockchain wallet and submits encryptred messages without revealing identity

2. Organisation - Receives and Decrypt information recieved
## How to Install UpTechAfrica
Ensure you have Docker installed and:
```
cd uptechafrica
```
```
make dev
```
Whistleblower http://localhost:8080

Admin http://localhost:8081/login 

## Setting up Hyperledger Ledger
Organisation/Journalist
```
git clone https://github.com/raymondfx/hyperledger-ledger.git
```
```
cd hyperledger-ledger/demo
```
```
LEDGER_URL=http://dev.greenlight.bcovrin.vonx.io ./run_demo journalist
```
http://localhost:8021

Whitstleblower 
```
cd hyperledger-ledger/demo
```
```
LEDGER_URL=http://dev.greenlight.bcovrin.vonx.io ./run_demo whistleblower
```
http://localhost:8031

## UpTechAfrica Whistleblower Interface

Whistleblower interface on `127.0.0.1:8080`

Generate passphrase and Bitcoin wallet Keys and print or save them somewhere secure

![Alt text](whistleblower.png?raw=true "Whistleblower")


## UpTechAfrica Organisation Interface
Admin/journalist interface on `127.0.0.1:8081`

The credentials to login are printed in the Terminal.

![Alt text](organisation.png?raw=true "Organisation")


## Decrypting of Messages
We recommend using Tails Operating system , its a portable operating system
that protects against surveillance and censorship.

Boot a USB disk with Tails and use it to access the messages

![Alt text](tails.png?raw=true "Tails")




