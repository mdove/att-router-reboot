# att-router-reboot
Simple python script that logs into and then reboots `BGW210` and `BGW320-500` routers provided by AT&T.

Tested on `BGW320-500` under python 3.13.

## Usage

Migrated to `uv` for virtual machine management:

% uv run att-reboot.py -a <device code>
