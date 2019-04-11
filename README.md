# Semantic versioning git hook

Hook for increase semantic version of release (git tag) like [semver.org](https://semver.org/)

Hook is trigger when you execute ``git merge`` on production branch (in this case ``stable``)

You can increase with hook:

1) MAJOR version
1) MINOR version
1) PATCH version

## How it use?

* You can copy hook into your repo ``your-repo-dir/.githooks/post-merge`` and add local configuration for git ``git config --local core.hooksPath .githooks/``
* You can copy hook into git dir in repo ``your-repo-dir/.git/hooks/post-merge`` and that's all
