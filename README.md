# tornprice [LINUX]
Kotek's crutch for figuring out Torn City item market prices. Also works while travelling

### Hey!
This tool allows you to just enter the item's name and receive twenty lowest item market prices.

Why twenty? I dunno, because.

The main thing is that you don't need an ID, you only need the name.

### Dependencies
I dunno.

- Python
- Curl
- Sed
- Sort

### Installation
`git clone https://github.com/kotek14/tornprice.git`

### How to run
First edit the script itself and insert your API key to wherever it says "INSERT YOUR KEY HERE". Simple as that.

After that you can run it and it will work unless

A: Your key is wrong

B: My code sucks

`python tornprice`

### Why Linux only?
Basically, the price resolver is an ugly bash script, so I cannot promise anything to Windows users.

Probably I will make it work properly one day.
