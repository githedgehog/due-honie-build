# due-honie-build

This prepares our [due](https://github.com/CumulusNetworks/DUE) builder which is used to build our version of [ONIE](https://github.com/githedgehog/ONIE).

The modifications we are doing to `due` are minor.
Essentially we just add the YubiHSM packages for the time being plus we fix the due build as it is broken by default.
It tries to include old Debian source lists which do not exist any longer.

There are most likely more changes to come.
Do not forget to update this README when you add changes! :)
