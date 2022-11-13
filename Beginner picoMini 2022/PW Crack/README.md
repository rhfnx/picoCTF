# PW Crack 🖥️
## Points 🏆
- ```100 Points```
## Tags PW Crack 1&2 🔗
- ```Beginner picoMini 2022```
- ```General Skills```
- ```password_cracking```
## Tags PW Crack 3,4,5 🔗
- ```Beginner picoMini 2022```
- ```General Skills```
- ```password_cracking```
- ```hashing```

## Author ⭐
- LT 'SYREAL' JONES

## Description PW Crack 1 📖
Can you crack the password to get the flag? Download the password checker here and you'll need the encrypted flag in the same directory too.

## Description PW Crack 2 📖
Can you crack the password to get the flag? Download the password checker here and you'll need the encrypted flag in the same directory too

## Description PW Crack 3 📖
Can you crack the password to get the flag? Download the password checker here and you'll need the encrypted flag and the hash in the same directory too. There are 7 potential passwords with 1 being correct. You can find these by examining the password checker script.

## Description PW Crack 4 📖
Can you crack the password to get the flag? Download the password checker here and you'll need the encrypted flag and the hash in the same directory too. There are 100 potential passwords with only 1 being correct. You can find these by examining the password checker script.

## Description PW Crack 5 📖
Can you crack the password to get the flag? Download the password checker here and you'll need the encrypted flag and the hash in the same directory too. Here's a dictionary with all possible passwords based on the password conventions we've seen so far.

## Hints PW Crack 1 ❓
> 1. To view the file in the webshell, do: $ nano level1.py
> 2. To exit nano, press Ctrl and x and follow the on-screen prompts.
> 3. The str_xor function does not need to be reverse engineered for this challenge.

## Hints PW Crack 2 ❓
> 1. Does that encoding look familiar?
> 2. The str_xor function does not need to be reverse engineered for this challenge.

## Hints PW Crack 3 ❓
> 1. To view the level3.hash.bin file in the webshell, do: $ bvi level3.hash.bin
> 2. To exit bvi type :q and press enter.
> 3. The str_xor function does not need to be reverse engineered for this challenge.

## Hints PW Crack 4 ❓
> 1. A for loop can help you do many things very quickly.
> 2. The str_xor function does not need to be reverse engineered for this challenge.

## Hints PW Crack 5 ❓
> 1. Opening a file in Python is crucial to using the provided dictionary.
> 2. You may need to trim the whitespace from the dictionary word before hashing. Look up the Python string function, strip
> 3. The str_xor function does not need to be reverse engineered for this challenge.


## Solutions PW Crack 1 🎯
- Download the file from the Challenge.

  <details>
  
  <summary>File List 📁</summary>
  
  |FILE|DOWNLOAD FILE|VIEW FILE|
  |----|-------------|---------|
  |level1.py|[Download](https://artifacts.picoctf.net/c/52/level1.py)|[Click here](https://github.com/rhfnx/picoCTF/blob/main/Beginner%20picoMini%202022/PW%20Crack/level1.py)|
  |level1.flag.txt.enc|[Download](https://artifacts.picoctf.net/c/52/level1.flag.txt.enc)|[Click here](https://github.com/rhfnx/picoCTF/blob/main/Beginner%20picoMini%202022/PW%20Crack/level1.flag.txt.enc)|
  
  </details>
  
- Try run the file. you can see there is a password to input on the program if we want the flag.</br>
  ![image](https://user-images.githubusercontent.com/108726715/200016100-87331802-e392-42ed-b964-a400185ec389.png)</br>
- Now check the source code, maybe we can find something in there.</br>
  ![level1](https://user-images.githubusercontent.com/108726715/200016246-0fb50e4f-6cb3-4367-a541-7e6ac2a3a8f4.png)</br>
- There is a password ```1e1a```, try run it again and input the password.</br>
  ![image](https://user-images.githubusercontent.com/108726715/200016510-10a8e211-ff65-4fa3-84e1-40bce4c8dc85.png)</br>
 - the flag is ```picoCTF{545h_r1ng1ng_fa343060}```

## Solutions PW Crack 2 🎯
- Download the file from the Challenge.

  <details>
  
  <summary>File List 📁</summary>
  
  |FILE|DOWNLOAD FILE|VIEW FILE|
  |----|-------------|---------|
  |level2.py|[Download](https://artifacts.picoctf.net/c/18/level2.py)|[Click here](https://github.com/rhfnx/picoCTF/blob/main/Beginner%20picoMini%202022/PW%20Crack/level2.py)|
  |level2.flag.txt.enc|[Download](https://artifacts.picoctf.net/c/18/level2.flag.txt.enc)|[Click here](https://github.com/rhfnx/picoCTF/blob/main/Beginner%20picoMini%202022/PW%20Crack/level2.flag.txt.enc)|
  
  </details>
 - Try run the file, this challenge it's the same as ```PW Crack 1```.</br>
  ![image](https://user-images.githubusercontent.com/108726715/200020551-2f67db92-ce06-4416-8168-a335de3ba4b5.png)</br>
 -  Check the source code.</br>
  ![level2](https://user-images.githubusercontent.com/108726715/200020911-d4c478d6-c108-4074-9354-1d0fa8f039d0.png)<br>
 - Let's try print the password using python in terminal.</br>
  ![image](https://user-images.githubusercontent.com/108726715/200021323-beff4285-7002-4981-9e3e-629b03706bbd.png)</br>
 - The password is ```39ce``` , Let's try run it again and input the password.</br>
  ![image](https://user-images.githubusercontent.com/108726715/200021686-08c00aad-b23c-4fb4-ba97-5f06bf4aed26.png)</br>
 - The flag is ```picoCTF{tr45h_51ng1ng_502ec42e}```

## Solutions PW Crack 3 🎯
- Download the file from the Challenge.

  <details>
  
  <summary>File List 📁</summary>
  
  |FILE|DOWNLOAD FILE|VIEW FILE|
  |----|-------------|---------|
  |level3.py|[Download](https://artifacts.picoctf.net/c/23/level3.py)|[Click here](https://github.com/rhfnx/picoCTF/blob/main/Beginner%20picoMini%202022/PW%20Crack/level3.py)|
  |level3.flag.txt.enc|[Download](https://artifacts.picoctf.net/c/23/level3.flag.txt.enc)|[Click here](https://github.com/rhfnx/picoCTF/blob/main/Beginner%20picoMini%202022/PW%20Crack/level3.flag.txt.enc)|
  |leve3.hash.bin|[Download](https://artifacts.picoctf.net/c/23/level3.hash.bin)|[Click here](https://github.com/rhfnx/picoCTF/blob/main/Beginner%20picoMini%202022/PW%20Crack/level3.hash.bin)|
  
  </details>
- Try run the file, you can see we need password to get the flag.<br/>
  ![image](https://user-images.githubusercontent.com/108726715/201508139-ef65c4ab-36db-4565-92bd-0a97dcca9cac.png)</br>
- Check the code using text editor
- On the bottom line there are 7 strings which only 1 can be the real password we looking for.</br>
  ![level3](https://user-images.githubusercontent.com/108726715/201508843-4886a8a4-fedc-4c53-bff6-f11ee2763d1b.png)</br>
- I try this and it's work!</br>
  ![image](https://user-images.githubusercontent.com/108726715/201508900-43e76c58-df51-4d3f-8ef4-7d5cf7cd8d03.png)</br>
- the flag is ```picoCTF{m45h_fl1ng1ng_2b072a90}```




## Solutions PW Crack 4 🎯
- Download the file from the Challenge.

  <details>
  
  <summary>File List 📁</summary>
  
  |FILE|DOWNLOAD FILE|VIEW FILE|
  |----|-------------|---------|
  
  </details>

## Solutions PW Crack 5 🎯
- Download the file from the Challenge.

  <details>
  
  <summary>File List 📁</summary>
  
  |FILE|DOWNLOAD FILE|VIEW FILE|
  |----|-------------|---------|
  
  </details>
  
  
