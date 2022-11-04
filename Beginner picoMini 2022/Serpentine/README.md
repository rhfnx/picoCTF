# Serpentine 🐍
## Points 🏆
- ```100 Points```

## Tags 🔗
- ```Beginner picoMini 2022```
- ```General Skills```
- ```Python```

## Author ⭐
- LT 'SYREAL' JONES

## Description :book:
Find the flag in the Python script!

## Hints ❓
> 1. Try running the script and see what happens
> 2. In the webshell, try examining the script with a text editor like nano
> 3. To exit nano, press Ctrl and x and follow the on-screen prompts.
> 4. The str_xor function does not need to be reverse engineered for this challenge.

## Solutions 🎯
- Download the file from the Challenge.

  <details>
  
  <summary>File List 📁</summary>
  
  |FILE|DOWNLOAD FILE|VIEW FILE|
  |----|-------------|----------|
  |serpentine.py|[Download](https://artifacts.picoctf.net/c/93/serpentine.py)|[Click here](https://github.com/rhfnx/picoCTF/tree/main/Beginner%20picoMini%202022/Serpentine/serpentine.py)|
  
  </details>
  
- Run ```serpentine.py``` using ```$python3 serpentine.py``` command in your terminal.
- The ```b``` option doesn't show the flag and there's an order to check the source code let's check using cod editor.</br>
  ![Screenshot from 2022-11-04 21-04-03](https://user-images.githubusercontent.com/108726715/199993135-d7e3abc9-98e4-4c98-8292-ff436a4e06b8.png)</br>
- Now we can see on the bottom of code, in the 2nd ```elif``` the ```print_flag()``` doesn't called.</br>
  ![serpentine](https://user-images.githubusercontent.com/108726715/199996878-6c61c385-0fa4-4757-990b-42835bcdc8b0.png)</br>
- After adding the function let's try run it again.</br>
  ![serpentine2](https://user-images.githubusercontent.com/108726715/199997353-bb49e562-f41d-4dcc-a21d-109a80a09e40.png)</br>
- Now try run it again.</br>
  ![Screenshot from 2022-11-04 21-19-30](https://user-images.githubusercontent.com/108726715/199998359-ba4989f6-d2e6-4632-b9e9-1e056beb2c23.png)</br>
- The flag is ```picoCTF{7h3_r04d_l355_7r4v3l3d_ae0b80bd}```.
