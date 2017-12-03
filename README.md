# JavaScript miner for the cryptocurrency Monero Blockchain (XMR) using Coin-Hive

# Use Client's CPU Power
Monero is different. To mine Monero, you have to calculate hashes with an algorithm called Cryptonight. This algorithm is very compute heavy and – while overall pretty slow – was designed to run well on consumer CPUs.

There are solutions to run the Cryptonight algorithm on a GPU instead, but the benefit is about 2x, not 10000x like for other algorithms used by Bitcoin or Ethereum. This makes Cryptonight a nice target for JavaScript and the Browser.

Of course, when running through JavaScript performance still takes a bit of a toll, but it's not that bad. Our miner uses WebAssembly and runs with about 65% of the performance of a native Miner. For an Intel i7 CPU (one of the fastest desktop CPUs) you should see a hashrate of about 90h/s. A native miner would get to 140h/s.

## How to use
It’s very simple, download and open the page coinhive-monero.html

You must sign-in on coinhive.com, copy the site-key, and paste in my page coinhive-monero.html
modify SITE_KEY: Coin-Hive's Site Key

Automaticaly the Javascript into start mining with your CPU.

On coinhive you could see the progress of you Monero mining

Also, if you are a programmer, you could copy my js to paste in some your page, in this way your visitors will do mining for you. ;)

## Disclaimer
This project has nothing to do with `coin-hive.com`
