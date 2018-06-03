## My Stack Templates

Some templates I use for new Haskell projects.

I tend to start with [basic-prelude](https://www.stackage.org/lts/package/basic-prelude), a bunch of common-sense language extensions, `-Wall` and other recommended warnings.

Usage:
```
stack new projectname ~/dir/stack-templates/app.hsfiles
```

For more info see the [stack documentation](https://docs.haskellstack.org/en/stable/GUIDE/#stack-new).

For another approach to the same task, see [summoner](https://github.com/kowainik/summoner).

### app.hsfiles

For applications. In addition to `BasicPrelude`, it adds a couple dependencies that I always end up using: `text` and `safe` (for fixed versions of prelude functions like `headMay`, `tailSafe`, [Partial](https://www.stackage.org/haddock/lts-11.11/safe-0.3.17/Safe-Partial.html#t:Partial), etc.)
