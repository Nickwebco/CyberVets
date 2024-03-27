# Super SSH Challenge

![Super SSH Challenge](https://github.com/Nickwebco/CyberVets/blob/main/PicoCTF/General%20Skills/Super%20SSH/images/Super%20SSH%20Challenge.png?raw=true)

# Hint
- https://linux.die.net/man/1/ssh
- You can try logging in 'as' someone with <user>@titan.picoctf.net
- How could you specify the port?
- Remember, passwords are hidden when typed into the shell

# Solution
Utilize the webshell and log into the user and port.  Check the image below

![webshell soln](https://github.com/Nickwebco/CyberVets/blob/main/PicoCTF/General%20Skills/Super%20SSH/images/ssh-sln.png?raw=true)

Use:  ssh ctf-player@titan.picoctf.net -p 50832
Flag: picoCTF{s3cur3_c0nn3ct10n_07a987ac}
