# npc-statblocks

Program for parsing NPC statblocks from Pathfinder

You will need Rakudo Perl 6, and a fairly recent
version at that. If you have problems running the script
because of the version you have installed, try visiting:

https://perl6.org/downloads/

The CSS file in this directory is for the generated
HTML files.

You should be able to run this (assuming
you put your NPCs in a file called npc.txt):

    $ perl6 ./statblocks-cleaner.p6 npc.txt > npc.html

Now just open that npc.html file with your web browser
of choice and you should see something that's a
lot closer to well-formatted.
