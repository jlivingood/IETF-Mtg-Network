# Purpose of the IETF Meeting Network

IETF participants want a highly reliable and responsive network, with sufficient bandwidtht to avoid congestion, that enables work to be conducted without interuption or network limitation during an IETF meeting.

Such a network enables in-person network attendees to get their work done. It also enables remote participants to have a good experience as well, via remote participation in working group meetings.

## Key Requirements
- Highly reliable and performant network with no experiments to potentially cause disruptions.
- Support for network experiments via a separate Hackathon network.
- Redundant upstream connectivity to the internet.
- Native dual stack for all devices on the network - IPv4 and IPv6.
- Support for the most-recent IEEE Wi-Fi standard with ubiquitous Wi-Fi available in the meeting venue.
- Public ticketing system to report issues, as well as track/report status or closure.
- Public network performance dashboard and associated reports.

# Network Experiments
- Network experiments MUST only occur on the Hackathon Network, which is a separate network form the Meeting Network.
- The Hackathon Network will run for the entirety of the IETF meeting, not just during the Hackathon.
- Participants may use a public ticketing system (with support for up-voting to support prioritization) to request support for experimental new protocols or other experiments. 

# Extension of IETF Network to Hotels
- The IETF meeting network MUST NOT be extended to hotels any longer.
- Hotel networks are now sufficiently performant that this is no longer an issue.
- If there are potential issues with filtering, participants can use a VPN (as most do anyway).

# Wireless SSIDs
- There shall be only one SSID for the Meeting Network: IETF
- There shall be only one SSID for Network Experiments (unless a special SSID is required as part of an experiment): IETF-Hackathon
- The wireless network shall require authentication

# Real-Time Reporting
- All data concerning the performance of the network should be made available transparently for all participants to see.
- The Network Operations Center (NOC) shall provide a real-time or near-real-time dashboard of all key network statistics
- Reporting using IPFIX (NetFlow) that shows the source/destination of network flows
- Bandwidth tracking of peak usage
- Transport protocol tracking (e.g., volume of TCP, UDP, QUIC)
- Application protocol tracking (e.g., volume of SMTP, HTTP, etc.)
- DSCP mark tracking (e.g., volume by DSCP code point)
- ECN tracking (e.g., volume with no ECN, ECT(1), CE)
- All aspects of Wi-Fi performance (e.g., by room, specific AP, etc.)

# Post-Meeting Reporting
- Within 1 week of the shut down of the network a final network performance and incident(s) report shalll be sent to the community and posted on the IETF website.

# Geo-IP Data
- Shall be updated to the IETF meeting location within 1 week of the end of the prior IETF meeting, so that Geo-IP databases pick up the change of geography well before the next IETF meeting.

# Cost Management
- Total meeting network cost in 2024 was roughly $850,000. At 1,000 attendees per meeting and 3 meetings per year, 851,000/3,000 = $283 per participant for each meeting. If this 
cost was reduced, it could enable a material reduction in meeting registration fees.
- A key activity is to have an independent team study these costs and make recommendations on how to reduce them.

# Clarity on Roles and Responsibilities
- Lines of reporting may need to be clarified. 
- The NOC Lead contractor is responsible to regularly report to the IESG and IETF LLC concerning meeting network operations.
- The IESG shall establish an appropriate community oversight mechanism for the meeting network operations function (e.g., via GEN Area).
