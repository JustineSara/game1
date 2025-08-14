# Game 1: Exploring

## Set up

I use the [Scittle 2d Gamedev Template][2dTemp].

I also use [Nix-shell] to manage the tools I need. In particuar `nodejs` which I need for the `nmp` command.

I use [cljs-josh] to have hot-reloading, which means you can change your program without losing the game-state. It is installed with:
```
npm install cljs-josh
```

And run with:
```
npx josh
```

[2dTemp]: https://github.com/chr15m/scittle-template-2d-game#
[Nix-shell]: https://cuddly-octo-palm-tree.com/posts/2021-12-19-tyska-nix-shell/
[cljs-josh]: https://github.com/chr15m/cljs-josh
