# IRC Bot for pentest study

This project aims to provide a tiny example of how an IRC Bot can serve as an agent of DoS attacks.

# Quick start

Make sure that you have IO::Socket dependency and Threads support at your Perl setup and run the following commands:

**On a Linux shell:**

```
$ sudo chmod 744 irc-bot
$ ./irc-bot
```

**On a Windows Prompt:**

```
x:\> perl irc-bot
```

# FAQ

Q: How to evaluate whether the attack is being successful?<br/>
A: Run `sudo tcpdump -i <interface> -v udp`

# Contributing

Please, feel free to send us pull requests.

# Changelog

None so far.

# License

This software is under GPL v3 license. For further information, please take a look on LICENSE file.