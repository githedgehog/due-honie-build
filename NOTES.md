# NOTES

Random due command lines and stuff.
This is essentially a scratchpad right now:

```console
ONIE_USE_SYSTEM_DOWNLOAD_CACHE=TRUE

duebuild --use-directory $HOME/git/onie/build-config --machine qemu_armv8a --jobs 1 --build-targets "all recovery-iso"



due --build --use-directory $HOME/git/onie/build-config --machine qemu_armv8a --jobs 1 --build-targets "all recovery-iso"

due -c --platform linux/amd64 --name honie-build --prompt HONIE --tag honie --use-template honie --from debian:11

**Example:** due --run --build --jobs 4 --machine kvm_x86_64 --build-targets all demo recovery-iso  
**Example:** due --run --build --jobs 4 --machine accton_as7112_54x --build-targets all demo recovery-iso  
```
