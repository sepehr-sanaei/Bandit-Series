# OverTheWire Bandit level 0 Write-up
This is the first level in the Bandit series which is aimed for absolute beginners. Each level will acquire you with the information needed for the next level.

## Goal
Connect to the game server over ssh and obtain the password for bandit level 1.

## Step 1
We are required to ssh "bandit.labs.overthewire.org" on port "2220" , with user "bandit0" and password of "bandit0".
We can do this by issuing this command:
```bash
ssh bandit.labs.overthewire.org -l bandit0 -p 2220
```
Then we have to enter the password which is "bandit0"
![SSH login to bandit0](../screenshots/level0-1.png)

And we are in!

## Step 1
Now by using the "ls" list the files in the directory.
![List the files in bandit0](../screenshots/level0-2.png)

## Step 1
Finally we can view the contents of the readme file using
```bash
cat readme
```
![View the contents of readme file](../screenshots/level0-3.png)

## What I learned
- "-l" sets the username and "-p" sets the port in 'ssh'.
- "ls" can list the contents of a directory
- "cat" can depict the contents of a file

## Password for Level 1
`[redacted]`