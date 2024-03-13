 ## Computing: 
- Computation: The process of performing calculations and operations on a computer to process data and perform tasks.
- Storage: The capability to store and retain data, files, and information on computer systems, either locally or in the cloud.
- Network: A collection of interconnected devices that can share resources and communicate, including LANs (Local Area Networks) and WANs (Wide Area Networks).
- Distributed Computing: A distributed system is a system whose components are located on different networked computers, which communicate and coordinate their actions by passing messages to one another
- Computability is the ability to solve a problem in an effective manner.
- In computer organisation, the memory hierarchy separates computer storage into a hierarchy based on response time.
- The BIOS (Basic Input/Output System) is firmware in a computer that initializes and manages hardware components during startup. It provides essential instructions for the operating system to take over and is responsible for tasks like booting the computer and configuring hardware settings.
- In computing, a device driver is a computer program that operates or controls a particular type of device that is attached to a computer or automaton.
- Abstraction layer - Simplified interface or set of functions that hide complex underlying details, allowing for easier interaction with a system or software component.
  - A low-level abstraction layer in computing provides a basic and minimal interface to interact with hardware or software components, exposing more of the underlying details and requiring a deeper understanding of the system.
- Peripheral is an auxiliary hardware device used to transfer information into and out of a computer.
- CPU (Central Processing Unit): The primary hardware component responsible for executing instructions and performing calculations in a computer.
- GPU (Graphics Processing Unit): A specialized hardware component optimized for rendering graphics and handling parallel processing tasks.
- DPU (Data Processing Unit): Hardware designed for accelerating data processing tasks, including data compression and encryption.
- TPU (Tensor Processing Unit): A specialized hardware unit for accelerating machine learning and neural network computations.
- A microcontroller contains one or more CPUs (processor cores) along with memory and programmable input/output peripherals

## Computer Architectures: 
- CISC (Complex Instruction Set Computer): A computer architecture with a diverse and extensive set of instructions, which can make it more versatile but sometimes less efficient.
- RISC (Reduced Instruction Set Computer): A computer architecture that uses a simplified and optimized set of instructions to improve performance.
- RISC-V (Open Source RISC Variant): An open-source RISC architecture, allowing for customization and flexibility.
- Embedded Systems: Computer systems integrated into devices or machines for dedicated functions, such as IoT devices and industrial controllers.
- Firmware: Firmware is like the DNA of a device. It's software permanently programmed into hardware, like the instructions for your TV remote.


## Kernel and Operating Systems: 
- Kernel: The core component of an operating system that manages hardware resources and enables communication between software applications and hardware.
- A monolithic kernel is an operating system architecture where the entire operating system is working in kernel space.
- Operating Systems: Software that manages computer hardware, provides user interfaces, and supports running applications and processes.
- A microkernel is an operating system architecture where core services like process management and communication are kept minimal, with other functions implemented as separate modules or user-level processes. This design promotes modularity and reduces the risk of system failures affecting the entire OS.

## Linux: 
- Debian and RHEL Linux Families: Two popular Linux distributions, with Debian known for its open-source approach and RHEL (Red Hat Enterprise Linux) for its enterprise support.
- Package Manager (Yum): A package management tool used in RHEL-based distributions to install, update, and manage software packages.
- IBM's Ownership of Red Hat: IBM's acquisition of Red Hat, a significant move in the open-source and enterprise software space.
- Cgroups: Cgroups are like fences for processes. They help manage and limit resources (like CPU and memory) for running processes in a Linux system.
- The Linux Foundation aims to bring together open source software professionals, developers, sysadmins, and students to advance important community and industry initiatives that increase diversity in tech and access to new technologies.

## Virtualization: 
- Bare Metal Servers: Physical servers that run directly on hardware without an underlying host operating system.
- Dual Boot Systems: Computers capable of running two different operating systems and allowing users to choose which one to use.
- Hypervisors (Type-1 and Type-2): Software or hardware that enables the creation and management of virtual machines (VMs), with Type-1 running directly on hardware and Type-2 running on an existing operating system.
- VMware: A leading provider of virtualization and cloud computing software solutions.
- KVM: KVM is like a virtual theater for computers. It's a virtualization solution for running multiple operating systems on a single host.
- Xen: Xen is like an usher at a theater, directing performances (virtual machines). It's an open-source hypervisor for virtualization.
- Libvert: Libvirt is a collection of software that provides a common API (Application Programming Interface) for managing popular virtualization solutions :-
  - KVM                                                   
  - Xen
  - ESX
  - LXC

   ![300px-Libvirt_support svg](https://github.com/meharbhamrah/CSKeywords/assets/143251459/499e056f-1272-451f-875a-f0ffdd7e511f)

  - Bare-Metal Hypervisor: A hypervisor installed directly on the hardware without the need for an underlying operating system. Example: Citrix XenServer.
  - Virtual Network: Creating virtualized network configurations to isolate and secure resources. Example: Setting up virtual networks in OpenStack.
  - Virtual Storage: Using virtualized storage devices for managing and accessing data. Example: Mapping a virtual hard drive to a VM.
  - Snapshot: A point-in-time copy of a virtual machine or storage, useful for backup or recovery. Example: Taking a snapshot of a VM before making changes.
  - Live Migration: Moving a running virtual machine from one physical host to another without service interruption. Example: VMware vMotion.
  - Resource Allocation and Overcommitment: Allocating more virtual resources (CPU, RAM) than the physical host has. Example: Assigning 8GB of RAM to multiple VMs on a host with 16GB of physical RAM.
  - Virtual Desktop Infrastructure (VDI): Delivering desktop environments to users as virtual instances. Example: Citrix Virtual Apps and Desktops.
  - Virtual Appliances: Preconfigured virtual machines designed for specific purposes. Example: A virtual firewall appliance.
  - Host OS and Guest OS: The underlying operating system (host) and the operating system running in a virtual machine (guest).
  - Virtualization Clustering: Grouping multiple servers to work together for high availability and load balancing. Example: Microsoft Failover Clustering.
  - VMware vSphere: A suite of virtualization products for creating and managing virtualized data centers.
  - Virtualization Backup and Recovery: Creating backups of virtualized environments and recovering from failures.
  - Paravirtualization: A virtualization technique where the guest OS is aware of the virtualization and optimized for it.
  - VM Sprawl: The uncontrolled growth of virtual machines, leading to inefficiency and management challenges.
  - Nested Virtualization: Running virtual machines within virtual machines, useful for testing and development environments.

## Cloud Computing Providers: 
- AWS (Amazon Web Services): A prominent cloud computing provider offering a wide range of cloud services, including computing, storage, and more.
- Azure (Microsoft): Microsoft's cloud platform offering infrastructure, platform, and software services for cloud-based solutions.
- GCP (Google Cloud Platform): Google's cloud computing platform, providing cloud services and solutions for various applications and industries.

## Security: 
- GDPR (General Data Protection Regulation): European regulations governing data protection and privacy, with strict requirements for handling personal data.
- HTTPS (HTTP Secure): A secure version of the HTTP protocol that encrypts data exchanged between a web browser and a web server.
- SSL (Secure Socket Layer) and TLS (Transport Layer Security): Protocols that secure communication by encrypting data between two endpoints.
- Cryptography and Post-Cryptography: The science and techniques of secure communication and data protection, both during transmission and while stored.
- TLS (Transport Layer Security): Think of TLS as a secret handshake for your data. It encrypts and secures information sent between your web browser and a website, keeping it private.
- IAM (Identity and Access Management): IAM is like a bouncer at a club. It decides who can enter and what they can do. In the digital world, it controls who can access what in a system.
- Homomorphic Encryption: Homomorphic encryption is like a locked safe that you can perform operations on even without unlocking it. It's a way to process encrypted data while it remains secure.
- SSO - Single Sign-On: SSO is like having a master key to multiple doors. With one login, you can access different systems and applications without entering your credentials every time.
- DID - Digital Identity: DID is like a digital ID card that you carry online. It's a way to securely prove who you are in the digital world.
- Zero Knowledge: Zero knowledge is like proving you have the answer without revealing the answer itself. It's a cryptographic technique for secure authentication.
- Firewall: A network security device or software that filters and controls incoming and outgoing network traffic to protect a network from unauthorized access and threats.
- Encryption at Rest - refers to the encryption applied to the stored data.
- Encryption in Transit - refers to encrypting data that is transferred between two nodes of the network.
- End-to-End Encryption - refers to the combination of the encryption at rest and encryption in transit.

## Computer Architecture: 
- Von Neumann vs. Harvard Architecture: Two distinct computer architectural models, with Von Neumann using a unified memory space for data and instructions and Harvard using separate memory spaces for instructions and data.
- FPGA (Field-Programmable Gate Array): Hardware that can be configured and reconfigured for specific tasks, often used in custom computing solutions.
- ASICs (Application-Specific Integrated Circuits): Custom-designed integrated circuits optimized for specific functions or applications.

## Programming: 
- Object-Oriented Programming (OOP): A programming paradigm based on the concept of objects, encapsulation, inheritance, and polymorphism to create modular and maintainable code.
- IDE (Integrated Development Environment): Software that provides a comprehensive environment for coding, debugging, and managing software projects.
- C, C++, Rust: Programming languages used for various applications, with C and C++ known for system-level programming and Rust for safe and concurrent programming.
- Rust: Rust is like a new kind of tool in a toolbox. It's a modern programming language known for its safety and performance features.
- HCL (HashiCorp Configuration Language) is a configuration language designed for infrastructure automation.

## Commonly Used Linux Commands: 
- A set of essential commands for file and directory operations, file permissions, system information, text processing, package management, and process management in a Linux environment.

 ***File and Directory Operations:***  
 - `ls`: List directory contents 
 - `cd`: Change directory 
 - `pwd`: Print working directory 
 - `mkdir`: Make a new directory 
 - `rm`: Remove files or directories 
 - `mv`: Move or rename files or directories 
 - `cp`: Copy files or directories 
  
 ***File Permissions:*** 
 - `chmod`: Change file permissions 
 - `chown`: Change file or directory ownership 
  
 ***System Information:*** 
 - `top`: Display system processes 
 - `df`: Display disk space usage 
 - `du`: Estimate file and directory space usage 
 - `free`: Display amount of free and used memory in the system 
  
 ***Text Processing:*** 
 - `cat`: Concatenate and display file content 
 - `grep`: Search text using patterns 
 - `sed`: Stream editor for text manipulation 
 - `awk`: Text processing tool for data extraction 
  
 ***Package Management (Debian/Ubuntu):*** 
 - `apt-get`: APT package handling utility (Debian/Ubuntu) 
  
 ***Package Management (Red Hat/CentOS):***
 - `yum`: Package manager (Red Hat/CentOS) 
  
 ***Process Management:***
 - `ps`: Display information about running processes 
 - `kill`: Terminate processes by process ID 

## Blockchain and Cryptocurrency: 
- Blockchain Technology: A decentralized ledger technology used for secure and transparent data recording.
- Satoshi Nakamoto: The pseudonymous creator of Bitcoin, the first cryptocurrency.
- ICO (Initial Coin Offering): A method of fundraising for blockchain projects, where tokens or coins are sold to investors to raise capital.

## Linux Directory Structure:
- The organization of directories in a Linux-based file system, including /bin, /sbin, /etc, /dev, /proc, /var, /tmp, /usr, /home, /boot, /lib, /opt, /mnt, /media, /srv.

## Other Terms: 
- In information technology, header refers to supplemental data placed at the beginning of a block of data being stored or transmitted.
   - In data transmission, the data following the header is sometimes called the payload or body.
     
- RAft Algorithm: Raft is a consensus algorithm. It allows the members of a distributed system to agree on a sequence of values in the presence of failures.
  
- Utility computing, or computer utility, is a service provisioning model in which a service provider makes computing resources and infrastructure management available to the customer as needed, and charges them for specific usage rather than a flat rate.
  
- Infrastructure as Code (IaC) is an approach where infrastructure components (e.g., servers, networks) are defined and managed using code, allowing for automated and consistent provisioning and deployment
  
- PageRank (PR) is an algorithm used by Google Search to rank web pages in their search engine results

- Consensus: Consensus is a general agreement on a decision made by the majority of those involved.
 
- Stack Data Structure: A stack is like a stack of books. You can only add or remove books from the top. It's a way to manage data where the last item added is the first to be used.

- Packets: Packets are like small packages of data. Information is broken into packets for transmission over networks, and these packets are reassembled at their destination.
  
- Compiler vs. Interpreter: Compiler translates the entire source code into machine code at once, while an interpreter translates code line by line and executes it.

- Scheduling: The process of managing and prioritizing tasks in a computer system to optimize resource utilization.

- MERN: MERN is an abbreviation for a technology stack used in web development. It includes MongoDB (a database), Express.js (a web application framework), React (a JavaScript library for user interfaces), and 
Node.js (a runtime for executing JavaScript).

- DevOps: DevOps is like teamwork between developers and operations teams. It's a set of practices that aim to automate and streamline the software development and deployment process.

- Hashing: Hashing is like turning a message into a unique fingerprint. It's a one-way process that converts data into a fixed-size string of characters.

- Arrays and Structures: Arrays are like lists of items, and structures are like custom containers that can hold different types of data. They help organize and store information in programming.

- India Stack: India Stack is like a digital infrastructure for the country. It includes tools for identity verification, payments, and more to promote digital services in India.

- Vector DB: Vector DB is like a library that stores and manages vector data efficiently. It's useful for applications dealing with vectors and spatial data.

- NoSQL: NoSQL databases are like a flexible set of drawers where you can store data in various formats. They're used for handling unstructured and semi-structured data.

- RDBMS: RDBMS is like a well-organized spreadsheet. It stands for Relational Database Management System, used to store structured data in tables.

- Redis: Redis is like a super-fast notepad. It's an in-memory database that stores data for quick retrieval.

- Open Source: Open source is like a recipe that's shared with everyone. It's software or technology with its source code available for anyone to use, modify, and share.

- VCS - Version Control System: VCS is like a time machine for code. It helps developers track changes, collaborate, and go back in time to previous versions of their work.

- Unit Testing: Unit testing is like checking if each ingredient in a recipe is good. It's a method to test individual parts (units) of software to ensure they work correctly.

- Hyper-converged infrastructure (HCI): HCI is like a Swiss Army knife for data centers. It combines storage, computing, and networking into one integrated system for efficient data management.

- Web Assembly (Wasm): Web Assembly is like a universal translator for web browsers. It's a binary instruction format that enables high-performance web applications across different platforms.

## Docker
- Containerization Platform: Docker is like a set of digital containers for applications. It allows you to package an application and its dependencies together in a standardized container, ensuring it runs consistently across different environments.

- Image Packaging: Docker uses images to package applications and their dependencies. These images are like blueprints for containers, containing everything needed to run the application. They can be easily shared and deployed.

- Orchestration: Orchestration in Docker involves managing and scaling containerized applications. It's like conducting an orchestra of containers, ensuring they start, stop, and scale as needed to meet application requirements.

- Image Management: Docker provides tools to build, push, pull, and manage container images. It's like a library where you can store and organize the different versions of your application.

- Microservices: Microservices are like individual instruments in an orchestra. Docker facilitates the development and deployment of microservices, allowing applications to be broken down into smaller, independently deployable components.

- Container Registry: A container registry is like a warehouse for container images. It's a place where you can store, share, and distribute container images, making them accessible to your team or the public.

- Kubernetes Integration: Kubernetes is a powerful orchestration platform for containers. Docker can be integrated with Kubernetes to leverage its advanced features for managing containerized applications.

- Application Isolation: Docker containers provide a level of isolation, ensuring that applications do not interfere with each other. It's like musicians playing in separate soundproof rooms but still part of the same orchestra.

- Service Scaling: Docker allows you to scale services by adjusting the number of containers running an application. It's like adding more musicians to the orchestra when the performance demands it.

## Kubernetes
- Orchestration Tool: Kubernetes is like a conductor for containerized applications. It automates the deployment, scaling, and management of containers, ensuring they work together harmoniously.

- Container Clusters: Container clusters are like orchestras with many musicians. Kubernetes groups containers into clusters, making it easier to manage and scale applications.

- Pod Management: Pods are like musical duets in Kubernetes. They are the smallest deployable units, containing one or more containers. Kubernetes manages the creation, scaling, and scheduling of pods.

- Service Discovery: Service discovery is like knowing where each instrument is on the stage. Kubernetes helps containers find and communicate with each other, ensuring seamless interaction.

- Node Orchestration: Node orchestration in Kubernetes is like ensuring each musician has their designated spot on the stage. It manages the allocation of containers to individual nodes (machines).

- Helm Charts: Helm charts are like sheet music for applications. They provide a way to define, install, and upgrade even the most complex Kubernetes applications.

- Resource Scaling: Resource scaling is like adjusting the number of musicians in an orchestra to match the audience size. Kubernetes can automatically adjust resources allocated to containers based on demand.

- Container Deployment: Container deployment is like setting up an instrument for a performance. Kubernetes handles the process of getting containers up and running.

- Namespaces: Namespaces are like sections in an orchestra pit. They provide a way to divide and isolate resources within a cluster, ensuring different components don't interfere with each other.

- Kubevirt: Kubevirt is like adding special instruments to an orchestra. It's a project that extends Kubernetes to manage virtual machines alongside containers.

## Cloud Computing
- IaaS, PaaS, SaaS: Different cloud service models - Infrastructure as a Service (IaaS), Platform as a Service (PaaS), and Software as a Service (SaaS).
  
- Public, Private, Hybrid Clouds, Multi Cloud: Different cloud deployment models, with public clouds available to the general public, private clouds for a single organization, and hybrid clouds combining both.
  
- Virtualization Technology: Virtualization technology enables the creation of virtual instances of computer resources, allowing multiple operating systems and applications to run on a single physical machine.

- Public Cloud: A public cloud is a cloud computing environment provided by a third-party service provider, offering on-demand computing resources, storage, and services over the internet.

- Elasticity: Automatically increasing server capacity during a sudden traffic spike for a web application.

- Resource Pooling: Sharing computing resources like CPU and memory among multiple virtual machines.

- Cloud Storage: Storing files and data in the cloud. Example: Amazon S3.

- Cloud Security: Encrypting data and using identity access management to secure cloud resources.

- Cloud Networking: Configuring virtual networks in the cloud. Example: AWS Virtual Private Cloud (VPC).

- Cloud Service Models: Cloud service models include Infrastructure as a Service (IaaS), which provides basic computing resources; Platform as a Service (PaaS), offering a platform for app development; and Software as a Service (SaaS), delivering software applications over the internet.

- Microservices in cloud computing means building an application as a collection of small, separate pieces that can do their jobs on their own, like different building blocks that work together to create a bigger structure.
  
- Cloud Orchestration: Automating the provisioning and management of cloud resources using tools.

- Cloud Automation: Automating routine cloud management tasks like backup and scaling.
  
- Cloud Migration: Moving an existing database to a cloud-based database service like Amazon RDS.
  
- Serverless Computing: Running code in response to events, e.g., using AWS Lambda.

- Hybrid Cloud: A hybrid cloud combines private and public clouds, allowing data and applications to be shared between them for flexibility and control.
  
- Load Balancing: Load balancing is like distributing the weight evenly on a scale. It ensures that network traffic is spread across multiple servers to improve performance and reliability.

- CNCF: CNCF is like a club for cloud-native techies. It stands for the Cloud Native Computing Foundation and hosts open-source projects for cloud-native applications.

- HA - High Availability: High Availability means a system that's always ready to work. It's like having a backup generator that kicks in if the power goes out, ensuring minimal downtime.
  
- IaaS, PaaS, SaaS: IaaS offers virtualized computing resources; PaaS provides a platform for app development; SaaS offers software applications accessible over the internet.

- Cloud Security: Cloud security involves measures and tools to protect data, applications, and infrastructure in cloud environments from threats and unauthorized access.

- Terraform: Terraform is an infrastructure as code tool used to provision and manage cloud resources through code.

- Cloudflare: Cloudflare is a content delivery and DDoS protection service that enhances website performance and security.

- DDOS - Distributed Denial of Service Attack: A DDoS attack is a malicious attempt to disrupt the normal functioning of a network or server by overwhelming it with a flood of internet traffic.

- Hyperscalers: Hyperscalers are large cloud service providers known for their ability to scale and provide services globally.

## OpenStack Components And Services
- Cloud Services: Cloud services in OpenStack offer a range of features for creating and managing cloud resources.

- Identity Service: The identity service manages user authentication and access control within an OpenStack cloud.

- Image Storage: Image storage provides a repository for virtual machine images used for creating and deploying instances.

- Block Storage: Block storage offers storage volumes that can be attached to virtual machines for data storage.

- Network Services: Network services manage connectivity and communication between instances and the outside world.

- Object Storage: Object storage provides scalable storage for unstructured data such as images and documents.

- Dashboard UI: The dashboard UI is a web-based interface for managing and controlling OpenStack services.

- Orchestration: Orchestration enables the automated deployment and management of cloud resources.

- Container Support: Container support allows the use of container technologies like Docker within OpenStack.

- Database Service: The database service offers database services for cloud applications.

- Upstream: Upstream refers to the development source of the OpenStack software itself.

- Downstream: Downstream involves the deployment and customization of OpenStack in real-world use.

## Neutron (OpenStack Networking)
- Subnet Management: Subnet management involves the creation of smaller address spaces within a network.

- Router Configuration: Router configuration manages network traffic between different subnets.

- Security Rules: Security rules define what network traffic is allowed and what is not, enhancing network security.

- Load Balancing: Load balancing distributes network traffic evenly among multiple servers or resources to improve performance and redundancy.

- Network Topology: Network topology represents how network devices are interconnected, aiding in network design and management.

## Networking and Protocols: 
- OSI Model (7 Layers): A conceptual framework for understanding network communication, divided into seven layers, including Physical, Data Link, Network, Transport, Session, Presentation, and Application layers.

- DNS (Domain Name System): A system that translates domain names (e.g., www.example.com) into IP addresses for routing and connectivity.

- Network Packet: A network packet is a formatted unit of data carried by a packet-switched network.

- Packet Switching is a method of grouping data into packets that are transmitted over a digital network.
  
- TCP/IP (Transmission Control Protocol/Internet Protocol): A suite of protocols used for internet communication, with TCP managing data transfer reliability and IP handling addressing and routing.
  
- URL (Uniform Resource Locator): A standardized web address format used to identify resources on the internet.
  
- Ports and Packets: Elements of network communication, where ports are specific endpoints for communication, and packets are units of data transmitted over a network.

- Load Balancing: A technique that distributes network traffic evenly across multiple servers to improve performance, availability, and reliability.
  
- Internet (WAN - Wide Area Network): A global network that connects computers and networks across the world, enabling data and information exchange.
  
- Intranet (LAN - Local Area Network): A localized network within an organization that facilitates communication and resource sharing among connected devices.
  
- Port Numbers (HTTP, HTTPS, FTP, SMTP, Telnet, SSH): Port Numbers are like specific doors in a building where data goes in and out. For example, HTTP uses Port 80, HTTPS uses Port 443, FTP uses Port 21, SMTP uses Port 25, Telnet uses Port 23, and SSH uses Port 22.

- Seven Layers of OSI Model: The OSI Model divides network communication into seven layers. Think of it as a cake with seven layers, each having a specific role. These layers help devices communicate over networks by breaking the process into manageable parts.

- NAT (Network Address Translation): NAT is like a magic trick that lets multiple devices in your home share one public IP address. It's like having a translator that helps them talk to the internet.

- Router: A router is like a traffic cop for data. It decides where data should go within a network and also directs data between your home network and the internet.
  
- IP Addressing: IP addressing assigns unique numerical addresses to devices on a network.

- Subnet Masks: Subnet masks divide IP addresses into network and host portions.

- NAT (Network Address Translation): A technique that maps private IP addresses to a single public IP address to allow multiple devices to share the same public IP.
  
- Router: A network device that forwards data packets between computer networks and directs traffic based on IP addresses.

- Router Functions: Routers manage traffic between different networks, ensuring data reaches its destination.

- Firewall Security: Firewalls control incoming and outgoing network traffic to protect against unauthorized access and threats.

- DNS Resolution: DNS resolution translates human-readable domain names into IP addresses for internet communication.

- NAT Translation: NAT translation maps private IP addresses to a single public IP address, allowing multiple devices to share the same public IP.

- OSI Layers: The OSI model is a conceptual framework with seven layers, each with specific roles in network communication.

- VPN Connections: VPN connections provide secure and private communication over a public network.
  
- nginx (Proxy Server): nginx is like a waiter at a restaurant. It takes your order (web request) and brings you the food (web content). It's a web server that also acts as a proxy to help manage internet traffic.

- Apache (Web Server): Apache is like a chef in a restaurant kitchen. It prepares and serves web content. It's one of the most popular web servers used to deliver websites.

- UDP (User Datagram Protocol): UDP is like sending a postcard. It's fast but doesn't guarantee delivery. It's used for quick, real-time communication where some data loss is acceptable.

- BGP Protocol: BGP is a routing protocol used for exchanging routing information between different networks.

- Overlay Network: An overlay network is a virtual network built on top of an existing network, offering additional capabilities.

- Underlay Network: The underlay network is the physical network infrastructure that supports overlay networks.

- Tun Flannel: Tun Flannel is a networking backend for Kubernetes, enabling communication between pods.

- CNI: CNI stands for Container Networking Interface, used to configure network interfaces for containers.

- Cilium: Cilium is an open-source project providing network and security services for containerized applications.

- Tunnel: A tunnel is a virtual pathway for secure data transmission between network points.

- Bridge: A bridge connects and allows communication between two or more network segments.

- Open vSwitch: Open vSwitch is a virtual switch supporting standard network protocols in virtualized environments.

- Tap: A tap captures and forwards network traffic, often used for monitoring and analysis.

## 5G 
- Transmitter
- receiver
- wireless signal (RF Signal) 
- wireless channel (RF Channel)
- Modulation
- Demodulation
- Attenution (transmission loss)
- Noise
- Interferance
- Millimiter Wave
- FCC
- Bandwidth
- Channel
- Narrowband
- Wideband
- Datapipe
- CDMA
- Downlink
- Uplink
- FDD
- TDD
- Signal Bar REPRESENTS Signal to noise ratio (SNR)
- Spectral Efficiency
- RAN (Radio Network Access)
- Core Network
- Analog Modulation
- Digital Voice
- **User-Generated Content:** Content generated and shared by end-users, often in the form of multimedia, such as videos, images, or posts on social media platforms.
- **Congested Environments:** Locations characterized by a high density of connected devices and users, leading to network congestion, where data transfer rates may be adversely affected.
- **High-Speed Train:** Refers to trains that move at high speeds, emphasizing the need for uninterrupted, high-speed internet connectivity, even when traveling on such rapid transit.
- **Cloud Computing:** The practice of storing, managing, and accessing data and software applications over the internet, offering scalability and flexibility for users and organizations.
- **Low Latency:** A minimal delay in data transmission, ensuring that data is transmitted rapidly, essential for real-time applications such as online gaming and interactive content.
- **Virtual Reality (VR):** A technology that creates immersive, computer-generated environments, requiring high data throughput and low latency to provide a seamless and immersive experience.
- **Augmented Reality (AR):** The overlay of digital information onto the real-world environment, necessitating real-time data processing for seamless integration of virtual and physical elements.
- **Connected Vehicles:** Automobiles equipped with advanced technology for communication with other vehicles and infrastructure, enabling features like real-time traffic updates and autonomous driving.
- **Software Updates:** The process of downloading and installing software enhancements or fixes, often to improve functionality, security, or compatibility.
- **Map Updates:** Real-time updates to navigation maps to ensure accurate and current information for route planning and location-based services.
- **Network Capacity:** The ability of a network to handle a high volume of users and data traffic concurrently without degradation in performance.
- **Real-Time Experience:** Applications and services that provide instant responses and minimal delays in data processing, crucial for interactive experiences, such as video conferencing and online gaming.
- **LTE (Long-Term Evolution):** A standard for wireless communication that offers improved data transfer rates and network performance compared to earlier technologies.
- **5G Technology:** The fifth generation of cellular technology designed to deliver significantly higher data speeds, lower latency, and increased network capacity, enabling advanced applications, including the Internet of Things (IoT) and augmented reality.
- **Next-Generation Mobile Experiences:** Enhanced and advanced mobile services made possible by 5G technology, offering high-speed data, low latency, and support for emerging applications and technologies.
- **Fallback Mechanisms:** In software and hardware systems, fallback mechanisms are used to provide alternative courses of action when a primary function or component encounters issues.

- ## 5G Network Architecture
- **UE (User Equipment)**: User Equipment refers to devices like smartphones, tablets, and IoT devices connected to the 5G network.
- **5G RAN (Radio Access Network)**: The 5G Radio Access Network facilitates wireless communication between User Equipment (UE) and the 5G core network. It comprises gNode-Bs (base stations).
- **5G Core Network (NGC - Next Generation Core)**: The core network in a 5G system responsible for managing and routing data within the network. It consists of various components, including AMF, SMF, and UPF.
- **gNode-B**: The next-generation base station is known as gNode-B, serving as the wireless interface between User Equipment and the 5G network.

## Deployment Options: Standalone (SA) and Non-Standalone (NSA)
- **Standalone 5G Network (SA)**: A fully independent 5G network comprising 5G RAN, core network, and User Equipment. This is the long-term goal for network operators.
- **Non-Standalone 5G Network (NSA)**: An intermediate solution where 5G RAN is selectively deployed alongside existing 4G networks. Dual connectivity-capable phones allow users to benefit from both 4G and 5G coverage.
- **Dual Connectivity (DC)**: DC-capable phones can establish two simultaneous channels, one with 4G and one with 5G base stations, enabling higher throughput and addressing capacity challenges.

## Key Techniques for 5G Performance
- **Massive MIMO (Multiple Input Multiple Output)**: Massive MIMO is a technology that uses a large number of antennas at the base station to enhance capacity, speed, and spectral efficiency of wireless communication.
- **Beamforming**: Beamforming focuses radio signals in specific directions, enhancing signal quality, coverage, and capacity.
- **Edge Computing**: This technology processes data closer to the source (e.g., IoT devices), reducing latency and improving real-time communication.
- **Network Slicing**: Network slicing enables network operators to create separate virtual networks within the physical infrastructure to cater to different service requirements efficiently.
- **Millimeter-Wave (mmWave)**: Millimeter-wave spectrum offers high bandwidth for fast data transmission but has shorter propagation distances, making it suitable for specific use cases.
- **Small Cells**: Small cells are low-power base stations that enhance coverage and capacity in areas with high user density.
- **IoT (Internet of Things)**: IoT refers to a network of interconnected devices and objects that can transmit data, enabling applications ranging from smart homes to industrial automation.
- **URLLC (Ultra-Reliable Low Latency Communication)**: URLLC services offer highly reliable and low-latency communication for applications like mission-critical services, remote healthcare, and real-time manufacturing.
- **AMF (Access and Mobility Management Function)**: AMF provides permission and manages access for user equipment to the 5G network.
- **SMF (Session Management Function)**: SMF handles session establishment, IP assignment, and session management in a 5G network.
- **UPF (User Plane Function)**: UPF manages user data transmission, delivering content to the user's device.
- **Slot-Based Framework:** A mechanism in communication systems that allows for flexible allocation of time slots or resources, enabling more efficient utilization of resources and adaptability to real-time requirements.
- **Resource Allocation:** The process of assigning available resources, such as bandwidth or time slots, to different users or applications in a network to ensure efficient use of those resources.
- **OFDM (Orthogonal Frequency Division Multiplexing):** A modulation technique used in wireless communication that divides a wideband channel into multiple narrowband subchannels, allowing for improved data transmission and adaptability to varying channel conditions.
- **Channel Coding:** The addition of redundant information (metadata) to data before transmission to enhance error detection and correction, ensuring data integrity even in the presence of noise or interference.
- **Metadata:** Additional information added to the original data to provide context or facilitate data processing. In the context of channel coding, it includes error-checking data.
- **Interference:** Unwanted signals or noise that disrupt the transmission and reception of data in a communication system, leading to potential data errors and reduced signal quality.
- **Retransmissions:** The process of re-sending data that was not received correctly due to errors, often caused by interference or signal degradation.
- **Data Rates:** The speed at which data is transmitted or received, typically measured in bits per second (bps), and a key factor in determining the efficiency and performance of a communication system.
- **Antennas**: Devices for transmitting and receiving wireless signals.
- **Wireless signals**: Electromagnetic waves for data transmission.
- **Frequency channel**: Specific radio frequency range for signals.
- **Data throughput**: Rate of data transmission/processing.
- **Network capacity**: Maximum data handling of a network.
- **Spectral efficiency**: Efficient spectrum use for data transmission.
- **Encoding techniques**: Methods for data representation.
- **Interference**: Unwanted signal overlap disrupting communication.
- **Smart signal processing**: Algorithms for signal management.
- **Data rates**: Speed of data transmission/reception.
- **Highly Technical Keywords**
- **Millimeter Wave Frequency Range**: Refers to a specific range of high-frequency electromagnetic waves with wavelengths measured in millimeters. In the context of mobile communications, this range is used to transmit data.
- **Frequency Spectrum**: The range of frequencies within the electromagnetic spectrum. In the context of mobile millimeter wave, it pertains to the specific frequencies within the millimeter wave range.
- **Spectrum Scarcity**: The limited availability of frequency spectrum for wireless communication, often leading to congestion in existing frequency bands.
- **Bandwidth Utilization**: Efficient usage of available frequency bandwidth for transmitting and receiving data. In mobile millimeter wave, optimizing bandwidth is crucial for high data rates.
- **Communication Systems**: Complex networks and technologies used for transmitting and receiving data. In the context of millimeter wave, it involves the systems that harness these high-frequency signals.
- **Wavelength**: The distance between two consecutive points in a wave. In the millimeter wave frequency range, shorter wavelengths are a defining characteristic, leading to unique propagation characteristics.
- **Mobile Millimeter Wave**: A technology that operates in the millimeter wave frequency range for mobile communication. It aims to leverage high-frequency bands for faster data rates and increased network capacity.
- **Network Architecture Principles**: Fundamental design guidelines defining the structure and operation of 5G networks.
- **Independence of Software from Hardware**: The separation of software and hardware components within the network architecture for improved flexibility and scalability.
- **Separation of Compute and Storage Resources**: Decoupling of network compute servers (for high-power computations) from storage resources, enhancing redundancy and resilience.
- **Separation of User Plane and Control Plane**: Isolating application data (user plane) from background signaling (control plane), providing flexibility and scalability.
- **Logical Subsets of Network Components**: Network slices, which are subsets of available network resources customized for specific applications.
- **Resource Allocation**: The process of assigning network resources within a slice to meet the specific requirements of an application.
- **Redundancy and Resiliency**: Ensuring network reliability by separating compute and storage resources, preventing single points of failure.
- **Flexible Subscription Models**: The ability to offer customized network services to customers based on their requirements.
- **Application Requirements**: Diverse needs of applications, including eMBB, IoT, and URLLC, in terms of latency, connection density, and throughput.
- **Background Signaling**: The underlying network processes and communication required to set up and manage user plane data sessions.

- ## AWS
- **Anamoly Detection** (identification of rare events, items, or observations which are suspicious because they differ significantly from standard behaviors)
- **Amazon Cloudwatch** ( monitor your complete stack (applications, infrastructure, network, and services) and use alarms, logs, and events data to take automated actions and reduce mean time to resolution (MTTR))
- **MTTR** (average time it takes to repair a system)
