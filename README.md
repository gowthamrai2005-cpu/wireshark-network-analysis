# Wireshark Network Capture and Analysis

## Objective
To capture and analyze live network packets and identify basic protocols and traffic types using Wireshark.

## Tools Used
- Wireshark (Ubuntu)
- Browser (for generating traffic)
- Terminal (for ping test)

## Steps Performed
1. Opened Wireshark and selected the active interface (`enp0s3`).
2. Started live packet capture.
3. Visited `https://example.com` to generate HTTP/DNS traffic.
4. Used `ping google.com` to generate ICMP packets.
5. Applied filters: `dns`, `tcp`, and `icmp` for analysis.
6. Stopped the capture and saved as `network_traffic.pcap`.

## Protocols Identified
| Protocol | Description |
|-----------|--------------|
| **DNS** | Converts domain names to IP addresses. |
| **TCP** | Handles reliable communication between devices. |
| **ICMP** | Used by ping to test connectivity. |

## Findings
- DNS queries were visible for example.com.
- TCP handshake packets appeared when the browser connected.
- ICMP packets confirmed network reachability.

## Outcome
Learned how to capture, filter, and analyze network traffic using Wireshark.
