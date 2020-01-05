Start/run Opencast behind a firewall
==============================

Opencast needs to download some dependencies at the inital startup or after updats. This is necessary for both install from source or from repo. When you opperate your Opencast system behind a firewall, you have to configure web access via a proxy-server.

All setting have to be done in your Opencast configuration directory (see [Basic Configuration](basic.md)).

1) Enable proxy w/o user

    org.ops4j.pax.mvn.

2) Proxy w/ user
