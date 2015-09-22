These are a couple tools that I often fallback to when I have issues with
quoting or other command line type issues.

args prints all of its command line arguments, one per line, so you can see
how the shell divvied things up.

args-env is similar, but it also prints all of the environment variables.

This particular project is setup for building a standalone executable under
Android. For non-android uses, just compile args.c using gcc.
