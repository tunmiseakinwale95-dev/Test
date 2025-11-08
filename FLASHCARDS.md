# A Level Computer Science - OCR Specification
## Comprehensive Study Flashcards

## Available Units

### Unit 1: Computer Systems - **175 Flashcards**
File: `cs-alevel-unit1-flashcards.json`

### Unit 2: Algorithms and Programming - **196 Flashcards**
File: `cs-alevel-unit2-flashcards.json`

**Total: 371 Flashcards**

---

# Unit 1: Computer Systems

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

---
---

# Unit 2: Algorithms and Programming

Total Flashcards: **196**

---

## 🧠 Category 1: Computational Thinking

### Q: What is abstraction in computational thinking?
**A:** The process of removing unnecessary detail and complexity from a problem to focus on the essential features. Involves hiding implementation details and showing only functionality. Examples: using functions without knowing internal workings, database views.

### Q: What is decomposition?
**A:** Breaking down a complex problem into smaller, more manageable sub-problems that can be solved individually. Makes large problems easier to understand and solve. Each sub-problem can be solved separately and then combined.

### Q: What is algorithmic thinking?
**A:** Creating a logical sequence of steps to solve a problem. Involves identifying the inputs, processes, and outputs needed. The solution must be clear, unambiguous, and executable.

### Q: What is pattern recognition?
**A:** Identifying similarities, trends, or regularities in data or problems. Helps in reusing solutions from similar problems. Allows for generalization and use of existing algorithms/solutions.

---

## 💻 Category 2: Programming Fundamentals

### Q: What is a subroutine?
**A:** A named block of code that performs a specific task and can be called from other parts of the program. Two types: procedures (perform actions) and functions (return values). Benefits: code reuse, modularity, easier testing and maintenance.

### Q: What is the difference between a procedure and a function?
**A:**
- **Procedure:** executes code but doesn't return a value. Used for performing actions (e.g., print, save file).
- **Function:** executes code AND returns a value. Used for calculations or data transformations (e.g., calculate total, get user input).

### Q: What are parameters?
**A:** Variables listed in the subroutine definition that receive values when the subroutine is called. Allow data to be passed into subroutines. Make subroutines more flexible and reusable.

### Q: What is the difference between local and global variables?
**A:**
- **Local variables:** declared inside a subroutine, only accessible within that subroutine, destroyed when subroutine ends, prevent naming conflicts.
- **Global variables:** declared outside subroutines, accessible throughout the program, persist for program lifetime, can cause unexpected side effects.

### Q: What is parameter passing by value?
**A:** A copy of the argument's value is passed to the parameter. Changes to the parameter inside the subroutine don't affect the original variable. Safer but uses more memory for large data. Default in many languages.

### Q: What is parameter passing by reference?
**A:** The memory address of the argument is passed to the parameter. Changes to the parameter inside the subroutine DO affect the original variable. More memory efficient for large data but can cause unintended side effects.

---

## 🔄 Category 3: Recursion

### Q: What is recursion?
**A:** A programming technique where a subroutine calls itself to solve a problem by breaking it into smaller instances of the same problem. Must have: base case(s) to stop recursion, recursive case(s) that call the function. Alternative to iteration.

### Q: What is a base case in recursion?
**A:** The condition that stops the recursion. Returns a value without making another recursive call. Without a base case, recursion continues infinitely causing stack overflow. Example: in factorial, base case is n = 0 or n = 1.

### Q: Give an example of a recursive algorithm
**A:** **Factorial:**
```
function factorial(n)
  if n <= 1 then
    return 1  // base case
  else
    return n * factorial(n-1)  // recursive case
  end if
end function

factorial(5) = 5 * 4 * 3 * 2 * 1 = 120
```

### Q: What are the advantages of recursion?
**A:**
1. More elegant and readable for certain problems (trees, fractals)
2. Natural fit for recursive data structures
3. Simpler code for complex problems
4. Easier to prove correctness mathematically
5. Good for divide-and-conquer algorithms

### Q: What are the disadvantages of recursion?
**A:**
1. Uses more memory (stack space for each call)
2. Slower than iteration (overhead of function calls)
3. Risk of stack overflow with deep recursion
4. Can be harder to debug
5. Not all problems suit recursive solutions

### Q: What is stack overflow?
**A:** An error that occurs when the call stack runs out of memory, typically from excessive recursion without reaching base case or too deep recursion. Crashes the program. Can be avoided with proper base cases and tail recursion optimization.

---

## 📦 Category 4: Abstract Data Types

### Q: What is an abstract data type (ADT)?
**A:** A theoretical concept that defines a data type by its behavior (operations) rather than its implementation. Specifies what operations can be performed but not how they are implemented. Examples: Stack, Queue, List, Dictionary. Implementation details are hidden.

### Q: What is a stack ADT?
**A:** A Last-In-First-Out (LIFO) abstract data type.

**Operations:** push(item), pop(), peek(), isEmpty()

**Applications:** function calls, undo operations, expression evaluation, backtracking algorithms.

### Q: What is a queue ADT?
**A:** A First-In-First-Out (FIFO) abstract data type.

**Operations:** enqueue(item), dequeue(), peek(), isEmpty()

**Applications:** task scheduling, print queues, breadth-first search, buffer management.

### Q: What is a priority queue?
**A:** A queue where each element has a priority value. Elements with higher priority are dequeued before lower priority elements, regardless of insertion order. Applications: task scheduling, Dijkstra's algorithm, event simulation. Often implemented using heaps.

### Q: What is a dictionary/map ADT?
**A:** An abstract data type storing key-value pairs. Each key is unique and maps to one value.

**Operations:** insert(key, value), get(key), delete(key), containsKey(key)

Also called associative array or hash map. Fast lookups by key.

---

## 🌳 Category 5: Binary Trees

### Q: What is a binary tree?
**A:** A tree data structure where each node has at most two children: left child and right child. Each node contains data, pointer to left child, pointer to right child. Root is the top node. Leaf nodes have no children.

### Q: What is a binary search tree (BST)?
**A:** A binary tree with ordering property: for each node, all values in left subtree are less than node's value, all values in right subtree are greater. Enables efficient searching, insertion, deletion. Average case O(log n) for balanced trees.

### Q: What are the three tree traversal methods?
**A:**
1. **In-order (Left, Root, Right):** visits nodes in ascending order for BST
2. **Pre-order (Root, Left, Right):** useful for copying tree structure
3. **Post-order (Left, Right, Root):** useful for deleting tree or evaluating expressions

### Q: Describe in-order traversal algorithm
**A:**
```
function inOrder(node)
  if node is not null then
    inOrder(node.left)     // traverse left
    visit(node)            // process node
    inOrder(node.right)    // traverse right
  end if
end function
```

For BST: produces values in ascending order

### Q: How do you insert into a binary search tree?
**A:** Start at root. Compare value with current node:
- If less: go left (if left is null, insert here)
- If greater: go right (if right is null, insert here)
- If equal: handle duplicates (reject or increment counter)

Time complexity: O(log n) average, O(n) worst case (unbalanced)

---

## 🕸️ Category 6: Graphs

### Q: What is a graph?
**A:** A data structure consisting of vertices (nodes) connected by edges. Can represent networks, relationships, maps. Components: vertices/nodes, edges/arcs. Can be directed (one-way edges) or undirected (two-way edges).

### Q: What is an adjacency matrix?
**A:** A 2D array representation of a graph where matrix[i][j] = 1 if edge exists from vertex i to j, 0 otherwise. For weighted graphs, stores weight instead of 1. Space: O(V²). Good for dense graphs. Fast edge lookup O(1).

### Q: What is an adjacency list?
**A:** A graph representation where each vertex stores a list of its adjacent vertices. Space: O(V + E). Good for sparse graphs. Slower edge lookup than matrix but more space-efficient. Easier to iterate over neighbors.

### Q: What is depth-first search (DFS)?
**A:** A graph traversal algorithm that explores as far as possible along each branch before backtracking. Uses a stack (or recursion).

**Applications:** detecting cycles, topological sorting, maze solving, finding connected components.

### Q: What is breadth-first search (BFS)?
**A:** A graph traversal algorithm that explores all neighbors at current depth before moving to next depth level. Uses a queue.

**Applications:** shortest path in unweighted graphs, level-order traversal, finding connected components.

### Q: What are the differences between DFS and BFS?
**A:**
- **DFS:** Uses stack, goes deep, less memory for sparse graphs, doesn't find shortest path.
- **BFS:** Uses queue, goes wide, finds shortest path in unweighted graphs, more memory usage.
- **Both:** O(V + E) time complexity, visit all vertices.

---

## 🎯 Category 7: Object-Oriented Programming

### Q: What is object-oriented programming (OOP)?
**A:** A programming paradigm based on objects that contain data (attributes) and code (methods). Key principles: encapsulation, inheritance, polymorphism. Benefits: modularity, reusability, easier maintenance, models real-world entities.

### Q: What is a class?
**A:** A blueprint or template for creating objects. Defines attributes (data) and methods (behavior) that objects of that class will have. Example: Car class with attributes (color, model) and methods (drive, brake). Classes are abstract, objects are concrete.

### Q: What is encapsulation?
**A:** Bundling data and methods that operate on that data within a class, hiding internal details. Uses access modifiers (private, public, protected). Benefits: data protection, implementation hiding, easier to change internal code without affecting external code.

### Q: What are access modifiers?
**A:** Keywords controlling visibility of class members:
- **Public:** accessible from anywhere
- **Private:** only accessible within the class
- **Protected:** accessible within class and subclasses

Good practice: make attributes private, provide public methods (getters/setters)

### Q: What is inheritance?
**A:** Mechanism where a new class (subclass/child) inherits attributes and methods from an existing class (superclass/parent). Enables code reuse and hierarchical classification. Subclass can add new features or override existing ones. Example: Dog inherits from Animal.

### Q: What is polymorphism?
**A:** The ability of objects of different classes to respond to the same method call in different ways. Two types: overriding (runtime) and overloading (compile-time). Enables flexible code. Example: different animals respond differently to speak() method.

### Q: What is method overriding?
**A:** When a subclass provides a specific implementation of a method already defined in its superclass. Same method name, parameters, and return type. Subclass version is called for subclass objects. Example: Dog.speak() overrides Animal.speak().

### Q: What is a constructor?
**A:** A special method called when an object is created. Initializes object attributes. Same name as class, no return type. Can be overloaded. If none defined, default constructor is provided. Example: Car(color, model).

---

## ⚡ Category 8: Algorithm Efficiency & Big O

### Q: What is Big O notation?
**A:** Mathematical notation describing algorithm efficiency by expressing how runtime or space requirements grow with input size n. Focuses on worst-case scenario and growth rate, ignoring constants. Examples: O(1), O(log n), O(n), O(n²).

### Q: What is O(1) - Constant time?
**A:** Algorithm takes same time regardless of input size.

**Examples:** array access by index, hash table lookup (average), push/pop on stack.

Most efficient. Example: return array[5] - always one operation.

### Q: What is O(log n) - Logarithmic time?
**A:** Algorithm runtime increases logarithmically with input size. Doubles input only adds one more operation. Very efficient for large datasets.

**Examples:** binary search, balanced BST operations.

Grows very slowly.

### Q: What is O(n) - Linear time?
**A:** Algorithm runtime increases proportionally with input size. Double input, double time.

**Examples:** linear search, traversing array/list, finding min/max.

Acceptable for most purposes.

### Q: What is O(n log n) - Linearithmic time?
**A:** Algorithm runtime is n multiplied by log n. Common in efficient sorting algorithms.

**Examples:** merge sort, quick sort (average), heap sort.

Good efficiency for sorting. Much better than O(n²).

### Q: What is O(n²) - Quadratic time?
**A:** Algorithm runtime is proportional to square of input size. Often involves nested loops.

**Examples:** bubble sort, insertion sort, selection sort.

Inefficient for large datasets. Double input, quadruple time.

### Q: Compare common Big O complexities
**A:** From best to worst:
```
O(1) < O(log n) < O(n) < O(n log n) < O(n²) < O(2ⁿ) < O(n!)
```

**For n=100:**
- O(1): 1 operation
- O(log n): ~7 operations
- O(n): 100 operations
- O(n²): 10,000 operations
- O(2ⁿ): ~10³⁰ operations

---

## 🔄 Category 9: Sorting Algorithms

### Q: What is bubble sort?
**A:** Simple sorting algorithm that repeatedly steps through list, compares adjacent elements and swaps if in wrong order. Continues until no swaps needed. Called 'bubble' because larger values bubble to the end.

**Time:** O(n²), **Space:** O(1). Stable but inefficient.

### Q: What is insertion sort?
**A:** Builds sorted array one element at a time by inserting each element into its correct position. Like sorting playing cards in your hand.

**Time:** O(n²) worst, O(n) best (already sorted)
**Space:** O(1)

Efficient for small or nearly-sorted data. Stable.

### Q: What is merge sort?
**A:** Divide-and-conquer algorithm that divides array in half recursively, sorts each half, then merges sorted halves. Always O(n log n) time regardless of input.

**Space:** O(n) for temporary arrays.

Stable. Predictable performance. Not in-place.

### Q: What is quick sort?
**A:** Divide-and-conquer algorithm using a pivot to partition array. Elements less than pivot go left, greater go right. Recursively sort partitions.

**Average:** O(n log n)
**Worst:** O(n²)
**Space:** O(log n)

In-place. Unstable. Very fast in practice.

### Q: Compare sorting algorithm complexities
**A:**
- **Bubble Sort:** O(n²) time, O(1) space, stable
- **Insertion Sort:** O(n²) time, O(1) space, stable
- **Merge Sort:** O(n log n) time, O(n) space, stable
- **Quick Sort:** O(n log n) avg, O(n²) worst, O(log n) space, unstable

Best for large data: Merge or Quick Sort

---

## 🔍 Category 10: Searching Algorithms

### Q: What is linear search?
**A:** Simple search algorithm checking each element sequentially until target found or end reached. Works on unsorted data.

**Time:** O(n), **Space:** O(1)

Best case: O(1) if first element. Worst: O(n) if last or not present.

### Q: What is binary search?
**A:** Efficient search for sorted arrays. Repeatedly divides search space in half by comparing target with middle element.

**Time:** O(log n), **Space:** O(1) iterative or O(log n) recursive

Requires sorted data. Much faster than linear for large datasets.

### Q: Compare linear and binary search
**A:**
**Linear Search:**
- ✅ Works on unsorted data
- ✅ Simple to implement
- ✅ Works on any structure
- ❌ O(n) time - slow for large data

**Binary Search:**
- ✅ O(log n) time - very fast
- ✅ Efficient for large datasets
- ❌ Requires sorted data
- ❌ Requires random access

---

## 📁 Category 11: File Handling

### Q: What are the file access modes?
**A:**
- **Read mode ('r'):** open existing file for reading, error if doesn't exist
- **Write mode ('w'):** create new file or overwrite existing
- **Append mode ('a'):** add to end of existing file, create if doesn't exist
- **Read/Write mode ('r+', 'w+', 'a+'):** combination modes

### Q: What is a text file?
**A:** File storing data as human-readable characters using encoding like ASCII or UTF-8. Can be opened in text editor. Examples: .txt, .csv, .json. Lines typically end with newline character. Easy to read but less efficient than binary.

### Q: What is a CSV file?
**A:** Comma-Separated Values file storing tabular data. Each line is a record, commas separate fields. First line often contains headers. Human-readable, widely supported.

**Example:**
```
name,age,grade
Alice,16,A
Bob,17,B
```

### Q: What is JSON?
**A:** JavaScript Object Notation - text format for storing and exchanging data. Uses key-value pairs and arrays. Human-readable, language-independent, supports nested structures. Common for web APIs and config files.

**Example:** `{"name": "Alice", "age": 16}`

---

## ⚠️ Category 12: Exception Handling

### Q: What is exception handling?
**A:** Mechanism for handling runtime errors gracefully without crashing the program. Uses try-catch-finally blocks. Separates error-handling code from normal code. Makes programs more robust and user-friendly.

### Q: What is a try-except block?
**A:**
- **try block:** contains code that might raise an exception
- **except block:** handles the exception if it occurs

Program continues after except block. Can have multiple except blocks for different exception types. Example: try reading file, except handle FileNotFoundError.

### Q: What are common exception types?
**A:**
- **ValueError:** invalid value (e.g., int('abc'))
- **TypeError:** wrong type (e.g., 'a' + 5)
- **ZeroDivisionError:** division by zero
- **IndexError:** index out of range
- **KeyError:** key not in dictionary
- **FileNotFoundError:** file doesn't exist

---

## 🗄️ Category 13: SQL & Databases

### Q: What is SQL?
**A:** Structured Query Language - standard language for managing relational databases. Used to: create/modify database structure, insert/update/delete data, query data. Not case-sensitive. Declarative (say what you want, not how to get it).

### Q: What is a primary key?
**A:** A field (or combination of fields) that uniquely identifies each record in a table. Must be: unique, not null, unchanging. Only one primary key per table. Often an ID number. Ensures entity integrity.

### Q: What is a foreign key?
**A:** A field in one table that references the primary key of another table. Creates relationship between tables. Can be null. Can have multiple foreign keys per table. Ensures referential integrity. Example: StudentID in Enrollment table references Students table.

### Q: What is the SELECT statement?
**A:** Retrieves data from database.

**Syntax:** `SELECT column1, column2 FROM table WHERE condition ORDER BY column`

- `SELECT *` selects all columns
- `WHERE` filters rows
- `ORDER BY` sorts results (ASC/DESC)

**Example:** `SELECT name, age FROM students WHERE age > 16`

### Q: What is a JOIN?
**A:** Combines rows from two or more tables based on related column.

- **INNER JOIN:** returns matching records from both tables
- **LEFT JOIN:** all from left table, matching from right
- **RIGHT JOIN:** all from right table, matching from left

**Example:** `SELECT * FROM students INNER JOIN enrollments ON students.id = enrollments.student_id`

### Q: What are SQL aggregate functions?
**A:** Functions that perform calculations on multiple rows:
- **COUNT():** number of rows
- **SUM():** total of values
- **AVG():** average of values
- **MAX():** largest value
- **MIN():** smallest value

**Example:** `SELECT COUNT(*) FROM students WHERE grade = 'A'`

---

## 🗂️ Category 14: Dictionaries & Hash Tables

### Q: What is a hash table?
**A:** Data structure implementing associative array (dictionary) using hash function to compute index for storing values. Maps keys to values. Average O(1) for insert, delete, search. Also called hash map. Handles collisions using chaining or open addressing.

### Q: What is a hash function?
**A:** Function that converts input (key) into integer (hash code) used as array index. Should be: fast to compute, deterministic (same input → same output), uniform distribution. Good hash function minimizes collisions.

### Q: What is a collision in hash tables?
**A:** When two different keys hash to the same index. Inevitable with finite array size. Handling methods: chaining (linked lists at each index), open addressing (find next available slot). Affects performance - too many collisions degrade to O(n).

---

## 🎨 Category 15: Algorithm Design Techniques

### Q: What is divide and conquer?
**A:** Algorithm design paradigm that breaks problem into smaller subproblems, solves them recursively, then combines solutions. Steps: divide, conquer, combine.

**Examples:** merge sort, quick sort, binary search.

Often uses recursion. Efficient but may have overhead.

### Q: What is dynamic programming?
**A:** Optimization technique that solves complex problems by breaking them into overlapping subproblems, solving each once, and storing results (memoization). Avoids redundant computation.

**Examples:** Fibonacci with memoization, shortest path, knapsack problem.

Bottom-up or top-down approach.

### Q: What is a greedy algorithm?
**A:** Algorithm that makes locally optimal choice at each step hoping to find global optimum. Doesn't reconsider choices. Fast but doesn't always give optimal solution.

**Examples:** Dijkstra's algorithm, Huffman coding, activity selection.

Works when greedy choice property holds.

### Q: What is backtracking?
**A:** Algorithm technique for finding solutions by trying possibilities and abandoning (backtracking) when they fail. Systematic trial and error. Uses recursion.

**Examples:** N-Queens problem, Sudoku solver, maze solving.

Can be slow but guarantees finding solution if one exists.

---

## 📝 Study Tips for Unit 2

1. **Practice writing code** for each algorithm - don't just memorize
2. **Trace through algorithms** with example data to understand how they work
3. **Draw diagrams** for data structures (trees, graphs, stacks, queues)
4. **Understand when to use** each data structure and algorithm
5. **Practice Big O analysis** by counting operations in code
6. **Work through past paper** programming questions
7. **Implement sorting and searching** algorithms from scratch
8. **Understand recursion** by drawing call stacks
9. **Practice SQL queries** with sample databases
10. **Learn to recognize** which algorithm design technique fits each problem
11. **Understand trade-offs:** time vs space, simplicity vs efficiency
12. **Review OOP concepts** with real-world examples

---

## Quick Reference Guide - Unit 2

### Time Complexities:
- **O(1)** - Array access, hash table lookup
- **O(log n)** - Binary search, balanced BST
- **O(n)** - Linear search, array traversal
- **O(n log n)** - Merge sort, quick sort (avg)
- **O(n²)** - Bubble sort, nested loops

### Data Structures:
- **Stack** - LIFO (push, pop, peek)
- **Queue** - FIFO (enqueue, dequeue, peek)
- **BST** - Ordered tree (O(log n) average)
- **Hash Table** - Key-value pairs (O(1) average)
- **Graph** - Vertices + edges (DFS, BFS)

### Tree Traversals:
- **In-order** - Left, Root, Right (ascending in BST)
- **Pre-order** - Root, Left, Right (copy structure)
- **Post-order** - Left, Right, Root (delete tree)

### OOP Principles:
- **Encapsulation** - Hide implementation details
- **Inheritance** - Reuse code from parent class
- **Polymorphism** - Same method, different behaviors

### SQL Basics:
- **SELECT** - Retrieve data
- **INSERT** - Add records
- **UPDATE** - Modify records
- **DELETE** - Remove records
- **JOIN** - Combine tables

---

**Keep practicing and good luck with your A Level exams!** 🎓
