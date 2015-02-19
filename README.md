# xie

Gentoo eix with dmenu and history

## usage

Just call `xie searchstring` to search for packets containing searchstring. If
there is more than one matching packet, you will get a dmenu prompt asking you
for the exact packet category/name. Only the selected packets entry will be
printed out by eix then.

If you happen to search for e.g. `tor` regularly and hate to input the category,
the history function is your rescue. After you first selected the `net-misc/tor`
packet, it will be remembered in `~/.xie_history` and the next time you search
for `tor`, it will appear right at the top of the dmenu list, so you just need
to confirm by pressing return instead of scrolling down all the way to
`net-misc`.

## license

See file LICENSE
