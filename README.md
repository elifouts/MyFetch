![Light Beige Photo Collage Home Decor Blog Banner](https://github.com/user-attachments/assets/65aa8df8-985b-491c-ba76-e85d819152c6)

# About
A modular easy to use system fetch tool utilizing NerdFonts.
- Clean
- Simple
- Customizable
- Strong cross-OS compatability
- Not bloated
- Portable
- POSIX


> [!NOTE]
> This is Forked from NerdFetch to be more modular.
>
> You can Checkout NerdFetch here [Link](https://github.com/ThatOneCalculator/NerdFetch)

## Install

If you use Arch
```
yay -S myfetch
```
If you use basically anything else
```
git clone https://github.com/elifouts/MyFetch.git
cd MyFetch
makepkg -si
```
## Usage

These flags are available

```
Usage: myfetch [-i initials] [-d] [-f] [-c 8|16] [-C string] [-v] [-h]

  -i    Set custom Ascii initials (two letters)
  -d    Show Distro
  -f    Sets Ascii Font to Frame
  -c    Sets Color Pallete
  -C    Sets Color Pallete Icon
  -v    Show version
  -h    Show help

Made By Eli F.

```

### Examples

Simple
```
myfetch
```
![image](https://github.com/user-attachments/assets/bf8be407-8cb9-43f1-8667-a4854d9763a3)

You can print your initials in ascii
```
myfetch -i EF -c 8
```
![image](https://github.com/user-attachments/assets/6b442c10-dd10-4fe8-bc68-80c029c2ca57)

You can change the ASCII Font to frame
```
myfetch -i E -f -c 16
```
![image](https://github.com/user-attachments/assets/f95facce-5bb6-4527-ad86-a85b172580ca)

You can use your distro
```
myfetch -d
```
![image](https://github.com/user-attachments/assets/1b74742a-6875-4818-a9aa-68466b58e23e)

Uses Terminal Colors
```
myfetch -d -c 8 -C " █"
```
![image](https://github.com/user-attachments/assets/6cee28c8-32d7-4e3a-8f0f-76a9f6856b45)


See what `myfetch -a` does...
