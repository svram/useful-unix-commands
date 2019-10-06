#### Collection of useful unix commands and tool I've used over the years for work and projects

- Search for a pattern string in a directory

```bash
grep -rnw /path/to/dir -e 'pattern_string_to_match'
```
------
- Let the Terminal speak

```bash
say -v ?
```
 to list the voice options.
 
 ```bash
 say -v Alex --r=150 hello sir
 ```
 
 ------
 
 - Ping a remote host
 ```bash
 ping www.HOSTNAME.COM
 ```

------

 - How long is the HOST up
 ```
uptime
```

Sample Output of ```uptime```:

```11:50  up 6 days, 21:41, 4 users, load averages: 3.20 15.22 11.69```

------

- Check disk usage of a directory
```
du -sh /path/to/directory
```

Sample output of ```du```:
```678M	/Users/HOSTNAME/Documents/```

This means that my documents folder has occupied 678 MB of space on disk

------

- Check the weather in any city

```
curl http://wttr.in/LOCATION
```

Enter your city name in ```LOCATION```

