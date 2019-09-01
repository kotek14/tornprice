# tornprice
Kotek's crutch for figuring out Torn City item market prices. Also works while travelling

### Hey!
This tool allows you to just enter the item's name and receive twenty lowest item market prices.

Why twenty? I dunno, because.

The main thing is that you don't need an ID, you only need the name.

### Dependencies
I dunno.

- Python

### Installation
`git clone https://github.com/kotek14/tornprice.git`

### How to run
First edit the script itself and insert your API key to wherever it says "INSERT YOUR KEY HERE" (don't touch the quotes. I warned you). Simple as that.

After that you can run it and it will work unless

A: Your key is wrong

B: My code sucks

`python tornprice`

### Updates

#### Version 1.7

Added `--flowers` function that calculates prices of all of your prices.

Added `--plushie-set` and `--flower-set` functions that check if you need items for complete item sets.

Added `--points` function that returns prices for 10 points, flower set and a plushie set.

Q: "Kotek, where are versions 1.5 and 1.6?"

A: "They never existed. I pick a version whichever version number I feel like picking"

#### Version 1.4

Normal command-line interface. Well, I call it "normal" because I used the "normal" tools to do it. It's still a crutch.

I can't explain why, but trust me. It's important.

To get a list of all command-line options, type in `-h` or `--help`, just like you do with every other command-line program. Don't know what I'm talking about? Too bad! I tried doing a GUI once and it still follows me in my nightmares.

I added a function that goes through your inventory and counts up all of the plushies.

Pretty useful for plushie-stackers like myself.

Can be invoked by a parameter `--plushies`

#### Before Aug 31st

Back in the day my price resolver was a really ugly bash script. Now it's all Python-based.

Additionally, I added the item cache (if it doesn't exist in the same directory as the program itself, it will be downloaded as `tornitems.kot`.

Generally speaking, I rewrote the entire thing. Now it is not as disgusting to look at.
