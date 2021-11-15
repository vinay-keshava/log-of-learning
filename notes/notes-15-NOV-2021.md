# 15-NOV-2021

### 1 - Pass Command


- Pass - the unix command password manager to store and manage passwords.
  - Before storing the password GPG(GNU Privacy Guard)keys has to be generated
  - "$gpg --full-generate-key" follow the instructions and generate a key phrase for the password manager.
  - gpg --list-secret-keys --keyid-format LONG the output from the sec branch is copied
  - $pass init "---keysss---"
  - $pass insert example.com
  - Reference Video - https://www.youtube.com/watch?v=hlRQTj1D9LA


```python
	print("Pass Unix command")

```
