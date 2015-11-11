## This version only includes Caps Lock indicator as Num Lock is useless on my laptop

![logo.png](http://i.imgur.com/wqRFty2.png)

This is just another indicator for **Lock Keys** with fancy
icons which can enable and disable **Caps Lock**
directly from the **Graphical User Interface**.

## Manually

Install the deps:
```
sudo apt-get install valac libgtk-3-dev libappindicator3-dev libcaribou-dev libgtk-3-bin
```

Build and install system wide:
```
make
sudo make install
```

Then exec `indicator-lockkeys` from command-line or logout and login
in Unity again.

