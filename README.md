# PlanetOS - The OS from the stars 💫.

PlanetOS is a personal project built by me while in dreamer mode. I built PlanetOS to take on Windows(little me didn't know it was impossible).
It was written in over the course of a week and gave me practical hands-on experience of bare-metal programming AKA Assembly.

So far, I learnt Assembly solely for this projectand since I've dropped it, I dropped Assembly too.

## Screenshots
![welcome](/screenshots/home.png)

![desktop](/screenshots/desktop.png)

![hangman](/screenshots/hangman.png)

### Did you build this by yourself?
Yes I did, but its was built while following a tutorial on [OSDev](osdev.org) (can't remember the exact tutorial though).

### How do I build this to test?
Unfortunately, I did not find the Makefile (little me wasn't good at safegaurging stuff).
So unless you can reverse engineer a Makefile from it, you can't build it yourself.

### So how do I test it?
Fortunately, I found [a build](/releases/) I made, you can use any of those to test.

#### What you'll need?
- Qemu Emulator
- The img file of either version (check the `./releases` folder)

#### What next?
When Qemu is installed, clone this repo or download the version you want to test, then run

`"<folder where qemu was installed>/qemu-system-i386.exe" -fda "<any of the img builds you downloaded>"`

e.g
![command](/screenshots/cmd.png)
