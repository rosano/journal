---
date: 2024-02-07T13:41:34.485-05:00
years: 2024
months: 2024-02
days: 2024-02-07
place: Toronto
country: Canada
categories: ["code"]
link: https://stackoverflow.com/questions/3737740/is-there-a-better-way-to-run-a-command-n-times-in-bash
---
[Is there a better way to run a command N times in bash?](https://stackoverflow.com/questions/3737740/is-there-a-better-way-to-run-a-command-n-times-in-bash)

```
count=10
for run in $(seq $count); do
   git checkout HEAD@{1}
done
```
