# BACKEND ENGINEERING

### I - Communication protocols

	What is communication protocols ?
	⇒ A communication protocol is a system of rules that allows two or more entities of a communication system to transmit information via any kind of variation of a physical quantity.

	The protocol defines the rules , the syntax , the synchronization , semantics , communication and possible error recovery methods. 

	For anologie communication protocole is like programming language for computation
	or for another analogy communication protocol is like algorithms for computation 

	Multipl protocols often describe differents aspects of a single communication.

	Internet protocols are published by the Internet Engineering Task Force (IETF).

	Some of best protocols-suite : 
	TCP/IP, IPX/SPX, X.25, AX.25 and AppleTalk

### A / Types of protocols

	We are two type of protocols : 
	Text Based Protocols and Binary Protocol
	
	| Text Based Protcol | 
	It's a protocol more readable for humain.
	the text based representation trensmits request and response as line of ASCII text. 
	We can find : FTP (File Transfert Protocol), SMTP (Simple Mail Transfert Protocol), the Finger Protocol

	| Binary protocol |
	A binary protocol utilizes all values of a byte.
	Binary protocols are intended to read a machine rather than a human.
	Binary protocol have been use in the normative documents describing modern standards like HTTP/2, HTTP/3 ,EbXML, EDOC and an interface in UML

### B / Basic requirement of protocol

	Getting the data accross a network is only the problem for a protocol.

	Message are sent and received on communicating systems to etablish communication. 
	Protocols should therefore specify rules governing the transmission.
	In general, much of the following should be addressed : 
	- Data formats for data exchange
	Digital message bitstring are exchanged. 
	the bitstring divided in fields and each fields carries information relevant protocol. 
	the bitstring is divided into two parts called the Header and the Payload.
	the actual message is carried in the *payload.
	the header area contains the fields with relevance to the operation protocol.

	- Address formats for data exchange 
	 Addresses are used to identify both the sender and the intended receiver(s).
	 The addreses are carried in the header area of the bitstring, allowing the receivers to determine weather the bitstrings are of interest and should be processed or should be ingored

	 - Address mapping
	 Sometimes protocols need to map addresses of one scheme on addresses of another scheme.
	 For instance to translate a logical IP address specified by the application to an Ethernet MAC address.

	 - Routing
	 
