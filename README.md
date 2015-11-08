irc
===

Homeshick-compatible dotfiles for irc

Dependencies
------------

* [`weechat`](https://weechat.org): IRC client

Installation
------------

```
homeshick clone jrhorn424/irc
homeshick cd irc
./install
```

Post-installation
-----------------

Download the following script plug-ins after starting `weechat` for the first time.

```
/script install buffers.pl
/script install iset.pl
/script install go.py
/script install buffer_autoclose.py
/script install colorize_nicks.py
/script install vimode.py
/vimode bind_keys
```
