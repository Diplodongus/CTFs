# CTFs
# UIUCTF: WASMBABY

![date](https://img.shields.io/badge/date-08.01.2021-brightgreen.svg)  
![solved in time of CTF](https://img.shields.io/badge/solved-in%20time%20of%20CTF-brightgreen.svg)  
![warmup category](https://img.shields.io/badge/category-web-lightgrey.svg)
![score](https://img.shields.io/badge/score-50-blue.svg)
![solves](https://img.shields.io/badge/solves-347-brightgreen.svg)

## Description
wasm's a cool new technology! http://wasmbaby.chal.uiuc.tf

author: ian5v

## Attached files
- None

## Summary
This was a beginner challenge, and the solution is found by inspecting the wasm file that is ran on the website.

## Flag
```
CTF{this_is_a_test_flag}
```

## Detailed solution
When connecting to the website, you are prompted with a screen as below.

![Alt text](/UIUCTF2021/img/WASMBABY/1-root.png?raw=true "Root of Challenge Website")

Pressing **CTRL+SHIFT+i** brings up the developer console in chrome.

![Alt text](/UIUCTF2021/img/WASMBABY/2-dev-console.png?raw=true "Root of Challenge Website")

On this screen, selecting the **Sources** tab, we can see there is a file called “index.wasm”.

![Alt text](/UIUCTF2021/img/WASMBABY/3-Sources.png?raw=true "Root of Challenge Website")

In this index page, I just did a seach of “CTF” and found the solution towards the bottom.

![Alt text](/UIUCTF2021/img/WASMBABY/4-Flag.png?raw=true "Root of Challenge Website")

Flag found is uiuctf{welcome_to_wasm_e3c3bdd1}.

## Another solution
There is likely another solution involving the developer console tab / trying to get that part of wasm to execute so the flag shows up under “hello, world”. This was the simplest solution for me.
