# Expected behaviour

The dashboard shows two correctly detected deps: https://github.com/Finkregh/renovate-ansible-test/issues/2 (`testbar v2022052401` and `testfoo v2022052401`).

* https://fink.ftp.sh/gitea/finkregh/tmp-ansible-role-testfoo/tags
* https://fink.ftp.sh/gitea/finkregh/tmp-ansible-role-testbar/tags

Both versions come from the git tags, have initially been correctly detected. In both repos newer tags have been created which should have been detected following https://github.com/Finkregh/renovate-ansible-test/blob/main/renovate.json#L10.

For both deps there should have been PRs for updates to the newer tags.

I do not see any logs/details.
