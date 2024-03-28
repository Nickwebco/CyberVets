# WebDecode Challenge
![WebDecode](https://github.com/Nickwebco/CyberVets/blob/main/PicoCTF/General%20Skills/Super%20SSH/images/WebDecode.png?raw=true)

Start Searching here ( http://titan.picoctf.net:58480/ )

# Hints
- Use the web inspector on other files included by the web page.
- The flag may or may not be encoded

# Solution

Clicking the hyperlink takes you to this website.

![image](https://github.com/Nickwebco/CyberVets/assets/156858289/e6cfd597-d6c8-481d-a972-a1d0aeb1261d)

I then navigated to the "About" section.  I followed the hint and hit ctrl + shift + I to inspect the page.  
I noticed that there was a part under "Section" that looked like a encoded messsage.  (cGljb0NURnt3ZWJfc3VjYzNzc2Z1bGx5X2QzYzBkZWRfMDdiOTFjNzl9)
I navigated to ChatGPT where it identified the hash as Base64 and spit out the flag.
FLAG:  picoCTF{web_succ3ssfully_d3c0ded_07b91c79} 
