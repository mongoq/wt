# wt
Run Linux commands per SSH without complicated login procedures.

Use wt (change wt command name to a short name that fits your server i.e. **brutus** -> **bt**).

Example commands to run on your server:

```wt ping pong.de```

```wt htop```

```wt shutdown -h now```

```wt``` (passwordless SSH-login)

To use **wt** either copy and run the script **wt** or copy the file **.bash_aliases** to your home directory to use wt from this repository.

Before you can run remote commands you have to setup your server to passwordless SSH-login.

TODO: Write short summary on https://linuxize.com/post/how-to-setup-passwordless-ssh-login/ 
or https://checkmk.com/de/linux-wissen/ssh-anmeldung-ohne-passwort

Don't forget to change the server name (in the scripts) to one that fits your needs.
