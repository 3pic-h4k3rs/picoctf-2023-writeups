Challenge: FindAndOPen
Points: 200

Solution: 

They give us a pcap file, so we have to use wireshark.

They also give us a zip file that requires a password. 

Opening wireshark, we can go through the file and try to find any secrets

At first, I tried to just brute force the zip, but it obviously did not work. 

Sifting through the ethernet, you eventually find a base64 string, as indicated by the = sign at the end

This leads us to half the flag: picoCTF{R34DING_LOKd_

However, half the flag is not all the flag, and I sort of reached a dead end. 

But a day later, out of desperation, I put half the flag as the password, and surpisingly, it worked.

Flag: picoCTF{R34DING_LOKd_fil56_succ3ss_419835ef}
