% MFNERC Needs IPv6
% Theo Baschak
% Infrastructure Group

# Overview

*	The Internet is Critical to MFNERC daily operations.
*	The Looming Problem: IPv4 Exhaustion
*	Implications of IPv4 Exhaustion to MFNERC
*	IPv6: The solution
*	Risks Involved
*	What will deploying IPv6 cost?
*	Conclusion and Call for Action

# Internet Criticality

*	MFNERC is a Service Provider:
	*	School Information System
	*	Wapaskwa Virtual Collegiate
	*	MFNEDU.org email
	*	Video Conferencing services
*	Internet issues and outages now affect many internal and external staff, and students.
*	E-mail communications also very important to the organization.
	*	Example: Spam blacklisting noticed immmediately.

# IPv4 Exhaustion

*	IPv4 Exhaustion has been a topic for many years.
	*	Already a reality in Europe and Asian IP networks.
	*	ARIN hit 1x aggregate /8 left April 23.
	*	ARIN was at 2x /8 when we started BGP process in Sept 2013.
*	There will be a point very soon when no more IPv4 addresses are available.
	*	Expected to be 2014 or 2015.
*	IPv6 Planned, Tested, and Ready to roll much better place to be than caught with pants down
	*	Big Bang implementations risky and costly

# Org IP Needs

*	MFNERC has 1x /24 allocated to it from ARIN.
	*	256 IP addresses (minus subnetting overhead)
*	Currently using roughly 40 IP Addresses between Shaw, Commstream, and our BGP.
*	More IP Addresses will be needed for VC Units, and other new MFNERC Services.
	*	These all require Public IPs.

# Solution: IPv6

*	Base IPv6 specs defined in 1998, 15+ years ago now.
*	Much larger address space:
	*	IP version 4:
		*	32 bits
		*	ex: 206.220.195.237
		*	Smallest ARIN allocation: /24
		*	LAN Subnet Size: /24
	*	IP version 6:
		*	128 bits
		*	ex: 2604:4280:d00d:202:8d45:516d:c5e0:ec67
		*	Smallest ARIN allocation: /48
		*	Enough for 65536 /64 Networks
		*	LAN Subject Size: /64

# Risks

*	Risks of Inaction:
	*	Inability to connect to new IPv6 subscribers (students) and content
	*	Optics: Falling behind the curve
	*	Increased MFNERC network complexity with more NAT
*	Risks of Action:
	*	New unknown security risks with new unknown transport protocol
	*	Introducing new protocol to network
	*	v4/v6 feature parity not entirely there, some things won't be possible at this time

# Deployment Costs

*	Switches: IPv6 ready
*	BGP Routers: IPv6 ready
*	Firewalls: Cisco ASA: IPv6 ready, Watchguard: IPv6 ready
*	OSs:
	*	Windows 2008 R2: IPv6 ready
	*	Windows 2012: IPv6 ready
	*	Windows 7 SP1: IPv6 ready
	*	Windows 8: IPv6 ready
	*	Win XP: Being phased out rapidly within MFNERC already
*	PBX: NOT IPv6 ready
*	Phones: NOT IPv6 ready
*	Address Space: $500 one time to ARIN, $100/yr to maintain

# Conclusion

*	I strongly encourage MFNERC to pursue IPv6 in 2014.

*	Presentation source/download available at [github](https://github.com/tbaschak/ipv6-mfnerc)
