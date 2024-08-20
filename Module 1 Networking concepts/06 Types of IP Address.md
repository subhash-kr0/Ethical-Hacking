# Types of IP Addresses

## 1. Public IP Addresses
- **Visibility**: Accessible from the internet.
- **Usage**: Assigned by your Internet Service Provider (ISP) and used for communication between devices on the global internet.
- **Example**: The IP address your router gets from your ISP.

## 2. Private IP Addresses
- **Visibility**: Used within a private network and not accessible from the internet.
- **Usage**: Assigned to devices within a local network (e.g., home or office) to enable communication within that network.
- **Examples**: 
  - `192.168.0.1` (commonly used in home networks)
  - `10.0.0.1`
  - `172.16.0.1`

## 3. Static IP Addresses
- **Characteristics**: Permanently assigned to a device and does not change over time.
- **Usage**: Useful for servers, websites, or devices that need a constant IP address.
- **Example**: A web server with a static IP ensures that it can always be reached at the same address.

## 4. Dynamic IP Addresses
- **Characteristics**: Temporarily assigned to a device and can change over time.
- **Usage**: Commonly used by ISPs for most consumer devices. Allocated using DHCP (Dynamic Host Configuration Protocol).
- **Example**: The IP address assigned to your home router by your ISP, which may change periodically.

## 5. Loopback IP Addresses
- **Address**: `127.0.0.1`
- **Usage**: Used by a device to communicate with itself, primarily for testing and diagnostics.
- **Example**: Developers often use the loopback address to test network applications locally.

## 6. Reserved IP Addresses
- **Usage**: Reserved for special purposes and are not used for general communication on the internet.
- **Examples**: 
  - `0.0.0.0`: Represents a non-routable address, often used to signify the absence of an address.
  - `255.255.255.255`: Used for network broadcast messages.

## 7. Multicast IP Addresses
- **Range**: `224.0.0.0` to `239.255.255.255`
- **Usage**: Allows the delivery of packets to multiple destinations simultaneously. Used in streaming media and online gaming.
- **Example**: A video conference stream sent to multiple clients.

## 8. Anycast IP Addresses
- **Usage**: Assigned to multiple interfaces (usually servers), where the data is routed to the nearest or best destination as determined by the routing protocol.
- **Example**: Commonly used in global load balancing where requests are sent to the nearest data center.

## 9. Broadcast IP Addresses
- **Usage**: Used to send data to all possible destinations within a network segment.
- **Example**: In IPv4, the broadcast address for a subnet might look like `192.168.1.255`.

## Summary

- **Public IPs** are accessible from the internet, while **Private IPs** are confined to local networks.
- **Static IPs** remain constant, and **Dynamic IPs** can change over time.
- **Loopback IPs** are used for self-communication, **Reserved IPs** have special purposes, **Multicast IPs** support group communication, **Anycast IPs** optimize routing, and **Broadcast IPs** reach all devices on a network segment.
