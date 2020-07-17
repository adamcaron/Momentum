# Momentum customized.

Remove the clock and the clutter, and everything but the quote so the nice picture is all you see. See [below](#how-it-looks) for how it looks.

[Momentum Dashboard](https://momentumdash.com/) for Chrome turns your new tab windows into stunning photos. The problem is they blanket the image with all sorts of text and clutter, and unnecessary links and widgets. This repo has instructions to replace Momentum's extension with a stripped-down extension that renders only:
1. The beautiful image
2. A quote
3. That's it.

## How? 

In the `manifest.json`, the loaded `.html` file is specified.

Clone this repo into your home directory, then follow the instructions:

## To load into chrome:

Go to Chrome Settings (☰) > More Tools > Extensions
 - click 'Load unpacked extension...' and select the momentum version wherever it is in your computer's directory structure.

 > Note: the original location of Chrome extensions is `~/Library/Application\ Support/Google/Chrome/Default` http://stackoverflow.com/questions/17377337/where-to-find-extensions-installed-folder-for-google-chrome-on-mac

## How it looks

It changes your dashboard from this...

![Stupid,Crappy Image](bleh_momentum.png)

To this...

![Clean, Happy Image](clean_momentum.png)

Oh sweet blissful clarity
