This is a repository containing my solutions to the [RPISEC MBE](https://github.com/RPISEC/MBE/) aka **Modern Binary Exploitation** course.

Most of those exploits work correctly, are self-contained and need no fixing or adjusting, couple of them might need so.

The `sshlab.sh` script is intended to be used while SSHing to particular level - it uses `ssh` and `sshpass` - therefore designed to be ran from linux command line containing both applications. Using it one can login into selected level easily just by using this script:

```
$ ./sshlab.sh lab7A 192.168.56.103
```

Finally, couple of them (notably *lab6A*, *lab7A*, *lab9A*) are not finished yet or simply not working / not yielding shell access due to some issues I didn't have patience looking to.

It was a lot of fun doing this VM.

Cheers.
