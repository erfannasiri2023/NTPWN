# NTPWN
this is how when we are in a network and we need to find live hosts and scan them easy and not noisy.
Install with zip & unzip Mapcidr --> tandile range be ip Haye joda | mv Kon be bin
-------------------
2.Echo "10.160.32.0/24" | Mapcidr
------------------
3.Echo "10.160.32.0/24" | Mapcidr | httpx -sc -st
status code 
-------
4.Echo "10.160.32.0/24" | Mapcidr | httpx -p 1-65535 -stats
Scan Koni block nmishe intoori.
------
5.Echo "10.160.32.0/24" | Mapcidr | naabu -p 1-65535 | httpx | nuclei -es "info,low"
6.Echo "10.160.32.0/24" | naabuu --nmap
Result ro bede :
cat ./result.txt | cut -d ":" -f 2 | tr "\\n" ","
Resulte in k port hast ro bede be nmap intoori:
nmap -A -p 443,6687,6565,2345,... ip
For speed modern port scanner:
Rust scan --> fastest
Naabu --> faster
Nmap --> Fast
