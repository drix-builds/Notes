Topics:
- [ ] What is networking
- [ ] OSI model
- [ ] Life of a packet


## What is Networking?
goals: 
1. high level explanation of how a network works
2. how they will interact with the network as techs
3. fast examples of network issues and underlying causes we dive into
4. transistion into OSI model

## OSI model
1. 7 layer osi model
	1. Application 
		1. Where humans and computers interact, applications access network services
		2. Web browsers and email clients rely on this layer to initiante communications
		3. Client software programs are not part of the application layer in their entirety 
		4. Protocols: HTTP,DNS,SMTP
	2. Presentation 
		1.  Prepares  dataso that it is in a usable format for the application layer and is where data encryption occurs
	3. Session
		1. Maintians connections and is responsible for controlling ports and sessions
		2. layer 6 is responsible for adding the encryption on the sender's end as well as decoding the encryption
	4. Transport
		1. Transmits data using transmission protocols including TCP and UDP
	5. Network
		1. Decides which phusical path the daya will take
	6. Datalink
		1. Layer 2
		2. The "Local Network" Layer
		3. provides hop-to-hop delivery of messages tthrough a local network
			1. "hop" - one step along the bath between 2 devices
		4. MAC and LLC (Physical Addressing)
		5. 
	7. Physical 
		1. Layer 1
		2. Transmits raw bits over the physucal medium
		3. Cabels, NICS, radios, and antennas
		4. common failures:
			1. not plugged in
			2. faulty cabling
			3. exposed copper 

Sources: 
- [Cloudflare: What is the OSI Model?](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)