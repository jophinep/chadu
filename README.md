#chadu
=====

#####Jump directly to any inner recursive directory..
#####chadu means jump

---

**How to install?**

You will need sudo or root permission to do the installation

Download the chadu installation package: https://github.com/jophinep/chadu/archive/master.zip

Extract it and open the chadu-master directory

Then execute the following commands
```shel
chmod +x install
./install
```
---

**Description**

Used to jump directly to any inner recursive directory

---

**How to Use?**

use as: `chadu [dir-name/part of dir-name]`

---

Suppose you are in `'/home/jophine/jack/'` and you need to jump to `'/home/jophine/jack/fetch/water/pot'`

just use `chadu pot` or `chadu po`

You will have a list of options like:

0 /home/jophine/jack/fetch/water/pot

1 /home/jophine/jack/drink/water/pot

2 /home/jophine/jack/fetch/lake/pot

3 /home/jophine/jack/drink/ice/pot

now choose 0 and give ENTER

---

**Make it FAAASTER**

To make the command run faster, avoid running it from home directory or its parent directories

---

**Note: Chef Users**

Chef users, you can find a cookbook for chadu installation is opscode community
http://community.opscode.com/cookbooks/chadu

---
