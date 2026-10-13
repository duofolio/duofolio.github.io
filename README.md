# duofolio.github.io

Publishing configuration for [duofolio.github.io](https://duofolio.github.io/).

Website source remains in [duofolio/split_fiction](https://github.com/duofolio/split_fiction), under `personal-site/dist/`. Edit that repository, not this one.

The workflow reads the public `master` branch every 10 minutes and publishes only when its revision differs from `source-commit.txt` on the live site. GitHub may delay scheduled runs; use **Actions → Publish duofolio homepage → Run workflow** for an immediate update.

No cross-repository write keys or personal access tokens are stored. The workflow reads public source and uses this repository's built-in `GITHUB_TOKEN` to deploy its own Pages site.
Published website for duofolio/split_fiction. Source stays in split_fiction.
