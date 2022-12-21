
<h1 align="center">Domains Blacklist as Partial Output of Bash Script</h1>

<p align="center">
  <b>domains blacklist as partial output from link below</b><br>
  <a href="https://github.com/ngadmini/Grabbing-Blacklist-for-Bind9-RPZ"><img src="https://img.shields.io/badge/bind9%20RPZ-Grabbing%20Blacklist%20for%20Bind9%20RPZ-blue?style=flat-square&logo=github"></a>
  <br><br>
  <a href="#"><img src="http://s.4cdn.org/image/title/105.gif"></a>
</p>

### usage
joint `txt.adulta*` then use `grab_build.sh` in [this repo](https://github.com/ngadmini/Grabbing-Blacklist-for-Bind9-RPZ/blob/master/libs/grab_build.sh)
```
~$ curl -s -o rpz_db.zip https://codeload.github.com/ngadmini/partial-output/zip/refs/heads/master
~$ curl -s -o "partial-output-master/grab_build.sh" https://raw.githubusercontent.com/ngadmini/Grabbing-Blacklist-for-Bind9-RPZ/master/libs/grab_build.sh
~$ curl -s -o "partial-output-master/grab_library" https://raw.githubusercontent.com/ngadmini/Grabbing-Blacklist-for-Bind9-RPZ/master/libs/grab_library
~$ unzip rpz_db.zip -x partial-output-master/{LICENSE,README.md,.gitignore}
~$ cat partial-output-master/txt.adulta* > partial-output-master/txt.adult
~$ rm partial-output-master/txt.adulta*
~$ bash partial-output-master/grab_build.sh
```
you will get domain list in BIND9-rpz format in 5 catagories AND 7 sub-categories of adult category. Enjoy it's

### license
- [x] [![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]
- [x] This work is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg
