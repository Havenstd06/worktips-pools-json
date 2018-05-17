# worktips-pool-list

List of pools for worktips (http://worktips.info) mining.

This list can be consumed in your application so you'll always have an up-to-date list of pools. To consume the list, just use the following URL: https://raw.githubusercontent.com/Havenstd06/worktips-pools-json/master/worktips-pools.json

## Contributing

The goal of this repository is to have a central list of pools for Worktips. If you run a pool, please submit a Pull Request against *worktips-pools.json* to get added.

Please add your pool to the list in alphabetical order, named using CamelCase.domain style, and including trailing slashes for the `url` and `api` values.

**e.g.**
```
    {
        "name" : "MyPool.com",
        "url" : "https://wtip.mypool.com/",
        "api" : "https://wtip.mypool.com/api/",
        "type" : "forknote"
    },
```
