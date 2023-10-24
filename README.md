# Chrome extension: Blind mode

A simple Chrome plugin that turns the current tab black. 

This is perfect when testing screen readers and accessibility. 

## Installation

Currently the extension is not in the Chrome Web shop. 
You can install it manually like this: 

`git clone https://github.com/ertkjern/blind-mode.git`

Go to [chrome://extensions/](chrome://extensions/) in Chrome. 

Turn on developer mode on the top right corner.

Then click `Load unpacked` on the left side, and select the cloned folder

## How to use

Click on the extension button when you have the tab open that you want to turn black. 

## What does the plugin do?

It simply inserts the follwoing CSS to current open tab when clicking on the extension button:

```
body{
    opacity: 1 !important;
}

html{
    background-color: black !important;
}
```

### Lisence

MIT  