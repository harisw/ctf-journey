# ctf-journey
Simple guide on ctfs


## Steganography
- ```file <filename>```
- ```exiftool <filename>```
- ```strings <filename>```
- ```binwalk <filename>```
  Check for file inside the image
- ```steghide --extract -sf <filename>```
  Try to enter the password found here
  - Stegosolver on internet
  - https://www.aperisolve.com/

## Brute force web
- ```gobuster -u <target> -w <wordlist.txt>```


## Vulnerability scanning
- ```nmap -A -sV <ip-addr>```
- ```nikto -h <ip-addr>```
- ```dirb <url>```

## Useful Linux cmd
- ```sudo -l``` => Check privileges
