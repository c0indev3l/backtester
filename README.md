# Cryptrality backtest

A flexible way to backtest scripts with a trality-like API.


## Install

    pip install git+https://git@github.com/Cryptrality/backtester.git/




### Config file

if a file named `bot.config` is found in the current directory, the content
of the file will be parsed to get API keys and various other info.
The content of the file look like:

    SLIPPAGE = 0.0008
    FEES = 0.0002
    CACHED_KLINES_PATH = cached_klines
    INITIAL_BALANCE = 1000

More documentation in [Cryptrality](https://cryptrality.readthedocs.io)
readthedocs pages.

There is also a discord channel for people interested in brainstorming
and chat about the engine [here](https://discord.gg/jk8gNzg6)
