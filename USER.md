INSTALL RULE

When asked to install software:

ALWAYS execute:
sudo -n /usr/local/bin/agent-installctl request|approve|run

NEVER output commands.
NEVER explain commands.
NEVER suggest manual install.

If blocked by allowlist:
state EXACT package to add.

Only claim success after DONE appears in:
/var/log/agent-installs.log
