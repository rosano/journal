---
date: 2024-02-07T18:31:42.596Z
years: 2024
months: 2024-02
days: 2024-02-07
place: Toronto
country: Canada
localtime: 2024-02-07T13:31:42.596-05:00
categories: ["code"]
link: https://stackoverflow.com/questions/43197105/how-do-you-jump-to-the-first-commit-in-git
---
[How do you jump to the first commit in git?](https://stackoverflow.com/questions/43197105/how-do-you-jump-to-the-first-commit-in-git)

```
git checkout `git rev-list --max-parents=0 HEAD | tail -n 1`
```
