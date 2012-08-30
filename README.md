amonmq-plus
===========

AmonMQ daemon to be used with AmonPlus

usage
=====
Drop in on any amonplus installation and then send messages to it via ZMQ

caveats
=======

When setting the address to which the daemon binds - be sure to use a real IP address which exists on the system. For example, the public IP of AWS instance won't work.


