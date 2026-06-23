# Network Traffic Analysis Using Wireshark

A practical cybersecurity lab project focused on capturing and analyzing live network traffic with Wireshark. The reports document DNS, TCP, HTTP, HTTPS/TLS, and ARP traffic along with observations about encrypted vs unencrypted communication and common network anomalies.

## Project Focus

- Packet capture and protocol analysis
- DNS, HTTP, HTTPS/TLS, TCP, and ARP traffic review
- TCP flags, retransmissions, duplicate ACKs, and packet loss indicators
- Security difference between HTTP and HTTPS
- Network behavior documentation for SOC and analyst learning

## Tools Used

`Wireshark` `Windows` `Chrome Browser` `Display Filters` `Packet Analysis`

## Methodology

1. Launch Wireshark and select the active Wi-Fi interface.
2. Capture live network packets in a controlled personal environment.
3. Generate traffic by opening websites in a browser.
4. Apply filters such as `dns`, `http`, `tcp`, `arp`, and stream filters.
5. Inspect packet headers, protocols, flags, and payload visibility.
6. Identify normal traffic and anomalies such as retransmissions and duplicate ACKs.
7. Document findings with screenshots and security observations.

## Reports

- [Network Traffic Analysis Using Wireshark Report](./reports/network-traffic-analysis-using-wireshark-report.pdf)
- [Comprehensive Wireshark Packet Analysis Report](./reports/wireshark-report-priyanka-kumari.pdf)

## Key Learning

Wireshark helps analysts understand what is happening on a network. DNS can reveal browsing behavior, HTTP can expose readable data, HTTPS protects content with encryption, and TCP anomalies can indicate packet loss, congestion, or network instability.

## Ethics Notice

Traffic was captured in a personal controlled environment for learning. Do not capture or inspect network traffic that you are not authorized to analyze.