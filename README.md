# Watch2Upload
A tool to watch directories and backup its contents to a WebDAV server

## Description (draft)

Watch2Upload is a one-way sync client. It tracks changes inside a set
of directories and updates the corresponding remote directories
accordingly.

It supports multiple servers at the same time. Each watched
directory is associated with a remote server and a remote directory
inside that server.

For each watch directory there is a *delete* option. If the option is
set, then the contents of a directory will be deleted from the local
directory once they are upload to the remote directory.
