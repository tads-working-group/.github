# The TADS 3 Community Working Group

## What is TADS 3?

TADS 3 is an open source (but not currently free software) parser interactive
fiction authoring system created by Michael J. Roberts in 2006, following TADS 2
and TADS 1, both of which served as the predominant interactive fiction
authoring systems of their times. TADS 3 is often considered to be one of the
main parser interactive fiction authoring systems, a list which variously
includes Inform 7/10, Inform 6, and Hugo depending on who you ask. Although
Inform 7 has long been dominant, and TADS 3 has a much smaller community of
authors, we believe it still has much to offer.

## What is parser interactive fiction?

Parser-based interactive fiction is a form of text-based game, a subgenre of
which is often called a "text adventure," wherein the player explores a
simulated world of multiple locations, interactive objects, conversant NPCs, and
so on, overcoming obstacles (usually of the puzzle variety) and experiencing
novel-like story through a primarily text-based interface, where the computer describes
the situation to the player, and the player uses a simplified subset of English
to describe what they want to do.

## What is the TADS 3 Community Working Group?

The TADS 3 Community Working Group is a (currently small) group of TADS 3
authors dedicated to ensuring that this historically important, extremely
powerful, and well-designed software tool continues to be accessible for new
authors in the future, and easy to use for authors today, through collecting,
curating, improving, and adding to the stable of tools and documentation
available for TADS. Since TADS was abandoned by its creator in 2013, it has
fallen to the community to keep up with this task and bring TADS with us into
the future, and this group formed in response to what was perceived as a vacuum
in the community, since nobody was focusing on collecting and curating TADS
documentation and it was beginning to be difficult to find and scattered.

## What are we doing right now?

### Near term

As of November 2023, we are currently in the process of building a modern
community-made landing page for TADS 3, which will explain its benefits,
history, and features, as well as how to install it, and collect all known TADS
3 documentation into a single central, searchable, uniform location on our
servers where we can protect any of it from going off the web. This
documentation will also be given a new modern coat of CSS and HTML paint,
extensively edited and reformatted and updated, and made uniform so as not to be
confusing.

We are also concurrently working on a unified TADS 3 launcher, which will allow
players to run both regular TADS games, HTML TADS games, and Web UI games within
a single self-contained, packaged, and cross-platform Qt application, thus
eliminating the confusion and barriers to entry for playing TADS 3 games.

We have recently finished providing a distro-agnostic self-contained Author's
Kit for Linux as well.

### Long term

Since we updated the QTADS interpreter to Qt 6.6 in order for it to work with
our launcher, we are also planning on using that fork to create a version of
QTADS that can run in the browser via WebAssembly, thereby creating an
equivalent to Parchment for TADS that is capable of displaying the full panoply
of HTML TADS's multimedia capabilities (unlike Parchment, which can only play
TADS games in essentially plaintext mode), which should lower the barrier to
entry for playing TADS 3 games even further, allowing them to be easily played
online via IFDB's Play Online button.
