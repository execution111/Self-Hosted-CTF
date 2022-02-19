<h1 align="center">
	<img src="https://i.postimg.cc/KjLpyw0H/flag-removebg-preview.png" width="150px"><br>
    Self Hosted CTF - A fun Capture The Flag-like game for beginners to enchance their web request skills!
</h1>
<p align="center">
    Note: Please only open the "Answer" directory if you have completed the challenge!
</p>

**Install**

```
git clone https://github.com/execution/Self-Hosted-CTF.git

```
```
cd Self-Hosted-CTF
```
```py
python start.py
```

<h1></h1>

**Code Example**

```python
from C0mptCrypt import C0mptCrypt

string = input("Enter string: ")

enc = C0mptCrypt().Encrypt(string)

print(enc)
```

```python
from C0mptCrypt import C0mptCrypt

string = input("Enter encrypted string: ")

enc = C0mptCrypt().Decrypt(string)

print(enc)
```
