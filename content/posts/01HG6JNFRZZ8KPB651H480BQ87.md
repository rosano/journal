---
date: 2023-10-11T13:26:00.000Z
years: 2023
months: 2023-10
days: 2023-10-11
categories: ["code"]
---
[Cannot update due to one tiny app filling up 20GB drive](https://forum.cloudron.io/topic/8554/cannot-update-due-to-one-tiny-app-filling-up-20gb-drive/19)

Remove swap storage

```
sudo swapoff -a
# or
sudo swapoff /apps.swap

# if desired
truncate -s 1G /apps.swap

sudo rm /apps.swap
```
