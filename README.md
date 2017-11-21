# vbhardening

This repo is intented to obfuscate VM. It helps to hide VM from malware and other aggressive *ware, which refuses to run under VM.

## How does it works?
Every hypervisor has it's unique fingerprint. 
Some techiniques are based on hardware detection only, as while as others rely on memdump, strings, network stack and so on.

So actually we patch all SLIC, DSDT and hardware resources as well. This helps to bypass most of the checks.


## Usage

 * edit scripts (e.g. fix path)
 * run ```hu-patch-n-install-vbox.sh```
 * run ```hu-obfuscate-vm.sh```


## License
MIT License
