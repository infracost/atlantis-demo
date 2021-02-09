# Infracost Atlantis Demo

See [this pull-request for a demo](https://github.com/infracost/atlantis-demo/pull/2#issuecomment-776196455), expand the Show Output sections and scroll down to see the Infracost output.

The [Infracost Atlantis integration](https://github.com/infracost/infracost-atlantis) runs [Infracost](https://infracost.io) against the master/main branch and the pull request. It automatically adds a comment to the bottom of Atlantis' output showing the cost estimate difference (similar to `git diff`) if a percentage threshold is crossed.

See the [Infracost integrations](https://www.infracost.io/docs/integrations/) page for other integrations.
