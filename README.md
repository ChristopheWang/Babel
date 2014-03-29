Babel
=====
Babel Client in C++ with Qt Framework (4.7)

Epitech Project

Subject:

1. Goal

The goal is to create a SIP like VOIP((c) Bouba:-)) protocol. It will have to be usable over the Internet (no multicast or anything LAN specific).

To test your protocol you will write a server and a client implementation.

2.2 Requirements

2.1 Protocol

It has to be a client/server protocol but voice transport has to be client to client (the server can have a proxy mode for conference calls or natted clients). It has to be a binary protocol. Each group will HAVE to work with 1 or 2(max) other groups to have the same protocol. This is mandatory. Be careful! No code sharing. Everyone has to have its own client/server implementation. During the defense we will try to call the others. You will need to register in the same defense slot.

2.2 Platform

The project has to be OS independent. It has to run on at least one Linux/Unix system and one Windows system.

2.3 Languages

Only C++ is allowed. C and C+ will not be tolerated. You will loose a LOT of points.

2.4 Libraries

• You are NOT allowed to use a SIP or other VOIP library.

• You HAVE to use the portaudio library for sound (http://www.portaudio. com/).

• You HAVE to use speex for the compression codec (http://www.speex. org/).

• You HAVE to use QT (http://trolltech.com/) for the graphical interface.

• You are NOT allowed to use any QT library server side.

• You are allowed and encouraged to use BOOST C++ libraries (http: //www.boost.org). (optional)

• POCO C++ libraries (http://pocoproject.org/) are very cool but NOT allowed.

• For requests, send a mail to the author. The subject will be updated.

Tip: Have a look at BOOST Asio (http://www.boost.org/doc/libs/1_40_ 0/doc/html/boost_asio.html) for networking on the server. Portaudio and speex are C libraries. Do NOT use any c++ wrappers but create your own.
