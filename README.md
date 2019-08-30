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

### What did I update
Back in the day my price resolver was a really ugly bash script. Now it's all Python-based.

Additionally, I added the item cache (if it doesn't exist in the same directory as the program itself, it will be downloaded as `tornitems.kot`.

Generally speaking, I rewrote the entire thing. Now it is not as disgusting to look at.
