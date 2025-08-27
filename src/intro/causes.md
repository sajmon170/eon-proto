# What's the main cause?
This centralized state is caused by many factors. The most prominent ones stem
primarily from core design decisions of the World Wide Web.

## Designed by programmers, for programmers
In an age where even basic filesystem structure knowledge has been abstracted
away by mobile operating systems one cannot assume that the end user is able to
set up a dedicated HTTP server on their own, much less acquire an open port and
a domain name.

## Designed for mainframes
The WWW was designed in a time when a mainframe server was necessary to do any
kind of non-trivial computations while the end users' terminals were delegated
to only downloading and previewing content. It was not designed with edge
computing in mind.

## Designed without mobile internet in mind
Today everyone is always connected, and the primary way of accessing the
internet are mobile phones.

## Designed for static content delivery
Dynamic content is a CGI-based hack on top of existing old HTTP infrastructure,
even though it forms the basis of current web interaction.
