# zip-cracker

This program is used to crack zip files via 2 methods, bruteforce and dictionary attack. The bruteforce using catchphrases is using the zydra framework, which has been
incorporated into my python application.

## Please use this tool wisely and do not use it against unauthorized files. I will not be responsible for the same.

### PreRequisites
1. make sure to install `Python` and `pip3` (Essential for this script to work).
2. run `python3 requirements.py` to install all the necessary dependecies.

### How does it work:
1. You can create a wordlist file using the tool 'cupp' for using the dictionary attack.
2. Incase you don't have a wordlist file, you can use the bruteforce tool and have some luck at finding the password :))
3. Run `python3 stable-crack.py` to start cracking.
4. I put 2 text files ('hasPass.txt' and 'noPass.txt'--> one of them has the password and the other doesn't, test out the script on the pre-existing zip file to understand how the tool works.

### Compatibility
All the scripts work on linux and MacOS.The bruteforce attack (for which zydra.py is used) is not available on windows currently and i am working on finding an alternative.The dictionary based attack *works* on windows though.

If you have a windows system and want to run all the scripts perfectly, i encourage you to learn more about [WSL](https://docs.microsoft.com/en-us/windows/wsl/install-win10), which will help you to use a linux based distrobution in you windows system.

- Please issue if there is any bug/fault in the application. Since it's my first time building something like this, it would help me in the future.

## Happy cracking :))
