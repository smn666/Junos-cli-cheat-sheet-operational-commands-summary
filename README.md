# Junos-cli-cheat-sheet-operational-commands-summary

Junos-cli-cheat-sheet-operational-commands-summary : 
---------------------------------------------------
----------------------------------------------------

Command 	Description


clear -------	:Clear statistics and protocol database information.

		Syntax: clear (arp | bgp | firewall | helper | igmp | ike | ilmi | interfaces | ipsec | ipv6 | isis | ldp | log | mpls |
		 msdp | multicast | ospf | pim | rip | ripng | route | rsvp | snmp | system | vrrp)


configure------	:Enter CLI configuration mode.

		Alternative commands: configure <exclusive> <private>


file------------:Perform file manipulation operations, such as copy, delete, list, rename, and show.

		Syntax: file (compare | copy | delete | list | rename | show)


help------------:Provide help information.

		Syntax: help (reference | syslog | topic)


monitor---------:Monitor a log file or interface traffic in real time.

		 Syntax: monitor (interface | list | start | stop | traffic)


mtrace----------:Display trace information about a multicast path from a source to a receiver.

		Syntax: mtrace (from-source | monitor | to-gateway)


ping------------:Verify IP connectivity to another IP host or Asynchronous Transfer Mode (ATM) connectivity (ping ATM) using Operation Administration and Maintenance (OAM) cells to an ATM endstation.

		Syntax: ping host <interface source-interface > <bypass-routing> <count requests > <do-not-fragment> <interval seconds > <pattern string > <record-route>

		<routing-instance routing-instance-name > <size bytes > <strict> <tos type-of-service > <ttl  value > <via route > <rapid | detail>

		Syntax: ping atm interface interface <count count > <end-to-end | segment> <interval interval> <sequence-number sequence-number > <vci vci > <brief>

		Syntax: ping vpn-interface vpn-interface host <local echo-address>	

pipe------------:Filter the output of an operational mode or configuration mode command.

		Syntax: | (compare | count | display <detail | inheritance | xml> | except pattern | find pattern | last lines | match pattern | no-more | resolve <file-names> | save filename | trim columns)

quit------------:Log out from the CLI process.

		 Syntax: quit

request---------:Make system-level requests, such as halt or reboot the router, load software packages, and back up the router’s file systems.

		Syntax: request system (halt | reboot | snapshot | software)

restart---------:Restart the router hardware or software processes.

		Syntax: restart (fpc | class-of-service | gracefully | immediately | interface-control | mib-process | network-access-service | remote-operations | routing | sampling | sfm | snmp | soft)

set--------------:Set CLI properties, the router’s date and time, and the craft interface display text.

		  Syntax: set (chassis | cli | date)

show-------------:how information about all aspects of the software, including interfaces and routing protocols.

		 Syntax: show (accounting | aps | arp | as-path | bgp | chassis | cli | configuration | connections | dvmrp | firewall | helper | host | igmp | ike | ilmi | interfaces | ipsec | ipv6 | isis |

		  l2circuit | l2vpn | ldp | link-management | log | mpls | msdp | multicast | ntp | ospf | pfe | pim |

		  policer | policy | rip | ripng | route | rsvp | sap | snmp | system | task | ted | version | vrrp)

ssh--------------:Open a secure shell to another host.

		 Syntax: ssh host <bypass-routing> <routing-instance routing-instance-name > <source address > <vpn-interface vpn-interface > <v1 | v2>

start------------:Start a software process.

		 Syntax: start shell

telnet-----------:Start a telnet session to another host.

		 Syntax: telnet host <8bit> <bypass-routing> <inet | inet6> <noresolve> <port port > <interface interface-name> 

		 <routing-instance routing-instance-name > <source address > <vpn-interface vpn-interface>

test-------------:Run various diagnostic debugging commands.

		 Syntax: test (configuration | interface | msdp | policy)

traceroute-------:Trace the route to a remote host.

		 Syntax: traceroute host <as-number-lookup> <bypass-routing> <gateway address > <inet | inet6> <noresolve>

		 <routing-instance routing-instance-name><source address > <tos value > <ttl value > <vpn-interface vpn-interface > <wait seconds>


	
