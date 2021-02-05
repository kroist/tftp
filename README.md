# tftp
tftp protocol implementation

Usage:

`./server.py PORT [args]`
arguments:
* `--dir`, e.g. `--dir=/tmp/`
* `--signle-port`

`./client.py ADRESS PORT get filename [args]`
arguments:
* `--blcksize`, e.g. `--blcksize=512`
* `--windowsize`, e.g. `--windowsize=1`
* `--dir`, e.g. `--dir=downloaded/`
