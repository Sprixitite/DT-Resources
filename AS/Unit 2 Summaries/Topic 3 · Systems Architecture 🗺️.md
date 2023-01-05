# Topic 3 · Systems Architecture 🗺️

This topic covers the architecture of computers and the internal and external components that are used such as serial ports, buses, registers, memory and the CPU. It also explains how these components work together to enable the computer to operate, such as the fetch-decode-execute cycle, control and data buses, arithmetic logic and control units.

**These notes are written by James Wilkinson, assisted by Craft AI.**

----

### Architecture

Computer systems typically consist of three main components ⬇

- **The CPU →** Processes data and executes instructions.
- **The Memory →** Holds programs and data that are actively being used.
- **The I/O →** Used for communication with the outside world.

#### **Central Processing Unit**

The brains of the computer; a component which contains a control unit, a algorithmic and logic unit, and registers. It usually also will contain some form of internal main memory.

> **Control Unit →** This component controls the sequencing of instructions to be executed within a program; controlling the movement of data; managing the loops/jumps in the program; managing the fetch-decode-execute cycle; and sending control and timing signals to other components within the system.

> **Arithmetic Logic Unit →** This component controls the calculation of all mathematical calculations; managing the execution of logical comparisons; and the resolving boolean expressions within programs.

#### **Memory**

> **Main Memory →** This type of memory is apart of the internal memory, and is always instantly accessible; made up from **R**andom **A**ccess **M**emory (**RAM**) / Volatile Memory.

> **Random Access Memory →** Volatile, temporary memory that has instant access to all memory locations, used to store programs, files and parts of the OS which are currently being used.

> **Read Only Memory →** Permanent memory where its contents can be read but not overwritten; commonly used to hold the bootstrap loaders, which is a small program that loads the OS into RAM.

> **Cache Memory →** High speed, volatile memory that sits on the processor chip itself, stores copies of frequeuntly/recently executed instructions and opened files. The processor will search the cache memory before querying the larger but slower, main memory.

### Fetch → (Decode) → Execute Cycle

The fetch-execute cycle is the process used by a computer to retrieve a program instruction from memory, determine how that instruction is executed, and then carry out the actions associated with that instruction.

There are three steps to this process ⬇

- **Fetch →** The next instructions is *fetched* from memory into the control unit.
- **Decode →** The instruction is then *decoded* to determine the actions to be carried out.
- **Execute →** The action is then carried out and *executed*.

### Registers

A high-speed memory location on the CPU where data or control information is stored temporarily before it is acted upon. They have an important role in the Fetch-Execute Cycle, as they are much faster to access than internal memory, since they have to be accessed so often.

A CPU contains many registers some of which will be reserved for specific purpose whilst others are used for general purpose calculations. A register is a small block of memory, normally about 4/8 bytes, which is used in order for instructions to be processed.

**Machine instructions can only work if they are loaded into registers.**

> **PC →** Stores the address/location in memory of the next program instruction to be executed. As soon as an instruction has been fetched from memory the contents of the program counter are incremented to ensure it points to the next location to be executed.

> **MAR →** Stores the address of a memory location to be accessed either for a R/W operation.

> **MDR →** Stores data that has just been fetched from the memory or data waiting to be written.

> **CIR →** Stores the instruction currently being executed by the processor.

### Buses

A bus is a set of physical connections in the form of a set of physical cables or printed circuits used to connect the various hardware components together in order to pass data, control and address signals between them.

There are three types of buses: the memory, data & control buses. All of which must connect to the CPU so that it can communicate and control with the other various components in the system.

> **Address Bus →** Uni-directional bus used to identify a physical location in memory to be accessed. This may be to either access or write data to memory.

> **Data Bus →** Bi-directional bus used to transfer data between one component of a processor or computer system and another.

> **Control Bus →** Bi-directional bus used to carry commands from the CPU to other devices in relation to the instruction being executed at a particular time.

### Ports & The I/O Controller

Ports allow data to be transferred from input/output devices to the internal components within the computer. This can only happen when the external component is connected to an I/O Ports.

> **Serial Port →** Transmits one bits of data at a time across a single wire, which is used mainly for connected to mice and modems. It is best for long distance communication as it only needs one signal pathway each-way, making it easy to regenerate the signal.

> **Parallel Port →** Transmits multiple bits of data at the same time across multiple wires. This type of port is usually used for connecting to printers, as it can transmit larger amounts of data faster than the Serial Port.

> **USB (Universal Serial Bus) →** A high speed serial port alternative, which is commonly used for connecting peripherals such as keyboards, mice and cameras to the computer. USB ports are very popular due to their built-in power supply and widespread availability.

The I/O controller handles all communication between the internal components and any external components connected via ports. It also screens data to ensure that it is in the correct format to be sent to other components in the system.

### **Factors Affecting Performance**

There are a number of factors that can affect the performance of a computer system, including the clock speed, the core count and memory size and type.

> **Clock Speed** → The speed at which the microprocessor can process instructions is measured in Megahertz or Gigahertz. The higher the speed, the faster the instructions can be processed.

> **Processor Cores →** The amount of cores a CPU has, the more instructions it can execute simultaneously. The more cores you have, the faster instructions can be processed. However, if programs isn't designed to take advantage of these extra cores, the benefit will be minimal.

> **Memory Size and Type →** Different types of memory can be used in computers, such as RAM and ROM. The larger the size of the memory, the more data the computer can hold and process.

### Secondary Storage Devices

Secondary storage devices are used to store large amounts of data and programs in a way that is non-volatile, meaning that the data is still present after the computer is turned off. Secondary storage include magnetic, solid state, and optical mediums of storage.

> **Magnetic** → Magnetic storage devices use magnetism to store data, and are the most widely used type of secondary storage device. Examples of these include hard drives, floppy disks, and magnetic tape.

> **Solid State →** Solid state storage devices use integrated circuits containing semiconductors and are used as an alternative to traditional magnetic storage. Examples of these include solid state drives, USB flash drives, and flash memory cards.

> **Optical →** Optical storage devices use laser technology to store data on an optical medium, such as a CD, DVD, or Blu-Ray disc. These discs can store large amounts of data and are often used for applications such as watching movies or storing data backups.

