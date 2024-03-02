# Nmap
tryhack me nmap
## Nmap Format
nmap [scan type] [options] [target specification]
scan type = (use man Nmap)
options = (Use man Nmap)
Target Specification = can be domain name, IP address, Network etc
## Nmap Switches
Use (man Nmap) for each question.
1. What is the first switches listed in the help menu for a 'Syn Scan'
   - -sS
   - eg: nmap -sS tryhackme.com
2. Which switch would you use for a "UDP scan"?
   - -sU
   - eg: nmap -sU tryhackme.com
3. If you wanted to detect which operating system the target is running on, which switch would you use?
   - -O
   - eg: nmap -O tryhackme.com
4. Nmap provides a switch to detect the version of the services running on the target. What is this switch?
   - -sV
   - eg: nmap -sV tryhackme.com
5. The default output provided by nmap often does not provide enough information for a pentester. How would you increase the verbosity?
   - -v
   - eg: nmap -sS -v tryhackme.com
6. Verbosity level one is good, but verbosity level two is better! How would you set the verbosity level to two?
   - -vv
   - eg: nmap -sS -V tryhackme.com
7. What switch would you use to save the nmap results in three major formats?
   - -oA
   - eg:nmap -sS -oA targetfile tryhackme.com
8. What switch would you use to save the nmap results in a "normal" format?
   - -oN
   - eg: nmap -sS -oN tragetfile.txt tryhackme.com
9. A very useful output format: how would you save results in a "grepable" format?
   - -oG
   - eg: nmap -sS -oN targetfile.txt tryhackme.com
10. Sometimes the results we're getting just aren't enough. If we don't care about how loud we are, we can enable "aggressive" mode. This is a shorthand switch
    that activates service detection, operating system detection, a traceroute and common script scanning. How would you activate this setting?
    - -A
    - eg: nmap -A tryhackme.com
11. Nmap offers five levels of "timing" template. These are essentially used to increase the speed your scan runs at. Be careful though: higher speeds are
    noisier, and can incur errors!. How would you set the timing template to level 5?
    - -T5
    - eg:nmap -T5 tryhackme.com
12. How would you tell nmap to only scan port 80?
    - -p 80
    - nmap -p 80 tryhackme.com
13. How would you tell nmap to scan ports 1000-1500?
    - -p 1000-1500
    - eg: nmap p 1000-1500 tryhackme.com
14. How would you tell nmap to scan all ports?
    - -p
    - eg: nmap -p tryhackme.com
15. How would you activate a script from the nmap scripting library
    - --script
16. How would you activate all of the scripts in the "vuln" category?
    - --script=vuln
    - eg: nmap --script=vuln tryhackme.com

