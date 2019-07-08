# R3CON1Z3R

R3con1z3r is a lightweight Web information gathering tool with an intuitive features written in python. it provides a powerful environment in which open source intelligence (OSINT) web-based footprinting can be conducted quickly and thoroughly. 

Footprinting is the first phase of ethical hacking, its the collection of every possible information regarding the target. R3con1z3r is a passive reconnaissance tool with  built-in functionalities which includes: HTTP header flag, Traceroute, Whois Footprinting, DNS information, Site on same server, Nmap port scanner, Reverse Target and hyperlinks on a webpage. The tool, after being provided with necessary inputs generates an output in HTML format.

# Screenshots

<img width="681" alt="r3con1z3r" src="https://raw.githubusercontent.com/abdulgaphy/webshell/master/screenshots/reconizer.png">
<img width="681" alt="r3con1z3r" src="https://raw.githubusercontent.com/abdulgaphy/webshell/master/screenshots/recon.png">


# Installation

- To install on all Operating Systems (Linux, Windows, Mac OS X, Android e.t.c).
- r3con1z3r supports **Python 2** and **Python 3**.

```bash
   # install from pypi
   pip install r3con1z3r
   or 
   pip3 install r3con1z3r
```

# Usage

r3con1z3r automatically installs a command line tool on system path that can be interacted with by using

```
r3con1z3r [domain.com]
```

# Examples

```
r3con1z3r google.com
```

# Contributors

- [SHUAIB OLADIGBOLU](https://github.com/sawzeeyy)
- [NNAMDI](https://github.com/nnamdei)
- [DIRETNAN DOMNAN](https://github.com/deven96)

# ToDo

- [x] Include travis setup for automatic testing
- [x] Include automatic deployment of incremented versions to pypi so that `pip install r3con1z3r` can work

# License

r3con1z3r is licensed under the GNU GPL license. take a look at the [LICENSE](/LICENSE) for more information.

# Contribution

This project is open to contributions, Bug reports and pull requests are welcome on GitHub at https://github.com/abdulgaphy/r3con1z3r.



# Changelog

1.0 - Release
1.0.1 - pypi
1.0.3 - bug fix
1.0.4 - added argument parsing
1.0.5 - Stable Release
