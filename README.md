# napalm-dellos6

NAPALM driver for Dell EMC Networking OS6 Operating System.

### Implemented APIs

* get_facts
* get_interfaces
* get_lldp_neighbors
* get_environment
* get_interfaces_counters
* get_lldp_neighbors_detail
* get_arp_table
* get_ntp_peers
* get_ntp_servers
* get_ntp_stats
* cli
* get_interfaces_ip

### Missing APIs

* load_template
* load_replace_candidate
* load_merge_candidate
* compare_config
* commit_config
* discard_config
* rollback
* get_bgp_neighbors
* get_bgp_config
* get_bgp_neighbors_detail
* get_mac_address_table
* get_route_to
* get_snmp_information
* get_probes_config
* get_probes_results
* ping
* traceroute
* get_users
* get_optics
* get_config
* get_network_instances
* get_firewall_policies
* get_ipv6_neighbors_table
* get_vlans
* compliance_report

This driver is in the early stages, and is a work in progress. Feel free to submit a PR to add additional getters or better implementations of existing getters.

