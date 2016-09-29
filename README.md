# C++ Pota interpreter
To learn more about Pota programming language check out the [wiki](https://delfad0r.github.io/pota-wiki/).

## Setup
### Linux
To install the Pota interpreter download the repository somewhere (either via `git clone https://github.com/Delfad0r/cpota.git` or via the [button](https://github.com/Delfad0r/cpota/archive/master.zip) kindly provided by GitHub).  
Then, in the `cpota` directory, do something .-.

## Running
To execute a Pota program simply type `cpota myprogram.pota`.

### What do I lose?
Flexibility.  
Compared to the (official) [Python Pota interpreter](https://github.com/Delfad0r/pota), `cpota` lacks

- arbitrary precision integers (in `cpota` integers are represented by the native C++ `long long` type)
- every interpreter option but `-s`; this means that the tremendously useful debug mode (`-d`) is not available in `cpota`

### What do I gain?
Performance.  
No but seriously, try running something with `pota` and with `cpota` and see the difference.
