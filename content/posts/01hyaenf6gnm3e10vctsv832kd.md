---
date: 2024-05-20T07:32:42.832+00:00
year: 2024
month: 2024-05
day: 2024-05-20
place: Wiesenburg (Mark)
country: Germany
categories: ["code"]
link: https://stackoverflow.com/questions/63770382/how-can-we-reduce-the-size-of-homebrew-cask-and-homebrew-core-folders/75484337#75484337
---
[How can we reduce the size of homebrew-cask and homebrew-core folders?](https://stackoverflow.com/questions/63770382/how-can-we-reduce-the-size-of-homebrew-cask-and-homebrew-core-folders/75484337#75484337)

> [As of Homebrew 4, you can save space by removing certain packages only used for developing formulae or casks:]

```bash
brew untap homebrew/core
brew untap homebrew/cask
```
