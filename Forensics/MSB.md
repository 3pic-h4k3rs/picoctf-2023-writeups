# Challenge: MSB
Points: 200

# Solution: 

Judging by the title, MSB most likely refers to "Most Significant Bit".

However, most decoding tools use LSB, or "Least Significant Bit" to decode.

Given the file, it appears massively corrupted. Thinking for a while, I realized this was because the 0th bit of the color bytes was
most likely the message, which is why it appears so strange

Going on CyberChef, and putting the image in, I go to Extract LSB, set R, G, B as well as the byte to 7 since it is going by LSB, so we just go to 7 to
reach the most significant byte. 

![Screenshot from 2023-04-07 21-05-33](https://user-images.githubusercontent.com/128765475/230696759-0d128d4f-450e-45ba-abd2-d80496533121.png)

This gives us a book, but we have no time to read through it. Just command F, and type in "picoCTF" and the flag will be shown. 

And, we get the flag:

```picoCTF{15_y0ur_que57_qu1x071c_0r_h3r01c_ee3cb4d8}```
