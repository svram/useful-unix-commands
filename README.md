#### Collection of useful unix commands and tool I've used over the years for work and projects

- *Search for a pattern string in a directory*

```bash
grep -rnw /path/to/dir -e 'pattern_string_to_match'
```
------
- *Let the Terminal speak*

```bash
say -v ?
```
 to list the voice options.
 
 ```bash
 say -v Alex --r=150 hello sir
 ```
 
 ------
 
 - *Ping a remote host*
 ```bash
 ping www.HOSTNAME.COM
 ```

------

 - *How long is the HOST up*
 ```
uptime
```

Sample Output of ```uptime```:

```11:50  up 6 days, 21:41, 4 users, load averages: 3.20 15.22 11.69```

------

- *Check disk usage of a directory*
```
du -sh /path/to/directory
```

Sample output of ```du```:
```678M	/Users/HOSTNAME/Documents/```

This means that my documents folder has occupied 678 MB of space on disk

------

- *Check the weather in any city*

```
curl http://wttr.in/LOCATION
```

Enter your city name in ```LOCATION```

------

- *Download a file from the internet*

We can use ```wget``` for this. Do a ```brew install wget``` on macOS or ```apt-get install wget``` on Linux

```wget -O windows-security.pdf https://d1.awsstatic.com/whitepapers/aws-microsoft-platform-security.pdf```

The command above downloads the pdf file at the URL resource, renames it and saves it in the current directory.

Sample Output:

Resolving d1.awsstatic.com (d1.awsstatic.com)... 13.225.6.181
Connecting to d1.awsstatic.com (d1.awsstatic.com)|13.225.6.181|:443... connected.
HTTP request sent, awaiting response... 200 OK
Length: 1221064 (1.2M) [application/pdf]
Saving to: ‘windows-security.pdf’

windows-security.pdf                       100%[======================================================================================>]   1.16M   885KB/s    in 1.3s    

2019-10-07 12:10:42 (885 KB/s) - ‘windows-security.pdf’ saved [1221064/1221064]

------



