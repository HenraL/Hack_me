# Hack_me
This is a prank bash script I wrote myself

## Run on the fly:
Do you wish to run the prank without leaving a trace, why not try this command:
Prank the person using any name:
```bash
curl -L https://raw.githubusercontent.com/HenraL/Hack_me/main/Hack_me | bash -s <your_name>
```
or if you prefer with `wget`:
```bash
wget -q -O - https://raw.githubusercontent.com/HenraL/Hack_me/main/Hack_me | bash -s <your_name>
```
Prank the person using the account name:
```bash
curl -L https://raw.githubusercontent.com/HenraL/Hack_me/main/Hack_me | bash -s $(whoami)
```
or if you prefer with `wget`:
```bash
wget -q -O - https://raw.githubusercontent.com/HenraL/Hack_me/main/Hack_me | bash -s $(whoami)
```
Prank the person using the computer name:
```bash
curl -L https://raw.githubusercontent.com/HenraL/Hack_me/main/Hack_me | bash -s $(uname -n)
```
or if you prefer with `wget`:
```bash
wget -q -O - https://raw.githubusercontent.com/HenraL/Hack_me/main/Hack_me | bash -s $(uname -)
```
