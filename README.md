# OverTheWire Bandit Write-ups

My notes while working through the [Bandit](https://overthewire.org/wargames/bandit/) wargame from OverTheWire to build Linux command line and security fundamentals.

Passwords are intentionally not included. Each write-up covers the goal, the commands used, and what I learned.

## Progress

| Level | Topic | Write-up |
|-------|-------|----------|
| 0 | SSH, `ls`, `cat` | [Level 0](levels/level-00.md) |
| 1 | File named `-` (leading dash) | [Level 1](levels/level-01.md) |
| 2 | Spaces and leading dashes in file names | [Level 2](levels/level-02.md) |
| 3 | Hidden files, `ls -a`, `cd` | [Level 3](levels/level-03.md) |

## Skills practiced so far

- Connecting to a remote server with SSH (custom port and username)
- Navigating and reading files with `ls`, `cd`, `cat` and `more`
- Handling special file names: `./` paths, escaping spaces with `\`, and quoting
- Finding hidden files (names starting with `.`) using `ls -a`

## Repo structure

```
Bandit-Series/
├── README.md
└── levels/
    ├── screenshots/
    ├── level-00.md
    ├── level-01.md
    ├── level-02.md
    └── level-03.md
```

## Note

These write-ups are for learning. Please try each level yourself first.