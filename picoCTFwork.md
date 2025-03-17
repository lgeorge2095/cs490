# CTF Solutions

## 1. Fantasy CTF

**Steps:**
- Used the given netcat command to connect to the service.
- Followed the instructions provided in the game.
- Found the first flag after completing the task.

**Flag:**
picoCTF{m1113n1um_3d1710n_d5787049}



## 2. Cookie Monster Secret Recipe

**Steps:**
- Initially, I tried accessing the website and guessing a random password, but it didn’t work.
- The website gave me a hint about the cookies being in plain sight.
- I inspected the webpage elements and searched through them.
- Found the secret recipe hidden in the network tab.
- Decoded the recipe since it was not in a standard flag format.

**Flag:**
picoCTF{c00k1e_m0nster_l0ves_c00kies_DE7A5E76}



## 3. PH4ntom 1ntrud3r

**Steps:**
- The initial clue provided a string of encoded data:
ezF0X3c0cw== NgI1NzkwOQ== XzM0c3lfdA== bnRfdGg0dA== YmhfNHJfZA== cGljb0NURg==

vbnet
Copy
- Attempted to decode these fragments.
- Tried to reassemble them with a decoding tool.
- However, I couldn't successfully extract the flag.

**Expected Flag:**
picoCTF{1t_w4s_34sy_t0_f1nd_th4t_bh_4r_d}



## 4. hashcrack

**Steps:**
- Used the given netcat command, which provided a hash and password.
- Identified the hash types using a hash identifier tool:
  - First hash: MD5
  - Second hash: SHA-1
  - Last hash: SHA-256
- Cracked each of these hashes using online tools.
- The cracked hashes provided me with the correct password.

**Flag:**
picoCTF{UseStr0nG_h@shEs_&PaSswDs!_eff9dbe0}



## 5. Head-dump

**Steps:**
- Launched the website and browsed the page until I found a link to #API Documentation.
- This led me to another page where the heap dump was located.
- I was instructed to download and analyze the file to find the flag.
- Unfortunately, I was unable to analyze the file properly and couldn't find the flag.

**Status:**
- Could not complete the challenge.



## 6. RED

**Steps:**
- Downloaded the image, which was simply a red square.
- Noticed a hint in one of the descriptions referencing the rebranding of Facebook.
- Checked the image's metadata and found a hidden poem.
- The first letters of the poem spelled "CHECKLSB."
- Used the tool `zsteg` to decode the PNG image.
- Successfully decoded the flag.

**Flag:**
picoCTF{r3d_1s_th3_ult1m4t3_cur3_f0r_54dn355_}
