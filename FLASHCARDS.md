# A Level Computer Science - Unit 1: Computer Systems
## Comprehensive Study Flashcards

Total Flashcards: **175**

---

## 📚 Category 1: Computer Components & Architecture

### Q: What is the Von Neumann architecture?
**A:** A computer architecture where both program instructions and data are stored in the same memory. It consists of a CPU, memory unit, and input/output mechanisms, with a single shared bus for data and instructions.

### Q: What are the main components of the CPU?
**A:**
1. Arithmetic Logic Unit (ALU)
2. Control Unit (CU)
3. Registers (including PC, ACC, MAR, MDR, CIR)
4. Cache memory

### Q: What is the function of the Arithmetic Logic Unit (ALU)?
**A:** The ALU performs arithmetic operations (addition, subtraction) and logical operations (AND, OR, NOT, comparisons) on data.

### Q: What is the function of the Control Unit (CU)?
**A:** The Control Unit coordinates and controls all operations within the CPU. It decodes instructions, sends control signals to other components, and manages the fetch-decode-execute cycle.

### Q: What is the Program Counter (PC)?
**A:** A register that holds the memory address of the next instruction to be fetched and executed. It is automatically incremented after each instruction fetch.

### Q: What is the Accumulator (ACC)?
**A:** A register that stores the results of calculations performed by the ALU. It holds intermediate results during processing.

### Q: What is the Memory Address Register (MAR)?
**A:** A register that holds the memory address of the data or instruction that needs to be accessed (read from or written to).

### Q: What is the Memory Data Register (MDR)?
**A:** A register that temporarily stores data that has been read from memory or data that is about to be written to memory. Also known as Memory Buffer Register (MBR).

### Q: What is the Current Instruction Register (CIR)?
**A:** A register that holds the current instruction being decoded and executed. It stores the instruction after it has been fetched from memory.

### Q: What is cache memory?
**A:** A small amount of very fast memory located inside or close to the CPU that stores frequently accessed data and instructions to speed up processing. It sits between the CPU and main memory.

### Q: What are the levels of cache memory?
**A:**
- **L1 Cache:** Smallest and fastest, built into CPU cores
- **L2 Cache:** Larger than L1, may be shared between cores
- **L3 Cache:** Largest and slowest cache, shared across all cores

### Q: What is the Harvard architecture?
**A:** A computer architecture that has separate memory storage and pathways for instructions and data, allowing simultaneous access to both. Used in embedded systems and microcontrollers.

---

## 🔄 Category 2: Fetch-Decode-Execute Cycle

### Q: What is the Fetch-Decode-Execute Cycle?
**A:** The fundamental process by which a CPU retrieves, interprets, and executes instructions. It repeats continuously while the computer is running.

### Q: What happens during the FETCH stage?
**A:**
1. Address from PC is copied to MAR
2. Instruction at that address is copied to MDR
3. Instruction is copied from MDR to CIR
4. PC is incremented to point to next instruction

### Q: What happens during the DECODE stage?
**A:** The Control Unit decodes the instruction in the CIR, determining what operation needs to be performed and what data is required.

### Q: What happens during the EXECUTE stage?
**A:** The instruction is carried out. This may involve:
- The ALU performing calculations
- Data being moved between registers
- Reading/writing to memory
- Jumping to a different instruction

### Q: What factors affect CPU performance?
**A:**
1. Clock Speed (measured in GHz)
2. Number of cores
3. Cache size and type
4. Word length/bus width
5. Architecture type

### Q: What is clock speed?
**A:** The number of fetch-decode-execute cycles the CPU can complete per second, measured in Hertz (Hz). A 3.5 GHz processor completes 3.5 billion cycles per second.

### Q: What are cores in a CPU?
**A:** Independent processing units within a single CPU chip. Multi-core processors can execute multiple instructions simultaneously (parallel processing), improving performance for multi-threaded applications.

### Q: What is word length/bus width?
**A:** The number of bits that can be transferred simultaneously through the data bus or processed in a single operation. Common sizes are 32-bit or 64-bit.

---

## 🖥️ Category 3: Processor Types & Architecture

### Q: What is CISC (Complex Instruction Set Computer)?
**A:** A processor architecture with a large instruction set, where single instructions can execute complex operations. Examples: Intel x86, AMD processors. More complex circuitry but fewer instructions needed for programs.

### Q: What is RISC (Reduced Instruction Set Computer)?
**A:** A processor architecture with a smaller, simpler instruction set where each instruction executes in a single clock cycle. Examples: ARM processors. Simpler circuitry, better for pipelining, more energy efficient.

### Q: What are the advantages of RISC?
**A:**
1. Simpler instructions execute faster
2. Better for pipelining
3. More energy efficient
4. Lower heat generation
5. Lower cost to manufacture

### Q: What are the advantages of CISC?
**A:**
1. Fewer instructions needed for tasks
2. More memory efficient (smaller programs)
3. Better for complex operations
4. Easier to write assembly code

### Q: What is pipelining?
**A:** A technique where multiple instructions are overlapped in execution. While one instruction is being executed, the next is being decoded, and another is being fetched. This increases throughput and CPU efficiency.

### Q: What is parallel processing?
**A:** The simultaneous execution of multiple instructions or tasks using multiple processors or cores. Improves performance for applications designed to use multiple threads.

### Q: What is a GPU (Graphics Processing Unit)?
**A:** A specialized processor designed for parallel processing of graphics and visual data. Contains thousands of small cores optimized for handling multiple tasks simultaneously, useful for graphics rendering, AI, and scientific computing.

### Q: What is a multi-core processor?
**A:** A single CPU chip containing multiple independent processing cores, each capable of executing instructions. Allows true parallel processing and improved multitasking performance.

---

## 💾 Category 4: Input, Output & Storage Devices

### Q: What are input devices? Give examples.
**A:** Devices that allow data to enter the computer system.
**Examples:** Keyboard, mouse, touchscreen, microphone, webcam, scanner, barcode reader, sensors (temperature, pressure, motion)

### Q: What are output devices? Give examples.
**A:** Devices that allow data to leave the computer system.
**Examples:** Monitor/display, printer, speakers, headphones, projector, actuators (motors, LEDs)

### Q: What is primary storage?
**A:** Memory directly accessible by the CPU, including RAM and ROM. It is fast but volatile (except ROM). Used for currently running programs and data.

### Q: What is RAM (Random Access Memory)?
**A:** Volatile memory that stores currently running programs and data in use. Data is lost when power is turned off. Fast read/write speeds. Can be accessed in any order.

### Q: What is ROM (Read Only Memory)?
**A:** Non-volatile memory that stores permanent instructions (like BIOS/firmware). Data persists when power is off. Cannot be easily modified. Contains boot-up instructions.

### Q: What is secondary storage? Give examples.
**A:** Non-volatile storage for long-term data persistence. Slower than primary storage but has much larger capacity.
**Examples:** Hard Disk Drive (HDD), Solid State Drive (SSD), USB flash drives, optical discs (CD, DVD, Blu-ray), magnetic tape

### Q: What is an HDD (Hard Disk Drive)?
**A:** A magnetic storage device using spinning platters coated with magnetic material. Read/write heads access data. Large capacity, relatively cheap, but slower than SSDs and has moving parts that can fail.

### Q: What is an SSD (Solid State Drive)?
**A:** A storage device using flash memory (no moving parts). Much faster than HDDs, more reliable, silent operation, but more expensive per GB. Uses NAND flash memory.

### Q: What is virtual memory?
**A:** A memory management technique where secondary storage (hard drive/SSD) is used as an extension of RAM when physical RAM is full. Slower than RAM but allows running more programs than RAM capacity would normally allow.

### Q: What are optical storage devices?
**A:** Storage media that use laser light to read/write data on discs. Types: CD (700MB), DVD (4.7-8.5GB), Blu-ray (25-50GB). Portable and durable but slower than SSDs and can be scratched.

---

## 🖧 Category 5: Operating Systems & Scheduling

### Q: What is an operating system (OS)?
**A:** System software that manages computer hardware and software resources, provides common services for programs, and acts as an interface between users and hardware. Examples: Windows, macOS, Linux, Android.

### Q: What are the main functions of an operating system?
**A:**
1. Memory management
2. Processor/CPU scheduling
3. File management
4. Device/peripheral management
5. User interface provision
6. Security and access control
7. Error handling

### Q: What is process scheduling?
**A:** The method by which the operating system decides which process gets CPU time and in what order. Essential for multitasking and efficient resource utilization.

### Q: What is Round Robin scheduling?
**A:** A scheduling algorithm where each process gets a fixed time slice (quantum) of CPU time in turn. If not completed in that time, it goes to the back of the queue. Fair but may not be efficient for short processes.

### Q: What is First Come First Served (FCFS) scheduling?
**A:** Processes are executed in the order they arrive. Simple but can lead to convoy effect where short processes wait for long ones. Non-preemptive.

### Q: What is Shortest Job First (SJF) scheduling?
**A:** The process with the shortest execution time is selected next. Minimizes average waiting time but requires knowing execution times in advance and can cause starvation of longer processes.

### Q: What is Multi-Level Feedback Queue scheduling?
**A:** Uses multiple queues with different priorities. Processes can move between queues based on behavior. CPU-intensive processes move to lower priority queues while I/O-bound processes stay in higher priority queues. Flexible and adaptive.

### Q: What is the difference between preemptive and non-preemptive scheduling?
**A:**
- **Preemptive:** OS can interrupt a running process and allocate CPU to another process (e.g., Round Robin).
- **Non-preemptive:** Once a process starts, it runs until completion or voluntarily yields CPU (e.g., FCFS).

### Q: What is interrupt handling?
**A:** The process of responding to signals (interrupts) from hardware or software. The CPU temporarily stops current execution, saves its state, handles the interrupt, then resumes. Examples: keyboard input, mouse click, timer, hardware errors.

---

## 🌐 Category 6: Networking Fundamentals

### Q: What is a LAN (Local Area Network)?
**A:** A network covering a small geographical area (single building or campus). Characteristics: High speed, owned by single organization, low latency, uses Ethernet or Wi-Fi.

### Q: What is a WAN (Wide Area Network)?
**A:** A network covering a large geographical area (cities, countries, globally). Characteristics: Lower speed than LAN, uses third-party infrastructure (ISPs), higher latency. The Internet is the largest WAN.

### Q: What is the TCP/IP model?
**A:** A 4-layer protocol stack for network communication:
1. Application Layer (HTTP, FTP, SMTP, DNS)
2. Transport Layer (TCP, UDP)
3. Internet Layer (IP, routing)
4. Link Layer (Ethernet, Wi-Fi, physical transmission)

### Q: What is the Application Layer?
**A:** The top layer of TCP/IP stack where network applications and protocols operate. Protocols include HTTP (web), FTP (file transfer), SMTP (email), DNS (domain names). Provides services directly to users.

### Q: What is the Transport Layer?
**A:** Responsible for end-to-end communication and data delivery. Main protocols:
- **TCP (Transmission Control Protocol):** reliable, connection-oriented, error-checking
- **UDP (User Datagram Protocol):** faster, connectionless, no error-checking

### Q: What is the Internet Layer?
**A:** Handles addressing and routing of data packets across networks. Uses IP (Internet Protocol) to assign addresses and route packets to their destination. Includes IPv4 and IPv6.

### Q: What is the Link Layer?
**A:** The lowest layer that handles physical transmission of data over network hardware. Includes Ethernet, Wi-Fi, MAC addresses. Deals with physical connections and local network communication.

### Q: What is packet switching?
**A:** A method where data is broken into small packets that are sent independently across the network and reassembled at destination. Each packet can take different routes. Efficient use of bandwidth, robust, but variable latency.

### Q: What is circuit switching?
**A:** A method where a dedicated communication path is established between sender and receiver for the entire duration of transmission (like traditional phone calls). Guaranteed bandwidth but inefficient resource use.

### Q: What is a protocol?
**A:** A set of rules and standards that govern how data is transmitted and received over a network. Ensures different devices can communicate effectively. Examples: HTTP, TCP, IP, FTP.

### Q: What is TCP (Transmission Control Protocol)?
**A:** A connection-oriented protocol that ensures reliable data transmission. Features: establishes connection (handshake), error-checking, guaranteed delivery, packet ordering, flow control. Used for web browsing, email, file transfer.

### Q: What is UDP (User Datagram Protocol)?
**A:** A connectionless protocol for fast data transmission without reliability guarantees. No error-checking or delivery guarantee. Used for streaming, gaming, VoIP, DNS where speed is more important than reliability.

### Q: What is an IP address?
**A:** A unique numerical identifier assigned to each device on a network. IPv4 uses 32 bits (e.g., 192.168.1.1), IPv6 uses 128 bits. Allows devices to be located and communicated with on networks.

### Q: What is DNS (Domain Name System)?
**A:** A system that translates human-readable domain names (e.g., google.com) into IP addresses that computers use. Acts like a phone book for the internet.

### Q: What is a MAC address?
**A:** A unique hardware identifier assigned to network interface cards (NICs). 48 bits long, written in hexadecimal (e.g., AA:BB:CC:DD:EE:FF). Used for communication within local networks at the Link Layer.

---

## 📊 Category 7: Data Types & Representation

### Q: What are primitive data types?
**A:** Basic data types built into programming languages:
- **Integer:** whole numbers
- **Real/Float:** decimal numbers
- **Boolean:** True/False
- **Character:** single character
- **String:** sequence of characters

### Q: What is an integer data type?
**A:** A data type for whole numbers (positive, negative, or zero) without decimal points. Examples: -5, 0, 42, 1000. Fixed size in memory (e.g., 16-bit, 32-bit, 64-bit).

### Q: What is a real/float data type?
**A:** A data type for numbers with decimal points. Uses floating-point representation. Examples: 3.14, -0.5, 2.71828. May have precision limitations due to binary representation.

### Q: What is a boolean data type?
**A:** A data type with only two possible values: True or False (1 or 0). Used for logical operations and conditions. Typically stored in 1 byte though only needs 1 bit.

### Q: What is a character data type?
**A:** A data type representing a single character, stored using a character encoding system like ASCII or Unicode. Examples: 'A', '7', '@'. Typically 1 byte (ASCII) or 2+ bytes (Unicode).

### Q: What is a string data type?
**A:** A sequence of characters treated as a single unit. Can be of variable or fixed length. Examples: "Hello", "Computer Science", "". May be represented as arrays of characters.

### Q: What is ASCII encoding?
**A:** American Standard Code for Information Interchange. A 7-bit character encoding (0-127) representing English letters, digits, and symbols. Each character has a unique code (e.g., 'A' = 65, '0' = 48).

### Q: What is Unicode encoding?
**A:** A universal character encoding standard supporting characters from all writing systems. UTF-8 uses 1-4 bytes per character, UTF-16 uses 2-4 bytes, UTF-32 uses 4 bytes. Backward compatible with ASCII.

### Q: What is binary number system?
**A:** Base-2 number system using only two digits: 0 and 1. Each digit is a 'bit'. Computers use binary because it maps to electronic states (on/off). Example: 1011₂ = 11₁₀

### Q: What is hexadecimal number system?
**A:** Base-16 number system using digits 0-9 and letters A-F (10-15). Used as shorthand for binary. Each hex digit represents 4 binary bits. Example: FF₁₆ = 255₁₀ = 11111111₂

### Q: How do you convert binary to denary (decimal)?
**A:** Multiply each bit by its position value (powers of 2) and sum:
1011₂ = (1×8) + (0×4) + (1×2) + (1×1) = 8 + 0 + 2 + 1 = 11₁₀
Positions from right: 2⁰, 2¹, 2², 2³...

### Q: How do you convert denary to binary?
**A:** Repeatedly divide by 2 and record remainders:
- 11 ÷ 2 = 5 remainder 1
- 5 ÷ 2 = 2 remainder 1
- 2 ÷ 2 = 1 remainder 0
- 1 ÷ 2 = 0 remainder 1

Read remainders bottom-to-top: 1011₂

### Q: What is binary addition?
**A:** Rules:
- 0 + 0 = 0
- 0 + 1 = 1
- 1 + 0 = 1
- 1 + 1 = 10 (0, carry 1)
- 1 + 1 + 1 = 11 (1, carry 1)

Carry bits to next column like decimal addition.

### Q: What is two's complement?
**A:** A method for representing signed (positive and negative) integers in binary. To negate: invert all bits then add 1. The leftmost bit indicates sign (0=positive, 1=negative). Allows simple addition circuitry for positive and negative numbers.

### Q: What is overflow in binary arithmetic?
**A:** When the result of a calculation is too large to be represented in the available number of bits. The carry bit extends beyond the available space, causing an incorrect result. Example: adding two 8-bit numbers resulting in 9 bits.

---

## 🖼️ Category 8: Images & Sound Representation

### Q: What is a bitmap image?
**A:** An image represented as a grid of pixels (picture elements), where each pixel has a specific color value. File size depends on resolution and color depth. Examples: BMP, PNG, JPEG.

### Q: What is resolution in images?
**A:** The number of pixels in an image, usually expressed as width × height (e.g., 1920×1080). Higher resolution means more detail but larger file size.

### Q: What is color depth/bit depth in images?
**A:** The number of bits used to represent the color of each pixel. More bits = more colors possible:
- **1-bit:** 2 colors (black/white)
- **8-bit:** 256 colors
- **24-bit:** 16.7 million colors (8 bits each for Red, Green, Blue)

### Q: How do you calculate image file size?
**A:** File Size = Width × Height × Color Depth

Example: 1920×1080 image with 24-bit color:
1920 × 1080 × 24 = 49,766,400 bits = 6,220,800 bytes ≈ 6.2 MB
(Before compression)

### Q: What is metadata in image files?
**A:** Data about the image stored alongside pixel data:
- Image dimensions (width, height)
- Color depth
- Creation date/time
- Camera settings (ISO, shutter speed, aperture)
- GPS location
- Author/copyright

### Q: What is the difference between vector and bitmap graphics?
**A:**
- **Bitmap:** Grid of pixels, loses quality when scaled, larger files for complex images. Used for photos.
- **Vector:** Mathematical equations for shapes/lines, scales without quality loss, smaller files for simple images. Used for logos, illustrations.

### Q: What is sound sampling?
**A:** The process of converting analog sound waves into digital data by measuring (sampling) the amplitude of the wave at regular intervals. Each measurement is a sample.

### Q: What is sample rate?
**A:** The number of samples taken per second, measured in Hertz (Hz). Higher sample rate = better quality audio.
- CD quality: 44,100 Hz (44.1 kHz)
- Human hearing range: up to ~20 kHz

### Q: What is bit depth in audio?
**A:** The number of bits used to represent each audio sample. Higher bit depth = more precise amplitude values and greater dynamic range.
- **8-bit:** 256 levels
- **16-bit:** 65,536 levels (CD quality)
- **24-bit:** 16.7 million levels (studio quality)

### Q: How do you calculate sound file size?
**A:** File Size = Sample Rate × Bit Depth × Duration × Number of Channels

Example: 1 minute of CD quality stereo:
44,100 × 16 × 60 × 2 = 84,672,000 bits ≈ 10.6 MB
(Before compression)

### Q: What is lossy compression?
**A:** Compression that reduces file size by permanently removing some data. Results in smaller files but quality loss. Used when perfect accuracy isn't critical.
**Examples:** JPEG (images), MP3 (audio), MP4 (video)

### Q: What is lossless compression?
**A:** Compression that reduces file size without losing any data. Original can be perfectly reconstructed. Larger files than lossy but maintains quality.
**Examples:** PNG (images), FLAC (audio), ZIP (general)

---

## 💻 Category 9: Software Development

### Q: What are the stages of the software development lifecycle?
**A:**
1. **Analysis** - understand problem and requirements
2. **Design** - plan solution architecture
3. **Implementation** - write code
4. **Testing** - find and fix bugs
5. **Evaluation** - assess if requirements met
6. **Maintenance** - updates and bug fixes

### Q: What is a high-level programming language?
**A:** A programming language with abstraction from hardware details, using English-like commands. Easier to learn and write but must be translated. Examples: Python, Java, C++, JavaScript. Portable across different systems.

### Q: What is a low-level programming language?
**A:** A programming language close to machine code with little abstraction. Hard to learn but offers fine control over hardware.
- **Assembly:** one-to-one mapping with machine code
- **Machine code:** binary instructions executed directly by CPU

### Q: What is a compiler?
**A:** A translator that converts entire high-level source code into machine code before execution. Creates executable file. Advantages: fast execution, code optimization, no translator needed at runtime. Used by C++, C.

### Q: What is an interpreter?
**A:** A translator that converts high-level code line-by-line during execution. No executable created. Advantages: easier debugging, instant execution, cross-platform. Disadvantages: slower execution. Used by Python, JavaScript (though modern ones use JIT).

### Q: What are integrated development environments (IDEs)?
**A:** Software applications providing comprehensive facilities for development:
- Code editor with syntax highlighting
- Debugger for finding errors
- Compiler/interpreter
- Auto-completion
- Project management

**Examples:** Visual Studio, PyCharm, IntelliJ

### Q: What is syntax in programming?
**A:** The set of rules that define the correct structure and format of code in a programming language. Syntax errors prevent code from running. Examples: missing semicolons, incorrect indentation, mismatched brackets.

### Q: What are variables in programming?
**A:** Named storage locations in memory that hold data values which can change during program execution. Must have: identifier (name), data type, value. Example: age = 18

### Q: What are constants in programming?
**A:** Named values that cannot be changed during program execution. Used for values that should remain fixed. Examples: PI = 3.14159, MAX_USERS = 100. Improves code readability and maintainability.

### Q: What are the three programming constructs?
**A:**
1. **Sequence:** instructions executed in order, line by line
2. **Selection:** decisions using IF/ELSE statements
3. **Iteration:** repetition using loops (FOR, WHILE)

### Q: What is testing in software development?
**A:** The process of finding errors and verifying software meets requirements. Types:
- **Unit testing:** individual components
- **Integration testing:** components together
- **System testing:** entire system
- **Acceptance testing:** meets user needs

---

## ⚖️ Category 10: Legal, Moral, Ethical & Cultural Issues

### Q: What is the Data Protection Act?
**A:** UK law governing how personal data is processed and stored. Key principles: data must be used fairly, lawfully, accurately, kept secure, and only for specified purposes. Gives individuals rights over their personal data.

### Q: What is the Computer Misuse Act 1990?
**A:** UK law making it illegal to:
1. Unauthorized access to computer material (hacking)
2. Unauthorized access with intent to commit further offenses
3. Unauthorized modification of computer material (malware, viruses)

Penalties include fines and imprisonment.

### Q: What is the Copyright, Designs and Patents Act 1988?
**A:** UK law protecting intellectual property rights in software, digital media, and creative works. Makes it illegal to copy, modify, or distribute copyrighted material without permission. Protects creators' rights.

### Q: What are open source licenses?
**A:** Licenses allowing software source code to be freely used, modified, and distributed. Examples: GPL, MIT, Apache. Benefits: community collaboration, transparency, free to use. Examples: Linux, Firefox, Python.

### Q: What are proprietary licenses?
**A:** Licenses where software source code is kept private and usage is restricted. Users typically pay for licenses. Vendor controls updates and features. Examples: Windows, Microsoft Office, Adobe Photoshop.

### Q: What are ethical issues in computing?
**A:** Questions about right and wrong behavior:
- Privacy invasion (surveillance, data collection)
- Security responsibilities
- Algorithmic bias and fairness
- AI decision-making accountability
- Digital divide and access inequality
- Environmental impact

### Q: What are cultural issues in computing?
**A:** How technology affects different cultures and societies:
- Language barriers in software
- Cultural representation in AI/algorithms
- Global vs local censorship
- Digital cultural preservation
- Different privacy expectations across cultures
- Technology adoption rates

### Q: What are environmental issues in computing?
**A:** Technology's impact on the environment:
- E-waste from discarded devices
- Energy consumption of data centers
- Carbon footprint of manufacturing
- Non-renewable resource use
- Solutions: recycling programs, energy-efficient design, cloud optimization

### Q: What is the digital divide?
**A:** The gap between those with access to modern technology/internet and those without. Factors: income, geography, age, education. Creates inequality in opportunities for education, employment, services, and information access.

### Q: What are privacy concerns in modern computing?
**A:** Issues around personal data collection and use:
- Social media data harvesting
- Location tracking
- Targeted advertising
- Data breaches
- Government surveillance
- Facial recognition
- Cookies and online tracking

### Q: What is cybersecurity?
**A:** Protecting computer systems, networks, and data from theft, damage, or unauthorized access. Involves:
- Strong passwords and authentication
- Encryption
- Firewalls and antivirus
- Regular updates
- User education
- Backup systems

---

## 🔢 Category 11: Boolean Algebra & Logic

### Q: What is Boolean algebra?
**A:** A mathematical system for manipulating logical values (True/False, 1/0) using logical operations. Fundamental to digital circuit design and computer logic. Named after George Boole.

### Q: What is the AND operation?
**A:** A logical operation that returns True only if both inputs are True.
Symbol: ∧ or •

**Truth table:**
- 0 AND 0 = 0
- 0 AND 1 = 0
- 1 AND 0 = 0
- 1 AND 1 = 1

### Q: What is the OR operation?
**A:** A logical operation that returns True if at least one input is True.
Symbol: ∨ or +

**Truth table:**
- 0 OR 0 = 0
- 0 OR 1 = 1
- 1 OR 0 = 1
- 1 OR 1 = 1

### Q: What is the NOT operation?
**A:** A logical operation that inverts the input (returns opposite value).
Symbol: ¬ or bar over variable

**Truth table:**
- NOT 0 = 1
- NOT 1 = 0

### Q: What is the XOR operation?
**A:** Exclusive OR - returns True if inputs are different.
Symbol: ⊕

**Truth table:**
- 0 XOR 0 = 0
- 0 XOR 1 = 1
- 1 XOR 0 = 1
- 1 XOR 1 = 0

### Q: What is a logic gate?
**A:** An electronic circuit that performs a Boolean operation on input signals to produce an output. Building blocks of digital circuits. Types: AND, OR, NOT, NAND, NOR, XOR gates.

### Q: What is a truth table?
**A:** A table showing all possible input combinations and their corresponding outputs for a logical expression or circuit. Used to analyze and design logic circuits.

### Q: What is De Morgan's Law?
**A:** Rules for simplifying Boolean expressions:
1. NOT(A AND B) = NOT A OR NOT B
2. NOT(A OR B) = NOT A AND NOT B

Useful for circuit simplification and optimization.

---

## 📚 Category 12: Data Structures

### Q: What is an array?
**A:** A data structure storing multiple values of the same data type in contiguous memory locations, accessed by index. Fixed size, fast access (O(1)), index starts at 0 in most languages. Example: scores[0], scores[1], scores[2]

### Q: What are the advantages of arrays?
**A:**
1. Fast access to elements using index (O(1))
2. Memory efficient for fixed-size data
3. Simple to use and understand
4. Good cache locality (elements stored together)

### Q: What are the disadvantages of arrays?
**A:**
1. Fixed size - cannot grow/shrink
2. Insertion/deletion is slow (requires shifting)
3. Memory waste if not full
4. All elements must be same type

### Q: What is a record/struct?
**A:** A data structure that groups related data items of different types under one name. Each item is called a field. Example: Student record with name (string), age (integer), grade (char).

### Q: What is a list?
**A:** A dynamic data structure storing ordered elements that can grow/shrink. Unlike arrays, size is flexible. Elements accessed by index. Supports insertion, deletion, searching. Can be implemented as array or linked list.

### Q: What is a stack?
**A:** A Last-In-First-Out (LIFO) data structure. Elements added and removed from the same end (top).

**Operations:**
- **Push:** add to top
- **Pop:** remove from top
- **Peek:** view top without removing

**Uses:** function calls, undo operations, expression evaluation

### Q: What is a queue?
**A:** A First-In-First-Out (FIFO) data structure. Elements added at rear, removed from front.

**Operations:**
- **Enqueue:** add to rear
- **Dequeue:** remove from front
- **Peek:** view front

**Uses:** printer queues, task scheduling, breadth-first search

### Q: What is a circular queue?
**A:** A queue implementation where the last position connects back to the first position, forming a circle. Efficiently uses fixed memory space by wrapping around. Prevents wasted space in linear queue implementation.

### Q: What is a linked list?
**A:** A data structure where elements (nodes) are stored non-contiguously, each containing data and a pointer/reference to the next node. Dynamic size, efficient insertion/deletion, but slower access (O(n)). Types: singly, doubly, circular.

---

## 🧮 Category 13: Algorithms

### Q: What is an algorithm?
**A:** A step-by-step sequence of instructions or rules for solving a problem or completing a task. Must be: unambiguous, executable, finite (terminates). Can be represented using pseudocode, flowcharts, or code.

### Q: What is computational thinking?
**A:** A problem-solving approach involving:
1. **Decomposition** - breaking problems into smaller parts
2. **Pattern recognition** - identifying similarities
3. **Abstraction** - focusing on important details
4. **Algorithm design** - creating step-by-step solutions

### Q: What is linear search?
**A:** A searching algorithm that checks each element sequentially until target is found or end is reached.

**Time complexity:** O(n)
**Advantages:** works on unsorted data, simple
**Disadvantages:** slow for large datasets

### Q: What is binary search?
**A:** An efficient searching algorithm for sorted data. Repeatedly divides search space in half by comparing target with middle element.

**Time complexity:** O(log n)
**Requires:** sorted data
Much faster than linear search for large datasets

### Q: Describe the binary search algorithm steps
**A:**
1. Find middle element
2. If target equals middle, found!
3. If target < middle, search left half
4. If target > middle, search right half
5. Repeat until found or search space empty

### Q: What is bubble sort?
**A:** A simple sorting algorithm that repeatedly steps through the list, compares adjacent elements and swaps them if in wrong order. Continues until no swaps needed.

**Time complexity:** O(n²)
Simple but inefficient for large datasets

### Q: What is insertion sort?
**A:** A sorting algorithm that builds sorted array one element at a time. Takes each element and inserts it into its correct position in the sorted portion.

**Time complexity:** O(n²)
Efficient for small or nearly-sorted data

### Q: What is merge sort?
**A:** A divide-and-conquer sorting algorithm. Recursively divides array in half, sorts each half, then merges sorted halves.

**Time complexity:** O(n log n)
Stable, predictable, but requires extra memory

### Q: Describe the merge sort algorithm steps
**A:**
1. Divide array into two halves
2. Recursively sort each half
3. Merge the two sorted halves:
   - Compare first elements of each
   - Take smaller, add to result
   - Repeat until all merged

### Q: What is Big O notation?
**A:** A mathematical notation describing algorithm efficiency by analyzing how runtime or space grows with input size (n). Focuses on worst-case scenario.
- **O(1):** constant
- **O(log n):** logarithmic
- **O(n):** linear
- **O(n log n):** linearithmic
- **O(n²):** quadratic

### Q: Compare sorting algorithm efficiency
**A:**
- **Bubble Sort:** O(n²) - slow, simple
- **Insertion Sort:** O(n²) - good for small/nearly-sorted
- **Merge Sort:** O(n log n) - fast, needs extra space
- **Quick Sort:** O(n log n) average - fast, in-place

Best for large data: Merge or Quick Sort

### Q: What is a trace table?
**A:** A table showing how variable values change step-by-step during algorithm execution. Used for:
- Understanding algorithm behavior
- Finding errors
- Tracking loop iterations

Columns: step number, variables, conditions

---

## 📝 Study Tips

1. Review each category systematically
2. Practice drawing diagrams for CPU architecture and fetch-execute cycle
3. Work through binary/hex conversion problems regularly
4. Create your own examples for algorithms and trace them
5. Test yourself by covering answers and trying to recall
6. Focus on understanding concepts, not just memorizing
7. Practice past paper questions to apply knowledge
8. Make connections between related topics (e.g., how registers relate to fetch-execute cycle)

---

## Quick Reference Guide

### CPU Registers:
- **PC** - Program Counter (next instruction address)
- **ACC** - Accumulator (calculation results)
- **MAR** - Memory Address Register (address to access)
- **MDR** - Memory Data Register (data being transferred)
- **CIR** - Current Instruction Register (current instruction)

### Network Protocols:
- **HTTP** - Web pages
- **FTP** - File transfer
- **SMTP** - Email
- **TCP** - Reliable transmission
- **UDP** - Fast transmission
- **IP** - Addressing and routing

### File Calculations:
- **Image:** Width × Height × Color Depth (bits)
- **Sound:** Sample Rate × Bit Depth × Duration × Channels

### Scheduling Algorithms:
- **Round Robin** - Fixed time slices, fair
- **FCFS** - First come first served
- **SJF** - Shortest job first
- **Multi-level** - Multiple priority queues

### Search & Sort Complexity:
- **Linear Search:** O(n)
- **Binary Search:** O(log n) - requires sorted data
- **Bubble/Insertion Sort:** O(n²)
- **Merge Sort:** O(n log n)

---

**Good luck with your studies!** 🎓
