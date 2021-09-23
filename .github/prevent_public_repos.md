# Configuration for Prevent-Public-Repos

# Turn on Monitor Mode. In this mode the repo visibility is not modified and only an Issue is created
monitorOnly: false

# Enables detection of repos that change visibility from private to public (not just newly created ones)
enablePrivateToPublic: true

# Issue Title when repo is privatized
privatizedIssueTitle: '[CRITICAL] Public Repositories are Disabled for this Org'

# Issue Body when repo is privatized
privatizedIssueBody: 'NOTE: Public Repos are disabled for this organization! Repository was automatically converted to a Private Repo. Please contact an admin to override.'

# Users/Groups that should be cc'ed on the issue. Should be users/groups separated by a space.
ccList: '@Data'

# Repos to  exclude in detection. Should be a List of Strings.
# excludeRepos: ['repo1', 'repo2']