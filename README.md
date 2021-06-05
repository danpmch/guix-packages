# guix-packages
Custom package definitions for the GNU Guix package manager

## Using

To use these packages, add the repo as an additional channel to your guix
`~/.config/guix/channels.scm`:

    (cons (channel
        (name 'dan)
        (url "https://github.com/danpmch/guix-packages.git"))
      %default-channels)

