#chadu
=====

#####Jump directly to any inner recursive directory..
#####chadu means jump

---

**How to install**

```shel
wget -O /usr/bin/chadu https://raw.github.com/jophinep/chadu/master/chadu
chmod +rx /usr/bin/chadu
echo 'alias chadu=". chadu"' >> ~/.bashrc
source ~/.bashrc
```
---

**Description**

Used to jump directly to any inner recursive directory

use as: `chadu [dir-name/part of dir-name]`

---

Suppose you are in `'/home/jophine/jack/'` and you need to jump to `'/home/jophine/jack/fetch/water/pot'`

just use `chadu pot` or `chadu po`

You will have a list of options like:

1 /home/jophine/jack/fetch/water/pot

2 /home/jophine/jack/drink/water/pot

3 /home/jophine/jack/fetch/lake/pot

4 /home/jophine/jack/drink/ice/pot

now choose 1 and give ENTER

---
