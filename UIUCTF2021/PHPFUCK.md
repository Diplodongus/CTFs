# CTFs
# UIUCTF: PHPFUCK

![date](https://img.shields.io/badge/date-08.01.2021-brightgreen.svg)  
![solved in time of CTF](https://img.shields.io/badge/solved-in%20time%20of%20CTF-brightgreen.svg)  
![warmup category](https://img.shields.io/badge/category-jail-lightgrey.svg)
![score](https://img.shields.io/badge/score-50-blue.svg)
![solves](https://img.shields.io/badge/solves-237-brightgreen.svg)

## Description
i hate php

http://phpfuck.chal.uiuc.tf	

author: arxenix

## Tags
**Jail**, **PHP**, **Beginner**

## Attached files
- None

## Summary
Flag is found within the “flag.php” file on the website. (View Source)

## Flag
```
uiuctf{pl3as3_n0_m0rE_pHpee}
```

## Detailed solution
Connecting to their website, we can see this website is running PHP Version 7.4.3.

![Root](https://raw.githubusercontent.com/Diplodongus/CTFs/main/UIUCTF2021/img/PHPFUCK/1-root.png?raw=true "Root of website given")

Furthermore, it is commented at the top that “Flag is inside ./flag.php”

When we try to navigate to /flag.php, we just see “No flag for you!”

![Flag.php](https://raw.githubusercontent.com/Diplodongus/CTFs/main/UIUCTF2021/img/PHPFUCK/2-flag.php.png?raw=true "Flag.php page")

If we inspect the source of this page (**CTRL+U**), we are greeted with the flag. 


![Final Flag](https://raw.githubusercontent.com/Diplodongus/CTFs/main/UIUCTF2021/img/PHPFUCK/3-flag.png?raw=true "Final Flag")
