
## LFI for Lateral Movement? Gain SSH Access?

```
?file=../../../../../../../../home/user/.ssh/id_rsa
?file=../../../../../../../../home/user/.ssh/id_rsa-cert
```


# SSH Private Key Looting Wordlists 🔒🗝️

This repository contains a collection of wordlists to aid in locating or brute-forcing SSH private key file names. These wordlists can be useful for penetration testers, security researchers, and anyone else interested in assessing the security of SSH configurations.

[![GitHub Release](https://img.shields.io/github/release/PinoyWH1Z/SSH-Private-Key-Looting-Wordlists.svg?style=flat-square)](https://github.com/PinoyWH1Z/SSH-Private-Key-Looting-Wordlists/releases)
[![GitHub License](https://img.shields.io/github/license/PinoyWH1Z/SSH-Private-Key-Looting-Wordlists.svg?style=flat-square)](https://github.com/PinoyWH1Z/SSH-Private-Key-Looting-Wordlists/blob/master/LICENSE)

## Wordlist Files 📝

- **ssh-priv-key-loot-common.txt**: Default and common naming conventions for SSH private key files.
- **ssh-priv-key-loot-medium.txt**: Probable file names without backup file extensions.
- **ssh-priv-key-loot-extended.txt**: Probable file names with backup file extensions.
- **ssh-priv-key-loot-\*_w_gui.txt**: Includes file names simulating Ctrl+C and Ctrl+V on servers with a GUI.

## Usage 🚀

These wordlists can be used with tools such as Burp Intruder, Hydra, custom python scripts, or any other bruteforcing tool that supports custom wordlists. They can help expand the scope of your brute-forcing or enumeration efforts when targeting SSH private key files.

## Acknowledgements 🙏

This wordlist repository was inspired by John Hammond in his vlog "[Don't Forget This One Hacking Trick.](https://www.youtube.com/watch?v=2rqb3YSa1SE)" 

## Disclaimer ⚠️

Please use these wordlists responsibly and only on systems you are authorized to test. Unauthorized use is illegal.
