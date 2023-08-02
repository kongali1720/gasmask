# Gasmask
Gasmask – Information Gathering Tool in Kali Linux
Gasmask is a free and open-source tool available on Github. Gasmask is an Open Source Intelligence and Information Gathering Tool based on (OSINT). 
Gasmask is capable of doing everything almost you need for reconnaissance as per your need it can perform reconnaissance easily. Gasmask works as an open-source tool intelligence tool.
It integrates with just about every data source available and utilizes a range of methods for data analysis. Gasmask is written in python language. 
You must have python language installed into your Kali Linux system in order to use the Gasmask tool. This tool is used to get various information about our target.  
This information includes DNS server information, organization name, address, city, zip, country, email address related to the respective organization, registrars, naming servers, DNS information.
The dependencies of the tool include Python 3, x validators, python-whois, dnspython, requests, nmap, shodan, censys, pprint. For information gathering, 
this tool uses the following modules and information gathering sources virustotal, yahoo, spyse, youtube, yandex, shodan, reverse dns, netcraft, whois, bing, censys.io, dns, github, dnsdumpster,  
instagram, crt, ask, dogpile. These were the modules for which the tool uses the publicly available data to get information about the target.

# Features of Gasmask:

    Gasmask is a free and open-source tool available on Github. This means you can download and install this tool freely.
    Gasmask is an Open Source Intelligence and Information Gathering Tool (OSINT).
    Gasmask is used for performing reconnaissance.
    Gasmask works as an open-source tool intelligence tool which means open-source information is used by this tool to perform reconnaissance.
    Gasmask is written in python language. This means you must download and install python language in your Kali Linux operating system.
    Gasmask has some dependencies which are Python 3, x validators, python-whois, dnspython, requests, mmap, shodan, censys, pprint.
    Gasmask uses the following modules to perform reconnaissance dns, netcraft, whois, bing, censys.io, dns, Github, dnsdumpster,  instagram, crt, ask, etc.
    Gasmask is a free tool. You don’t need to pay any amount to anyone to use this tool as it is an open-source tool.

# Gasmask installation:
cd Desktop
mkdir Gasmask
cd Gasmask
git clone https://github.com/kongali1720/gasmask.git
ls
cd gasmask
ls
pip3 install -r requirements.txt
python3 gasmask.py
python3 gasmask.py -d testphp.vulnweb.com -i basic
python3 gasmask.py -d testphp.vulnweb.com -i whois
