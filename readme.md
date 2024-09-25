# DATASCI 217

## Links:

[Official Python Site](https://www.python.org)## Assignment 1

### Prompt:

If we list all the natural numbers below 10 that are multiples of 3 or 5, we get (3, 5, 6, 9). 
The sum of these multiples is 23. Find the sum of all the multiples of 3 or 5 below 1000.

### Solution: 

values = [0]

for x in range(1001):
    if x % 3 == 0:
        values.append(x)
    elif x % 5 == 0:
        values.append(x)
    
sumval = sum(values)

print(sumval)


## Photos practice: 

![screenshot of numpy installation](numpy-install-venv.png)

Click on the image!

[![image of Olympics meme captioned 'girls packing for a trip vs guys packing for a trip'](https://x.com/nonpoccafe/status/1818729033296916618?ref_src=twsrc%5Etfw%7Ctwcamp%5Etweetembed%7Ctwterm%5E1818729033296916618%7Ctwgr%5Ef870c447e2a64328f15ee37e0dd3f1c7c12c0d54%7Ctwcon%5Es1_c10&ref_url=https%3A%2F%2Fembedly.forbes.com%2Fwidgets%2Fmedia.html%3Ftype%3Dtext2Fhtmlkey%3D3ce26dc7e3454db5820ba084d28b4935schema%3Dtwitterurl%3Dhttps3A%2F%2Fx.com%2Fnonpoccafe%2Fstatus%2F1818729033296916618image%3D)](https://www.youtube.com/watch?v=dQw4w9WgXcQ)

