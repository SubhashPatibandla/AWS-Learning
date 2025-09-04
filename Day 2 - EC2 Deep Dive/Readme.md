**What is EC2, Why EC2, Types of EC2, Regions, Availability Zones in AWS**

**What is EC2 ?**

EC2-- Elastic Compute Cloud

Compute -- CPU, RAM & DISK (Nothing but a Virtual Server)

**Why EC2 ?**

No Maintenance, No Timely upgrades required by Sys Admin, No Security Issues, Scalable & Pay as you go.

**Types of EC2 ?**

1. General Purpose 🖥️

Balanced compute, memory, and networking.

Good for web servers, development, testing.

Examples:

t3, t4g → burstable performance (cheap, good for small apps).

m5, m6i, m7g → balanced, steady workloads.

2. Compute Optimized ⚡

High performance for CPU-intensive tasks.

Good for gaming servers, high-performance computing, batch processing.

Examples:

c5, c6i, c7g.

3. Memory Optimized 🧠

Designed for memory-heavy applications.

Good for databases, caching, big data analytics.

Examples:

r5, r6i, x1e, z1d.

4. Storage Optimized 💾

High disk throughput and IOPS.

Best for NoSQL databases, data warehousing, search engines (like Elasticsearch).

Examples:

i3, i4i → high IOPS SSDs.

d2, d3 → dense storage (HDD).

5. Accelerated Computing 🚀

Special hardware like GPUs or FPGAs.

Best for AI/ML, graphics rendering, scientific computing.

Examples:

p3, p4 → GPU for ML/AI.

g4, g5 → graphics.

f1 → FPGA.

**🔹 Instance Size**

Each family has sizes like:

t3.micro, t3.small, t3.medium, t3.large …

The bigger the size → more vCPUs, memory, network speed.

Example:
m5.large = 2 vCPUs, 8 GB RAM.
m5.2xlarge = 8 vCPUs, 32 GB RAM.

**Regions & AZ's in AWS :**

A Region is a geographical area in the world where AWS has data centers.

Example regions:

us-east-1 → N. Virginia (USA)

ap-south-1 → Mumbai (India)

Inside each region, there are multiple Availability Zones (AZs). An AZ = one or more data centers with independent power, cooling, and networking.

Each AZ is isolated, but they are connected with low-latency, high-speed fiber links.

Mumbai Region (ap-south-1) has 3 AZs:

ap-south-1a

ap-south-1b

ap-south-1c
