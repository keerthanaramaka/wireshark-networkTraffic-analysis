# Wireshark Network Traffic Analysis Report
**Summary:**
Captured live traffic for ~1 minute while browsing websites and using ping.

**Protocols Identified:**

1. **DNS**
   - Resolves domain names.
   - Port 53.
   - Example packet: Standard query for google.com.

2. **TCP**
   - Transport-layer traffic.
   - Seen for HTTP/HTTPS (ports 80/443).

3. **ICMP**
   - Used for ping (echo request/reply).

**Key Observations:**

- DNS queries are visible in clear text.
- HTTPS traffic is encrypted (only handshake is visible).
- ICMP packets show connectivity testing.

**Outcome:**
Gained experience with:
- Capturing live packets.
- Using Wireshark filters.
- Identifying protocol types in real traffic.
