# Teleport

Simple and secure teleportation tool for your terminal. Allow completion on remote servers and local files.

```zsh
teleport /path/to/file to [username]@[hostname]:[port] in /remote/path
```

Default port is 22.

Completion available only with zsh now.

## Teleport Hosts

Create file `.teleport_hosts` in your home directory. And add hosts like this:
```rc
abobka=root@192.168.127.10
host2=root@192.168.127.10:4544  <-- custom port
```

And now you can teleport any files by typing:

```zsh
teleport /kek.txt to abobka in /home/abobka
```
