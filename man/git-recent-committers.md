% git-recent-committers(1)

# NAME

git-recent-committers - show committers who made commits in the last N days

# SYNOPSIS

git recent-committers

# DESCRIPTION

Shows authors who made at least one commit in the last N days, together with the
number of commits they made in that period.

The default number of days can be controlled with the
`GIT_RECENT_COMMITTERS_DAYS` environment variable.

# EXAMPLES

`git recent-committers`

`GIT_RECENT_COMMITTERS_DAYS=30 git recent-committers`
