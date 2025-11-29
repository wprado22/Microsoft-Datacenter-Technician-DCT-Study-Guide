# Microsoft-Datacenter-Technician-DCT-Study-Guide
A complete reference of all key concepts, definitions, and differences you must know to be interview-ready and job-ready for a Microsoft Datacenter Technician role.
Table of Contents

Hardware Fundamentals

Servers & Components

Hardware Replacement & Hands-On Skills

Networking Basics

Datacenter Operations

Microsoft-Specific Knowledge

Version History

Hardware Fundamentals (Top Priority)
Servers & Components — Key Terms & Definitions

Term	Definition

Server - A powerful computer that processes data and provides services to other computers.

Motherboard - The main board that connects CPU, RAM, storage, NICs, and other components.

CPU (Central Processing Unit) -	The brain of the server that executes instructions.

GPU (Graphics Processing Unit) - Processes graphical or parallel workloads (AI, ML, rendering).

RAM (Random Access Memory) - Volatile short-term memory that stores active data for quick access.

NIC (Network Interface Card) - The component that connects a server to the network.

RAID - Controller	Manages multiple drives for redundancy or performance (RAID 0/1/5/10).

HDD (Hard Disk Drive) - Mechanical spinning storage — slower but high capacity.

SSD (Solid State Drive) - Flash-based storage — faster, durable, and modern standard.

Hot-Swappable Components - Hardware that can be replaced without shutting down the server.

Blade Server - Thin modular servers that share power/cooling inside a chassis.

Rack Server - Independent servers mounted in standard 19-inch racks.

Differences You Must Know
Comparison	Explanation

HDD vs SSD	HDD = mechanical, slower, cheaper. SSD = faster, no moving parts, better performance.

Blade vs Rack Server	Blade = dense, shared chassis. Rack = standalone and easier per-server management.
 Hands-On Hardware Skills to Practice

Replace RAM

Replace PSU (power supply)

Replace drives (HDD/SSD)

Recable a server with proper routing

Label cables on both ends (critical in DCs)

Networking Basics

Key Networking Terms
Term	Definition

IP Address	Unique network identifier for a device (IPv4/IPv6).

VLAN	Virtual segmentation within a network for security/traffic control.

Switch	Connects devices within the same network (Layer 2).

Router	Connects different networks and routes traffic between them (Layer 3).

Fiber Optic Cable	Uses light for ultra-fast, long-distance data transmission.

Copper Cable	Electrical cable (Cat5/6/7) used for short-distance connections.

LC Connector	Small, modern fiber connector commonly used in DCs.

SC Connector	Older, larger fiber connector.

OSI Model	7-layer model describing network communication.

Ping	Connectivity test using ICMP echo requests.

Traceroute	Shows the path packets take across the network.

Differences You Must Know
Comparison	Explanation

Switch vs Router	Switch = devices in one network. Router = connects multiple networks.

Fiber vs Copper	Fiber = faster & long distance. Copper = cheaper & short distance.

LC vs SC	LC = smaller, modern. SC = larger, older.

Data Center Operations

Operational Concepts
Term	Definition

Ticketing System	Tracks incidents, tasks, changes (ServiceNow, Jira).

SLA (Service Level Agreement)	Defines expected response times and service quality.

Incident Response	Process followed when an issue or alert occurs.

Rack Elevation Diagram	Visual map of server placement in a rack.

Power: Amps / Volts / Breakers / PDUs	Electrical fundamentals required for safe equipment operation.

Hot Aisle vs Cold Aisle	Cooling strategy to optimize airflow.

Inventory Control	Tracking hardware parts and replacement cycles.

Differences You Must Know
Comparison	Explanation

Hot Aisle vs Cold Aisle.	Cold aisle = intake (cool). Hot aisle = exhaust (warm).

Microsoft-Specific Focus

Microsoft & Cloud Knowledge
Term	Definition

Azure Basics	Understanding VMs, VNets, storage, regions, scaling.

Microsoft Datacenter Safety Training	Safety procedures: PPE, electrical safety, hazard controls, emergency protocol.

Cloud Region - is a geographic area where Microsoft builds and operates multiple datacenters.

Availability Zone (AZ) - Isolated datacenter within a region for redundancy.

Difference to Know
Comparison	Explanation

Region vs Availability Zone	Region = geographic area (e.g., East US). AZ = isolated physical datacenters inside a region.


