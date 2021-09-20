# fiduswriter-gesis

Fidus Writer integration for the Fidus Writer instance of GESIS.

Installation
============

To install run this on the command line:

```
sudo bash
cd /var/snap/fiduswriter/current
git clone git@github.com:fiduswriter/fiduswriter-gesis.git
ln -s fiduswriter-gesis/gesis .
exit
sudo fiduswriter.configure
```

----
Remember that this repository does not update automatically the way the main Fidus Writer package does. You need to manually install new versions.
