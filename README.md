[![Open in Dev Containers](https://img.shields.io/static/v1?label=Dev%20Containers&message=Open&color=blue&logo=visualstudiocode)](https://vscode.dev/redirect?url=vscode://ms-vscode-remote.remote-containers/cloneInVolume?url=https://github.com/hakumizuki/haskell-template)

# Haskell template
A Haskell devcontainer environment highly inspired by https://github.com/vzarytovskii/haskell-dev-env.


**Note**: This repository will be updated independently from the original repository, but in most cases, you may want to follow README.md from https://github.com/vzarytovskii/haskell-dev-env.

# How to use Warp as your terminal
[Warp](https://www.warp.dev/) is the modern terminal reimagined with AI.

Run the command below in your local environment.

```terminal
$ docker exec -it -w /workspaces/haskell-template haskell /bin/bash
```

**Note**: In this devcontainer, it is configured to automatically warpify when you start bash in the terminal.

# GHCi
If you just want to quickly try running Haskell, you can use [GHCi](https://downloads.haskell.org/ghc/latest/docs/users_guide/ghci.html).

```terminal
$ gchi
ghci> pythagoreanAnswers = [(a,b,c) | c <- [1..10], a <- [1..c], b <- [1..a], a^2 + b^2 == c^2]
ghci> pythagoreanAnswers
[(4,3,5),(8,6,10)]
```
