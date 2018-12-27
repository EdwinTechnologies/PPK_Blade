# PPK_Blade

Brute Force PuTTY Private Key Files
--------------------


DISCLAIMER: I am NOT responsible or liable for any damages or loss caused or sustained by this program!


This program uses multithreading to crack PuTTY Private Key Files

## Getting Started


### Prerequisites

To run this program you need the .NET Framework 4.5 (or higher)

### Installing

```
Download the .NET Framework:

https://www.microsoft.com/de-de/download/details.aspx?id=30653

and install it (If not already done)

Then download PPK_Blade:

Windows 64-Bit: https://github.com/EdwinTechnologies/PPK_Blade/raw/master/PPK_Blade_WIN.zip

```
### How To Use

Generic Console Command:

```
PPK_Blade.exe <File path to wordlist> <File path to target PPK>
```

Example:

```
PPK_Blade.exe rockyou.txt C:\Users\User\Desktop\myKey.ppk
```
Example Console Output:

```
PPK_Blade  Version 1.1  Copyright (c) EdwinTechnologies
http://edwintech.ddns.net/

Loading magazine...

[*] PPK_Blade.exe
|
|
|__ Magazine: rockyou.txt
|   |
|   |__ Passwords loaded: 14344357
|
|
|__ Target: myKey.ppk
|   |
|   |__ PuTTY-User-Key-File-2: ssh-rsa
|   |__ Encryption: aes256-cbc
|   |__ Comment: Very Secure Key
|
|
|__ Found 4 CPU Cores
|   |
|   |__ Fired up 4 Threads. Good Luck!
|   |__ 115532 Keys/sec | 92,0411420323686 % tested|
|
|__ [!] PASSWORD FOUND: '_155linux'
|__ [!] Be careful and don't get caught!
|__ [!] Time Elapsed: 00:02:11.78
```

## Authors

* **Edwin Technologies**

  http://edwintech.ddns.net/

  https://github.com/EdwinTechnologies

  https://twitter.com/EdwinTechDEV

  https://www.youtube.com/channel/UCRKjE74TrECAva6sN-YzaMQ


__*End of the README.md file*__
