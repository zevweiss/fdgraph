fdgraph
=======

A simple python script that, given a starting PID, outputs a graph (in
GraphViz dot format) showing the files that process has open, as well
as other processes which may communicating with it via pipes and
sockets.

Suggested usage:

    $ fdgraph $PID | dot -Txlib

Different graphviz layout algorithms sometimes end up looking better,
sometimes worse.
