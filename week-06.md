[<](README.md)

# Week 06 - DevLog

> Flash Raspberry Pi OS onto an SD card, SSH into your Pi, and set it up.


## Outcomes 

 


1\. Follow the [Command Line tutorial](https://omundy.github.io/learn-computing/slides/command-line.html). Watch [
Basic Terminal Usage](https://www.youtube.com/watch?v=jDINUSK7rXE). Describe in your own words what each of the following commands will do ✏️ 

```python
cd ~/
mkdir test && cd test
touch hello.py
echo "print(Hello World)" > hello.py
python hello.py
```

- `cd ~/` -> go to home folder; `mkdir test && cd test` -> create and enter `test`; `touch hello.py` -> create empty file; `echo "print('Hello World')" > hello.py` -> write one line to file; `python hello.py` -> run script.


2\. Share 3 differences between the Raspberry Pi and Raspberry Pi Pico ✏️

1. Raspberry Pi runs Linux, Pico runs MicroPython firmware.
2. Raspberry Pi is a full computer, Pico is a microcontroller.
3. Raspberry Pi is for general computing, Pico is for direct hardware control.


3\. Why shouldn't you power your Raspberry Pi from your computer USB? ✏️

- Laptop USB often cannot provide stable current, which can cause undervoltage, crashes, or SD card corruption.


4\. Of the ways to destroy a Raspberry Pi, which are you most likely to do? How will you keep from doing it? ✏️

- Most likely = wiring GPIO incorrectly or shorting pins; prevention: power off before rewiring and double-check pinout.


5\. Raspberry Pi OS is based on what Linux distribution? What does that even mean? ✏️

- Raspberry Pi OS is based on Debian Linux, meaning it uses Debian's Linux base, tools, and package ecosystem (`apt`).


6\. What does it mean to "Flash" your SD Card? ✏️

- Flashing means writing a full OS image onto the SD card so the Pi can boot from it.


7\. What does it mean if you see a red light and a flashing green light on your powered Raspberry Pi? ✏️

- It usually means the Pi has power (red) and is reading the SD card/booting (flashing green).


8\. What does a package manager do? ✏️

- A package manager installs, updates, and removes software while handling dependencies.


9\. Describe how you might use Git with a Raspberry Pi? ✏️

- Clone repos on the Pi, edit/run scripts over SSH, then commit and push changes to GitHub.


10\. What are two things your personal computer and a linux OS like Raspberry Pi have in common?

1. Both run an operating system and execute programs.
2. Both use files/folders, networking, and command-line tools.



## Other experiments

- 

## Questions to bring up in class

- 
