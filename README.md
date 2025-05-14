# zabbix-arista-bgp

This template is based on ARISTA-BGP4V2-MIB

Items
  - Arista BGP4v2 from SNMP

Discovery items
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) Admin State
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) EVPN Incomming Accepted Prefixes
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) EVPN Incoming Prefixes
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) EVPN Outgoing Prefixes
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) IPv4 Incomming Accepted Prefixes
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) IPv4 Incoming Prefixes
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) IPv4 Outgoing Prefixes
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) IPv6 Incomming Accepted Prefixes
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) IPv6 Incoming Prefixes
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) IPv6 Outgoing Prefixes
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) Peer State
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) Uptime

Triggers
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) is restarted
  - BGP Peer {#BGP_REMOTE_ADDR} ({#BGP_DESCRIPTION}) is down