# clevis-more
This project add some more pins for [clevis](https://github.com/latchset/clevis)

## clevis-*-chain
Chain multiple pins. Contrary to `sss`, it hide what pin(s) are inside next layer

## clevis-*-tpm2clock
Use tpm2 clock and counters as a pin. Allow for instance to authorize a policy for a single reboot
This can be useful in case of an upgrade that would change pcr values, to have a single boot allowed with this policy until the pcr based policy is fixed


Code is heavilly borrowed from [clevis](https://github.com/latchset/clevis) pins, and is released under the same license
