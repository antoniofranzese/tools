# Shell Tools
Command line utilities and wrappers

## Base installation
The tools folder must be placed in PATH **before** the system /bin and /usr/bin.

## Environment configuration
Some tools are *wrappers* for the original executable, and must be configured with the **absolute path** of their counterpart; if not configured, they assume a default suitable only for a standard Linux/WSL environment (MacOS requires configuration).

Place the needed variables in your .zshrc/.bashrc script, every path **MUST** be absolute.

| Variable           | Default value    |
| ------------------ | ---------------- |
| KUBECTL_EXECUTABLE | /usr/bin/kubectl |
| SVN_EXECUTABLE     | /usr/bin/svn     |
