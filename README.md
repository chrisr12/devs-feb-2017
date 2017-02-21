### GitHub for Developers
- Trainer: Stefan Stölzle (@stoe)
- Local Contacts: 
 - Daniel Figucio (@affrae)
 - Sam Hunt (@samuelhunt)
 
 
### Scripts for Reset Activity 
**Bash:** 
```sh
for d in {1..6}; do touch "file${d}.md"; git add "file${d}.md"; git commit -m "adding file ${d}"; done
```

**PowerShell:** 
```sh
for ($d=1; $d -le 6; $d++) { touch file$d.md; git add file$d.md; git commit -m "adding file$d.md"; }
```


### Helpful Links
- [GitHub for Developers Manual](github-for-developers-student-manual.pdf)
- [Git SCM Website](https://git-scm.com)
- [GitHub Guides](https://guides.github.com)
- [GitHub Training](https://services.github.com/training/)
