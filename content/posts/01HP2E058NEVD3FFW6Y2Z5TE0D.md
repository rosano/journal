---
date: 2024-02-07T18:41:34.485Z
years: 2024
months: 2024-02
days: 2024-02-07
categories: ["code"]
---
[Is there a better way to run a command N times in bash?](https://stackoverflow.com/questions/3737740/is-there-a-better-way-to-run-a-command-n-times-in-bash)

```
for run in $(seq $count); do
   git checkout HEAD@{1}
done
```
