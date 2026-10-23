# Cisco Packet Tracer CLI — Documentation and Learning Guide

A technical guide for learning how to configure, verify, and troubleshoot Cisco network devices through the command-line interface (CLI) in Cisco Packet Tracer.

The manual is designed as a practical reference: it introduces IOS navigation, interface configuration, VLANs, DHCP, connectivity checks, troubleshooting, and common operational practices.

## Goals

- Build confidence navigating Cisco IOS-style command-line modes.
- Configure router interfaces and IPv4 addressing.
- Create VLANs and assign switch access ports.
- Configure a router as a DHCP server entirely through the CLI.
- Verify network behavior with `show` commands and `ping`.
- Practice systematic troubleshooting instead of relying only on the graphical interface.

## Topics covered

1. How to use the manual
2. Lab topology and IP addressing plan
3. IOS modes, navigation, and contextual help
4. Device discovery and verification commands
5. Router interfaces and IPv4 configuration
6. Switch VLANs and access ports
7. DHCP configuration from the router CLI
8. PC configuration and connectivity tests
9. Trunks and router-on-a-stick
10. Saving and removing configurations
11. Troubleshooting based on evidence
12. Best practices, quick reference, and exercises

## Example lab

The guide uses a small practice network with a router, a switch, three PCs, and an optional Server-PT device.

| Setting | Example |
| --- | --- |
| Client VLAN | VLAN 10 — CLIENTS |
| IPv4 subnet | `192.168.10.0/24` |
| Default gateway | `192.168.10.1` |
| Example DHCP range | `192.168.10.100–192.168.10.199` |
| Subnet mask | `255.255.255.0` |
| Example DNS server | `1.1.1.1` |

These values and interface names are examples. Confirm the ports and device capabilities in your own Packet Tracer topology.

## Getting started

1. Download or open `index.html` in a web browser.
2. Follow the table of contents in order, entering the commands in the Packet Tracer device CLI.
3. Verify each change with the suggested `show` commands.
4. Save your Packet Tracer project and device configurations after completing the lab.

## Important notes

- Packet Tracer implements a subset of Cisco device features. Supported commands vary by device model and Packet Tracer version; use `?` to inspect available syntax.
- The Server-PT DHCP service is configured through Packet Tracer's GUI. For CLI-only DHCP practice, the guide uses the Cisco router as the DHCP server.
- Avoid running two unplanned DHCP servers on the same VLAN, as they may offer conflicting network settings.
- This is an independent educational project and is not official Cisco documentation. Commands and behavior may differ on physical equipment.


## Disclaimer

This project is intended for learning and lab practice. Always review the current configuration and plan a rollback before making changes to production network devices.
