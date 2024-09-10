# CS_Keywords
BASIC KEYWORDS:-
Computation:
1) Computation refers to the process of performing mathematical calculations or processing data according to a set of instructions (software programs).
It involves operations like addition, subtraction, multiplication, division, and logical comparisons.
Function:
The Central Processing Unit (CPU) in a computer handles computation by executing instructions from programs, performing calculations, and processing data.
2) Storage:
Storage refers to the methods and devices used to save and retrieve data and software. It can be either temporary or permanent.
Types:
Primary Storage (RAM):Temporary storage that holds data and instructions currently being used or processed by the CPU.
Secondary Storage:Permanent storage like Hard Disk Drives (HDDs) or Solid State Drives (SSDs) that save data even when the computer is turned off.
3) Network:A network is a system of interconnected computers and devices that can communicate with each other to share resources and information.
Types:
Local Area Network (LAN): A network that connects devices within a limited area, like a home or office.
Wide Area Network (WAN): A network that covers a larger geographic area, such as connecting multiple cities or countries.
Internet: A global network connecting millions of private, public, academic, and business networks, allowing worldwide communication and information exchange.


7 LAYERS OF OSI:-
The OSI (Open Systems Interconnection) model is a framework for understanding and designing network systems. It divides the process of network communication into seven distinct layers, each with specific functions. Here’s a brief overview of each layer:
1) Physical Layer (Layer 1): Handles the physical connection between devices, including the transmission of raw binary data over a medium like cables or wireless signals. Examples: Ethernet cables, fiber optics, and radio frequencies.
2) Data Link Layer (Layer 2): Manages node-to-node data transfer and handles error detection and correction. It packages raw data from the Physical Layer into frames and ensures reliable delivery. Examples: Ethernet, Wi-Fi, and MAC addresses.
3) Network Layer (Layer 3): Responsible for routing data across different networks and handling logical addressing and packet forwarding. It determines the best path for data to travel from source to destination. Examples: IP addresses and routers.
4) Transport Layer (Layer 4):Manages end-to-end communication and data flow control. It ensures that data is delivered error-free, in sequence, and without loss or duplication. Examples: TCP (Transmission Control Protocol) and UDP (User Datagram Protocol).
5) Session Layer (Layer 5): Manages sessions or connections between applications. It establishes, maintains, and terminates communication sessions. Examples: Session management in communication protocols, such as in web or file transfer applications.
6) Presentation Layer (Layer 6): Translates data between the application layer and the network format. It handles data encryption, decryption, and conversion between different data formats. Examples: Data translation and encryption formats like JPEG, ASCII, and SSL/TLS.
7) Application Layer (Layer 7): Provides network services directly to end-user applications. It’s the interface for user applications to interact with the network. Examples: Web browsers, email clients, and file transfer protocols.

The OSI model helps in understanding and troubleshooting network issues by separating network communication into manageable layers.


About protocol,DNS,port number.:-
Protocol: In computing, a protocol is a set of rules that define how data is transmitted and received over a network. It ensures that devices can communicate effectively and understand each other.
DNS (Domain Name System): DNS is a protocol that translates human-readable domain names (like www.example.com) into IP addresses (like 192.16.0.73), which are used by computers to locate each other on the internet.
Port Number: A port number is a numerical identifier used in networking to specify a particular process or service on a device. For example, HTTP traffic typically uses port 80, and HTTPS uses port 443.


FRONT-END,BACK-END,API:-
Front-end: The part of a website or application that users interact with directly. It includes everything the user sees and experiences, such as layout, design, and user interface elements. Technologies used include HTML, CSS, and JavaScript.
Back-end: The server-side part of a website or application that handles data processing, database interactions, and server logic. It ensures that requests from the front-end are processed and responded to correctly. Common languages include Python, Java, and Node.javascript.
API (Application Programming Interface): A set of rules and protocols that allows different software applications to communicate with each other. APIs enable the front-end and back-end to interact by sending requests and receiving responses, often in the form of data.


CLOUD COMPUTING:-
Cloud Computing is the delivery of computing services—including servers, storage, databases, networking, software, and more—over the internet (the “cloud”). It allows users to access and use resources on-demand without managing physical infrastructure.
Types of Cloud Computing:
1) Public Cloud: Services are provided over the internet and shared among multiple organizations. Examples include Amazon Web Services (AWS), Microsoft Azure, and Google Cloud Platform (GCP). It’s cost-effective and scalable but offers less control over the infrastructure.
2) Private Cloud: Services are maintained on a private network, dedicated to a single organization. This provides greater control and security but can be more expensive. It can be hosted on-premises or by a third-party provider.
3) Hybrid Cloud: Combines public and private clouds, allowing data and applications to move between them. This approach offers greater flexibility, optimizing existing infrastructure while leveraging the scalability of public clouds.

Each type provides different levels of control, flexibility, and cost, allowing organizations to choose based on their specific needs.


BLOCKCHAIN:-
Block chain is a decentralized digital ledger that records transactions in a series of linked blocks. Each block contains a set of transactions and is securely linked to the previous one, ensuring data integrity and immutability. It operates across a network of computers, making it transparent and resistant to tampering or fraud.Some famous examples are:-
1.ARM
2.CISC[complex instruction set computer]-
it is a closed source like intel and AMD(advanced micro devices).It develop X-86 series under ISA[intruction set arichtecture] in 1978.
3.RISC[reduced instruction set computer]-
it is a close source like ARM[Adavnce risc machine] .It has specific intruction,very fast and efficient.
4.RISC-V-
It is based on RISC principles and develop in 2023 and which is a free open source. it also have a project called SHAKTI.
5.ASIC:-
ASIC stands for Application-Specific integrated circuit. it's a type of integrated circuit designed for a specific application or function, rather than general puerpose use. for example, an ASIC designed for cryptocurrency mining is specifically built to perform the hashing calculations required for mining.

SOC(SYSTEM ON A CHIP)-

A System on Chip or an SoC is an integrated circuit that incorporates a majority of components present on a computer. As the name suggests, it is an entire system fabricated on a silicon chip. The beauty of an SoC is that it integrates all the components on a single substrate. In semiconductors, a substrate is a thin film of silicon used to fabricate integrated circuits. In contrast to the traditional motherboard, SoC integrates the replaceable components onto a single chip, thereby reducing the size and increasing efficiency.

OPERATING SYSTEM(OS):

An Operating system is system software that manages computer hardware and software resources and provides common services for computer programs. it act as an intermediary between users and computer hardware
The most commonly used Operating System(OS):-
WINDOWS
MACos
LINUX
#NIC
A network interface card, also known as NIC or network interface controller, is typically a circuit board installed on the computer to connect to the network. It works as an indispensable component for the network connection of computers.

#CLOUD COMPUTING
Cloud computing is the delivery of computing services—including servers, storage, databases, networking, software, analytics, and intelligence—over the Internet ("the cloud"). This allows for faster innovation, flexible resources, and economies of scale.

#BARE METAL SYSTEM
A bare-metal system is a computer system that operates directly on the hardware without the use of an operating system. This means that the software running on the system has direct access to the hardware resources, such as the CPU, memory, and Input/Output devices.

In simpler terms, it's like running a car without a driver: the engine and other components are working directly, without any intermediary system to manage them.

#VIRTUAL MACHINE
A virtual machine (VM) is a software-based emulation of a physical computer that allows multiple operating systems or instances to run on a single physical machine. VMs provide isolation, encapsulation, and resource efficiency, making them valuable for development, testing, and production environments. They come in two main types: system virtual machines, which emulate entire systems, and process virtual machines, which abstract individual applications. While VMs offer numerous advantages, including flexibility and efficient resource utilization, they also come with performance overhead and management complexity.

#KERNEL
The kernel is a computer program at the core of a computer's operating system and generally has complete control over everything in the system. The kernel is also responsible for preventing and mitigating conflicts between different processes.

#IP ADDRESS
An IP address (Internet Protocol address) is a unique string of numbers separated by periods or colons that identifies each device connected to a network. IP addresses serve two primary functions: identifying the host or network interface and providing the location of the host in the network. They are essential for routing internet traffic and ensuring data reaches the correct destination.

#ISP(INTERNET SERVICE PROVIDER)
An ISP, or Internet Service Provider, is a company or organization that provides individuals and businesses with access to the internet. ISPs offer various types of internet connections, including:

#DSL (DIGITAL SUBSCRIBER LINE)
Uses telephone lines to provide internet access. Cable: Uses cable television lines for internet service. Fiber-optic: Uses fiber-optic cables for high-speed internet access. Satellite: Provides internet access via satellite signals, useful in remote areas. Wireless: Uses radio signals to connect to the internet, which can include both fixed wireless and mobile broadband.

#DNS(DOMAIN NAME SYSTEM)
DNS stands for Domain Name System. It functions like a phone book for the internet, translating human-friendly domain names (like www.example.com) into IP addresses (like 192.0.2.1) that computers use to identify each other on the network.

#VPN(VIRTUAL PRIVATE NETWORK)
A VPN, or Virtual Private Network, is a service that creates a secure, encrypted connection over a less secure network, such as the internet. It allows you to access the internet as if you were connected to a private network, providing privacy and security.

When you use a VPN, your internet traffic is routed through a secure server before reaching its destination, adding a layer of privacy and security. However, it's important to choose a reputable VPN provider to ensure your data is handled securely and your privacy is protected.

#SEMICONDUCOTRS
Semiconductors, also known as integrated circuits (ICs) or computer chips, are essential components of computers and other electronic devices.
#FUNCTION
Semiconductors process data, store information, and control electronic devices.

#Production
There are many 2-3 companies in the world that manufacture chips .e.g TSMC ,intel , samsung. And the machines used for producing chips is provided by ASML company

#ARCHITECTURE X-86 :- intel,AMD
CISC :- Intel,AMD
RISC :- ARM
