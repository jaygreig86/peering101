============================
Finding Peer Information
============================

Before approaching potential peers it's a good idea to get a sense of how much traffic you're doing with the other network (if any) to asses whether a peering relationship makes sense.  Flow data will normally give you an idea of how much traffic you're doing to a particular Autonomous System.

Lets say you've taken a look and decided approaching network AS65000 makes sense, your next step is to find out more information on the ASN.  `PeeringDB <https://www.peeringdb.com>`_ is a good place to start which will provide some important details that you're going to need when creating a basis for a peering session between your network and the other party.  If you do not have your own entry within PeeringDB it's a good idea to get that setup before you start peering.

Some key information that you will find in PeeringDB records.

* IPv4 Prefixes 
* IPv6 Prefixes

These are useful for your max-prefix limits.

* IRR Record

This is needed when creating AS-PATH filters.  


