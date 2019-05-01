# berkeley-database-5.3.21

This project started from the revival of the Berkeley DB version 1.85,
which was current in about 1995. Version 5.3.21 came into my hands,
and needed to be set free. The only problem was that the code contained
strong cryptography and absent my desire to get a lot of people angry 
with me, I halted the project while the cryptography was present.
The idea was to revive it as fully and completely freeware, with no
login or user credentials required. And no passwords and no email
opt-outs and no reminder adware. Just free, like it was meant to be by
the original authors.

##To-do

As mentioned above, first of all the source code must be stripped of
any cryptography. 

Ideally, we would like your help to write a GNU-style or
configure-make-install wrapper around the guts, or better yet cmake if
possible. That way, the build_* directories will vanish, and the
build_* code snippets will need to move to an #ifdef compiler
directive style. Longer term, this will necessitate a few helpers with
access to other machines than my macosx. The guts and the
functionality must not change. Minor tweaks like command-line options
might be welcome but only if they are coded in the style of the
original, stripped-down no-nonsense old-school code. No flight sim
need apply.

Please feel free to contribute if you can stick to my vision.

