# introVyper

[**Vyper**](https://viper.readthedocs.io/en/latest/) is an experimental, contract-oriented, pythonic programming language that targets the Ethereum Virtual Machine (EVM).

> **Security**: It should be possible and natural to build secure smart-contracts in Vyper.

> **Language and compiler simplicity**: The language and the compiler implementation should strive to be simple.

> **Auditability**: Vyper code should be maximally human-readable and, it should be maximally difficult to write misleading code. 

This repo is an exploration of Vyper by example, specifically [this market maker model](https://github.com/ethereum/vyper/blob/764439285d60e8c71dc691ae32f1a5101b9cb046/tests/examples/market_maker/test_on_chain_market_maker.py). It is intended exclusively to help me understand Vyper, and represents no opinion but my own.

### Setup
The easiest way to try out the language, experiment with examples, and compile code to bytecode or LLL is to use the online compiler at [https://vyper.tools]( https://vyper.tools). For Vim users, consider my (*very* alpha version) [vim-vyper](https://github.com/Vvkmnn/vim-vyper) syntax plugin.

### Install

First, we set up a local `python3` environment. I run [Anaconda](https://conda.io/docs/) locally, which comes with an internal environment creator. Both approaches are included below:

```bash
# virtualenv -p python3.6 --no-site-packages ~/vyper-venv  # Vanilla Python
# source ~/vyper-venv/bin/activate
conda create conda create -n introvyper python=3.6         # Conda Python
source activate introvyper
```

To develop [locally](https://github.com/ethereum/vyper/blob/master/docs/installing-vyper.rst) 
```bash
virtualenv -p python3.6 --no-site-packages ~/vyper-venv
source ~/vyper-venv/bin/activate
### Compiler


