# ssh-io
Dedicated SSH service over low-level IO streams

## Purpose
Create a dedicated SSH service listening on stdio, serial lines, or compatible tty interfaces that supports standard multi-session ssh functionality.

Because why not - and I have found a need.

## Initial work
Attempt to get [libssh](https://www.libssh.org/) working (as-is) without a patch by bringing a file descriptor along for the ride
