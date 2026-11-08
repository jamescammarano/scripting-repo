# scripting-repo
**Note:** Not in use until I finish some other projects.

A monolith attempt at making a repo for all the various one shot scripts that aren't part of proper projects.

## Intentions:
- Docs included for each script.
- Each branch relates to an issue that outlines the problem and contains proposal(s) for how to move forward
- Each PR has an issue
- Testing is included
- Logging is included in a consistent way across scripts.
- Each script implements clean up function, trap is used appropriately, and a dev mode flag exists to wipe all traces of the run besides logs.
- Flags not positional arguments
- `script --help` prints the docs similar to `man pkg`
