# ing10x

> Attempting to master coding through practice. Implementing each project in multiple languages to profit from associative memory. 

A curated collection of **400+ programming projects** across 7 domains, designed to be implemented in **Go, Python, C, Rust, Java, C++, and Dart**. Each project is small enough to complete in a few hours but meaningful enough to teach real concepts.

## Repository Structure

```
10x/
├── cli/                    # Command Line Interface Projects
├── paradigms/              # OOP, Functional & Design Patterns
├── security/               # Hacking, Forensics & Security
├── systems/                # Systems Programming
├── embedded/               # Embedded Systems & IoT
├── distributed/            # Distributed Systems
└── web-api/                # Web & API Development
```

Each project follows this structure:
```
ing10x/domain/category/project-name/
├── go/
├── python/
├── c/
├── rust/
├── java/
├── cpp/
└── dart/
```

---

## CLI Projects

Command-line tools and utilities for everyday tasks.

### Basics
| # | Project | Description |
|---|---------|-------------|
| 1 | `word-counter` | Read file/stdin, count words, lines, characters (like wc) |
| 2 | `todo-list` | Add, list, complete, delete tasks stored in a JSON file |
| 3 | `unit-converter` | Temperature, length, weight conversions with flag parsing |
| 4 | `password-generator` | Configurable length, character sets, number of passwords |
| 5 | `calculator` | Parse and evaluate mathematical expressions from input |
| 6 | `flashcard-quiz` | Load Q&A from file, quiz user, track score |

### File & Text Processing
| # | Project | Description |
|---|---------|-------------|
| 1 | `log-parser` | Filter log files by date, level, or regex pattern |
| 2 | `duplicate-finder` | Hash files and report duplicates in a directory tree |
| 3 | `markdown-to-html` | Simple converter using parsing or regex |
| 4 | `csv-to-json` | Transform between formats with column filtering |
| 5 | `file-renamer` | Batch rename files using patterns or regex |
| 6 | `text-search` | Search for patterns in files with line numbers (grep clone) |
| 7 | `config-parser` | Read/write INI, YAML, or TOML configuration files |

### Networking & APIs
| # | Project | Description |
|---|---------|-------------|
| 1 | `url-shortener-client` | Interact with a URL shortening API |
| 2 | `weather-cli` | Fetch and display weather from a public API |
| 3 | `http-status-checker` | Check if a list of URLs are reachable (concurrency practice) |
| 4 | `rest-client` | Generic tool to make GET/POST requests with headers |
| 5 | `dns-lookup` | Resolve domain names to IP addresses |
| 6 | `download-manager` | Download files with progress bar and resume support |
| 7 | `ip-geolocation` | Look up geographic info for IP addresses via API |

### System Tools
| # | Project | Description |
|---|---------|-------------|
| 1 | `process-monitor` | List running processes, filter by name or resource usage |
| 2 | `disk-usage` | Recursive directory size calculator (like du) |
| 3 | `cron-parser` | Show next N execution times for a cron expression |
| 4 | `port-scanner` | Scan a range of ports on a host (concurrency practice) |
| 5 | `system-info` | Display CPU, memory, disk, and OS information |
| 6 | `file-watcher` | Monitor directory for changes and trigger actions |
| 7 | `env-manager` | Manage and switch between env variable profiles |

### Data & Databases
| # | Project | Description |
|---|---------|-------------|
| 1 | `sqlite-cli` | Create tables, insert, query, and export data from SQLite |
| 2 | `json-query` | Query JSON files using path expressions (like jq) |
| 3 | `data-validator` | Validate CSV/JSON against a schema definition |
| 4 | `backup-tool` | Incremental backup with compression and checksums |
| 5 | `contact-book` | Store and search contacts with SQLite backend |

### Security & Cryptography
| # | Project | Description |
|---|---------|-------------|
| 1 | `hash-calculator` | Compute MD5, SHA256, etc. for files or strings |
| 2 | `file-encryptor` | Encrypt/decrypt files with AES using a password |
| 3 | `password-vault` | Encrypted local storage for credentials |
| 4 | `jwt-decoder` | Parse and validate JSON Web Tokens |
| 5 | `checksum-verifier` | Verify file integrity against known checksums |

### Text & Content Generation
| # | Project | Description |
|---|---------|-------------|
| 1 | `lorem-generator` | Generate placeholder text with word/paragraph count |
| 2 | `ascii-art` | Convert text to ASCII art banners |
| 3 | `diff-tool` | Compare two files and show differences |
| 4 | `spell-checker` | Check spelling against a dictionary file |
| 5 | `slug-generator` | Convert titles to URL-friendly slugs |

### Productivity
| # | Project | Description |
|---|---------|-------------|
| 1 | `pomodoro-timer` | CLI timer with notifications or terminal output |
| 2 | `git-stats` | Parse git log and show commit statistics per author |
| 3 | `expense-tracker` | Track spending with categories, monthly summaries |
| 4 | `habit-tracker` | Log daily habits and show streaks/statistics |
| 5 | `clipboard-manager` | Store and recall clipboard history |
| 6 | `note-taker` | Quick notes with tags, search, and export |
| 7 | `time-tracker` | Track time spent on projects/tasks |

### Terminal Games
| # | Project | Description |
|---|---------|-------------|
| 1 | `hangman` | Word guessing game with ASCII graphics |
| 2 | `number-guessing` | Binary search game with hints |
| 3 | `tic-tac-toe` | Two-player or vs simple AI |
| 4 | `snake` | Classic snake game with ncurses/terminal graphics |
| 5 | `2048` | Sliding tile puzzle in the terminal |
| 6 | `wordle-clone` | Daily word puzzle with colored feedback |
| 7 | `minesweeper` | Classic grid-based puzzle game |

### DevOps & Automation
| # | Project | Description |
|---|---------|-------------|
| 1 | `docker-stats` | Display container resource usage in real-time |
| 2 | `ssh-config-manager` | Manage and switch SSH configurations |
| 3 | `health-checker` | Monitor uptime of multiple services |
| 4 | `log-rotator` | Archive and compress old log files automatically |
| 5 | `deploy-script` | Automate build, test, deploy workflow |

---

## Paradigms Projects

Object-oriented programming, functional programming, design patterns, and computer science fundamentals.

### OOP Fundamentals
| # | Project | Description |
|---|---------|-------------|
| 1 | `shape-hierarchy` | Abstract Shape class with Circle, Rectangle, Triangle subclasses |
| 2 | `bank-account` | Account base class, Savings/Checking with inheritance |
| 3 | `vehicle-fleet` | Vehicle -> Car, Truck, Motorcycle with polymorphism |
| 4 | `employee-management` | Employee types with salary calculation override |
| 5 | `media-library` | Book, Movie, Music classes with common interface |

### OOP Design Patterns
| # | Project | Description |
|---|---------|-------------|
| 1 | `singleton-logger` | Thread-safe singleton pattern for logging |
| 2 | `factory-pattern` | Document factory creating PDF, Word, HTML objects |
| 3 | `observer-pattern` | Event system with subscribers and publishers |
| 4 | `strategy-pattern` | Payment processor with multiple payment strategies |
| 5 | `decorator-pattern` | Coffee shop with add-on decorators (milk, sugar) |
| 6 | `builder-pattern` | Complex object construction (House, Computer builder) |

### Functional Programming Basics
| # | Project | Description |
|---|---------|-------------|
| 1 | `map-filter-reduce` | Process collections without loops using HOFs |
| 2 | `pure-functions` | Refactor imperative code to pure functions |
| 3 | `immutable-data` | Data transformations without mutation |
| 4 | `function-composition` | Compose small functions into pipelines |
| 5 | `currying-partial` | Implement curry and partial application |

### Functional Programming Projects
| # | Project | Description |
|---|---------|-------------|
| 1 | `expression-parser` | Parse and evaluate math expressions functionally |
| 2 | `json-transformer` | Transform nested JSON using pure functions |
| 3 | `validation-library` | Composable validators with monadic error handling |
| 4 | `state-machine` | Functional state machine for workflow |
| 5 | `event-sourcing` | Rebuild state from event log using reduce |

### Data Structures
| # | Project | Description |
|---|---------|-------------|
| 1 | `linked-list` | Singly/doubly linked list with all operations |
| 2 | `stack-queue` | Array and linked-list based implementations |
| 3 | `binary-tree` | BST with insert, delete, search, traversals |
| 4 | `hash-table` | Hash map with collision handling |
| 5 | `heap` | Min/max heap with heapify operations |
| 6 | `graph` | Adjacency list/matrix with BFS, DFS, shortest path |

### Algorithms
| # | Project | Description |
|---|---------|-------------|
| 1 | `sorting` | Quick, merge, heap, radix sort implementations |
| 2 | `searching` | Binary search, interpolation, exponential search |
| 3 | `dynamic-programming` | Knapsack, LCS, coin change, edit distance |
| 4 | `graph-algorithms` | Dijkstra, A*, Bellman-Ford, topological sort |
| 5 | `string-algorithms` | KMP, Rabin-Karp, longest palindrome |

### Concurrency & Parallelism
| # | Project | Description |
|---|---------|-------------|
| 1 | `producer-consumer` | Thread-safe queue with multiple workers |
| 2 | `thread-pool` | Fixed-size pool executing task queue |
| 3 | `dining-philosophers` | Classic deadlock avoidance problem |
| 4 | `parallel-map` | Parallel version of map over large dataset |
| 5 | `async-fetcher` | Concurrent URL fetching with rate limiting |
| 6 | `actor-model` | Simple actor system with message passing |

### Testing & Code Quality
| # | Project | Description |
|---|---------|-------------|
| 1 | `test-framework` | Build mini test framework with assertions |
| 2 | `mock-objects` | Create mock/stub objects for dependencies |
| 3 | `property-tests` | Generate random inputs to test properties |
| 4 | `coverage-tool` | Track which lines of code are executed |

### Metaprogramming & Reflection
| # | Project | Description |
|---|---------|-------------|
| 1 | `object-serializer` | Serialize any object to JSON using reflection |
| 2 | `dependency-injection` | Simple DI container with auto-wiring |
| 3 | `orm-mapper` | Map objects to database tables automatically |
| 4 | `plugin-system` | Load and execute plugins at runtime |

### Memory & Performance
| # | Project | Description |
|---|---------|-------------|
| 1 | `memory-pool` | Pre-allocated object pool to reduce allocations |
| 2 | `lru-cache` | Least recently used cache with O(1) operations |
| 3 | `profiler` | Measure function execution time and call counts |
| 4 | `bloom-filter` | Probabilistic set membership data structure |

### Interpreters & Language Tools
| # | Project | Description |
|---|---------|-------------|
| 1 | `lexer` | Break source code into tokens |
| 2 | `expression-evaluator` | Parse and evaluate arithmetic expressions |
| 3 | `mini-interpreter` | Interpret simple language with variables, loops |
| 4 | `regex-engine` | Basic regex matcher from scratch |

---

## Security Projects

Ethical hacking, penetration testing, forensics, and security tools.

### Network Reconnaissance
| # | Project | Description |
|---|---------|-------------|
| 1 | `port-scanner` | TCP/UDP port scanner with service detection |
| 2 | `network-mapper` | Discover hosts on network using ARP/ICMP |
| 3 | `banner-grabber` | Extract service banners from open ports |
| 4 | `subdomain-enum` | Brute-force and DNS enumeration for subdomains |
| 5 | `whois-lookup` | Query domain registration and IP info |

### Packet Capture & Analysis
| # | Project | Description |
|---|---------|-------------|
| 1 | `packet-sniffer` | Capture and parse raw network packets |
| 2 | `protocol-analyzer` | Decode HTTP, DNS, TCP headers from pcap |
| 3 | `arp-monitor` | Detect ARP spoofing attacks on network |
| 4 | `traffic-logger` | Log all connections with timestamps |
| 5 | `dns-sniffer` | Capture and log DNS queries on network |

### Web Application Security
| # | Project | Description |
|---|---------|-------------|
| 1 | `sqli-scanner` | Detect SQL injection vulnerabilities in parameters |
| 2 | `xss-detector` | Find reflected/stored XSS in web apps |
| 3 | `dir-bruteforcer` | Discover hidden paths and files |
| 4 | `header-analyzer` | Check security headers (CSP, HSTS, etc.) |
| 5 | `cookie-inspector` | Analyze cookie flags and security |
| 6 | `form-fuzzer` | Fuzz input fields with payloads |

### Password & Crypto Attacks
| # | Project | Description |
|---|---------|-------------|
| 1 | `hash-cracker` | Dictionary/brute-force attack on hashes |
| 2 | `rainbow-table` | Generate and lookup precomputed hashes |
| 3 | `weak-crypto-detector` | Identify weak algorithms (MD5, DES, RC4) |
| 4 | `padding-oracle` | Implement CBC padding oracle attack |
| 5 | `timing-attack` | Side-channel attack on string comparison |

### Exploitation Fundamentals
| # | Project | Description |
|---|---------|-------------|
| 1 | `buffer-overflow` | Stack-based overflow with shellcode injection |
| 2 | `format-string` | Exploit printf vulnerabilities |
| 3 | `rop-chain` | Return-oriented programming gadget finder |
| 4 | `heap-spray` | Heap manipulation technique demo |
| 5 | `use-after-free` | Demonstrate UAF vulnerability |

### Reverse Engineering
| # | Project | Description |
|---|---------|-------------|
| 1 | `disassembler` | Convert binary to assembly instructions |
| 2 | `pe-elf-parser` | Parse executable file formats |
| 3 | `string-extractor` | Extract readable strings from binaries |
| 4 | `api-tracer` | Log system/library calls at runtime |
| 5 | `deobfuscator` | Remove simple obfuscation from code |

### Malware Analysis (Defensive)
| # | Project | Description |
|---|---------|-------------|
| 1 | `sandbox-detector` | Detect VM/sandbox environment |
| 2 | `behavior-monitor` | Track file/registry/network activity |
| 3 | `yara-scanner` | Match files against YARA rules |
| 4 | `static-analyzer` | Extract IOCs from suspicious files |
| 5 | `hollowing-detector` | Detect process injection techniques |

### Digital Forensics
| # | Project | Description |
|---|---------|-------------|
| 1 | `file-carver` | Recover deleted files from disk images |
| 2 | `metadata-extractor` | Extract EXIF, PDF, Office metadata |
| 3 | `timeline-builder` | Create filesystem activity timeline |
| 4 | `memory-analyzer` | Parse process memory dumps |
| 5 | `log-correlator` | Correlate events from multiple log sources |
| 6 | `registry-analyzer` | Extract artifacts from Windows registry |

### Steganography
| # | Project | Description |
|---|---------|-------------|
| 1 | `lsb-stego` | Hide data in image least significant bits |
| 2 | `stego-detector` | Detect hidden data in images |
| 3 | `audio-stego` | Hide messages in audio files |
| 4 | `file-in-file` | Embed files inside other files |

### OSINT
| # | Project | Description |
|---|---------|-------------|
| 1 | `email-hunter` | Find emails associated with domain |
| 2 | `username-search` | Check username across platforms |
| 3 | `metadata-scraper` | Extract metadata from public documents |
| 4 | `social-recon` | Gather public social media info |
| 5 | `breach-checker` | Check if credentials in known breaches |

### Wireless Security
| # | Project | Description |
|---|---------|-------------|
| 1 | `wifi-scanner` | Discover and list nearby access points |
| 2 | `deauth-detector` | Detect deauthentication attacks |
| 3 | `handshake-capture` | Capture WPA handshakes for analysis |
| 4 | `rogue-ap-detector` | Identify unauthorized access points |

### CTF Tools
| # | Project | Description |
|---|---------|-------------|
| 1 | `flag-submitter` | Auto-submit flags to CTF platforms |
| 2 | `encoding-toolkit` | Base64, hex, rot13, URL encode/decode |
| 3 | `cipher-solver` | Break Caesar, Vigenere, substitution |
| 4 | `pwn-template` | Exploit development template with pwntools |

---

## Systems Programming

Low-level systems, operating system concepts, and system utilities.

### Memory Management
| # | Project | Description |
|---|---------|-------------|
| 1 | `custom-allocator` | Implement malloc/free with different strategies |
| 2 | `memory-pool` | Fixed-size block allocator for performance |
| 3 | `garbage-collector` | Mark-and-sweep or reference counting GC |
| 4 | `smart-pointers` | Implement unique_ptr, shared_ptr, weak_ptr |
| 5 | `memory-debugger` | Detect leaks, double-free, buffer overflows |

### Process & Thread Management
| # | Project | Description |
|---|---------|-------------|
| 1 | `process-spawner` | Fork/exec with IPC pipes |
| 2 | `thread-pool` | Worker threads with task queue |
| 3 | `scheduler-sim` | Round-robin, priority, MLFQ scheduling |
| 4 | `signal-handler` | Custom signal handling and propagation |
| 5 | `daemon-process` | Background service with PID file, logging |

### Shell & Terminal
| # | Project | Description |
|---|---------|-------------|
| 1 | `mini-shell` | Command parsing, execution, pipes, redirects |
| 2 | `job-control` | Background jobs, fg/bg, process groups |
| 3 | `terminal-emulator` | PTY handling, escape sequences |
| 4 | `repl-framework` | Read-eval-print loop with history |
| 5 | `autocomplete` | Tab completion with trie-based suggestions |

### Filesystem & Storage
| # | Project | Description |
|---|---------|-------------|
| 1 | `virtual-filesystem` | VFS layer with multiple backends |
| 2 | `fat-reader` | Parse and read FAT filesystem images |
| 3 | `fuse-filesystem` | Userspace filesystem (encrypted, compressed) |
| 4 | `file-watcher` | inotify/kqueue based change detection |
| 5 | `journaling` | Write-ahead logging for crash recovery |
| 6 | `disk-cache` | LRU block cache with write-back |

### Low-Level Networking
| # | Project | Description |
|---|---------|-------------|
| 1 | `raw-sockets` | Send/receive raw Ethernet frames |
| 2 | `tcp-stack` | Implement TCP state machine from scratch |
| 3 | `udp-server` | High-performance UDP with epoll/kqueue |
| 4 | `icmp-ping` | Implement ping using raw ICMP |
| 5 | `arp-impl` | Address resolution protocol |
| 6 | `network-bridge` | Layer 2 bridge between interfaces |

### IPC & Synchronization
| # | Project | Description |
|---|---------|-------------|
| 1 | `shared-memory` | POSIX shm with synchronization |
| 2 | `message-queue` | Inter-process message passing |
| 3 | `named-pipes` | FIFO-based communication |
| 4 | `semaphores` | Counting and binary semaphores |
| 5 | `lock-free-queue` | Atomic operations, CAS-based queue |
| 6 | `rpc-framework` | Remote procedure call implementation |

### Device Interaction
| # | Project | Description |
|---|---------|-------------|
| 1 | `serial-port` | UART communication library |
| 2 | `usb-hid` | Read/write USB HID devices |
| 3 | `framebuffer` | Direct framebuffer graphics |
| 4 | `input-events` | Read keyboard/mouse via evdev |
| 5 | `pseudo-device` | Create /dev entries with read/write |

### Binary & Executable Formats
| # | Project | Description |
|---|---------|-------------|
| 1 | `elf-parser` | Parse ELF headers, sections, symbols |
| 2 | `elf-loader` | Load and execute ELF binaries |
| 3 | `static-linker` | Link object files into executable |
| 4 | `dynamic-loader` | Implement ld.so functionality |
| 5 | `symbol-resolver` | Resolve symbols at runtime |

### Kernel Concepts (Userspace)
| # | Project | Description |
|---|---------|-------------|
| 1 | `syscall-wrapper` | Wrap raw syscalls with safe interface |
| 2 | `context-switcher` | Userspace coroutine context switch |
| 3 | `page-table-sim` | Simulate virtual memory mapping |
| 4 | `interrupt-handler` | Signal-based interrupt simulation |
| 5 | `boot-sequence` | Simulate kernel boot initialization |

### Debugging & Tracing
| # | Project | Description |
|---|---------|-------------|
| 1 | `debugger` | ptrace-based debugger with breakpoints |
| 2 | `strace-clone` | Trace system calls of process |
| 3 | `profiler` | CPU sampling profiler with flamegraphs |
| 4 | `coredump-analyzer` | Parse and analyze core dumps |
| 5 | `ebpf-tracer` | Kernel tracing with eBPF (Linux) |

### Virtualization & Containers
| # | Project | Description |
|---|---------|-------------|
| 1 | `container-runtime` | Namespaces, cgroups, minimal container |
| 2 | `hypervisor-sim` | Basic VM monitor concepts |
| 3 | `chroot-jail` | Process isolation with chroot |
| 4 | `seccomp-filter` | Syscall filtering sandbox |

---

## Embedded & IoT

Embedded systems, microcontrollers, sensors, and Internet of Things.

### GPIO & Basic I/O
| # | Project | Description |
|---|---------|-------------|
| 1 | `led-blinker` | Basic GPIO output with timing control |
| 2 | `button-debounce` | Hardware/software debouncing techniques |
| 3 | `pwm-controller` | Software/hardware PWM for LED dimming, motors |
| 4 | `rotary-encoder` | Read quadrature encoder with interrupts |
| 5 | `keypad-matrix` | Scan matrix keypad with row/column multiplexing |

### Communication Protocols
| # | Project | Description |
|---|---------|-------------|
| 1 | `i2c-driver` | Bit-bang or hardware I2C implementation |
| 2 | `spi-driver` | Full-duplex SPI with multiple slaves |
| 3 | `uart-library` | Serial communication with buffering, flow control |
| 4 | `onewire` | Dallas 1-Wire for temperature sensors |
| 5 | `can-bus` | Automotive CAN communication |
| 6 | `modbus` | Industrial protocol master/slave |

### Sensor Interfaces
| # | Project | Description |
|---|---------|-------------|
| 1 | `temp-logger` | DHT22, DS18B20, or I2C temp sensors |
| 2 | `imu-reader` | Accelerometer + gyroscope (MPU6050) |
| 3 | `gps-parser` | NMEA sentence parsing, coordinate extraction |
| 4 | `ultrasonic` | HC-SR04 distance measurement |
| 5 | `adc-sampling` | Analog sensor reading with averaging, filtering |
| 6 | `barometer` | BMP280 pressure/altitude calculation |

### Actuators & Motor Control
| # | Project | Description |
|---|---------|-------------|
| 1 | `servo-controller` | PWM-based servo positioning |
| 2 | `stepper-driver` | Step/direction with acceleration profiles |
| 3 | `dc-motor` | Bidirectional motor control with PWM |
| 4 | `pid-controller` | Closed-loop control for temperature, position |
| 5 | `relay-controller` | Safe high-voltage switching with isolation |

### RTOS & Task Management
| # | Project | Description |
|---|---------|-------------|
| 1 | `task-scheduler` | Cooperative/preemptive multitasking |
| 2 | `priority-queue` | Task prioritization with deadline handling |
| 3 | `semaphore-mutex` | Resource sharing between tasks |
| 4 | `message-queues` | Inter-task communication |
| 5 | `watchdog` | System health monitoring, recovery |
| 6 | `power-management` | Sleep modes, wake sources, power budgeting |

### Bootloader & Firmware
| # | Project | Description |
|---|---------|-------------|
| 1 | `bootloader` | Minimal bootloader with app jumping |
| 2 | `ota-updater` | Over-the-air firmware updates |
| 3 | `dual-bank-boot` | A/B partition switching for safe updates |
| 4 | `crc-validator` | Firmware integrity checking |
| 5 | `flash-manager` | Wear leveling, sector management |

### IoT Networking
| # | Project | Description |
|---|---------|-------------|
| 1 | `mqtt-client` | Pub/sub messaging for IoT |
| 2 | `coap-server` | Constrained Application Protocol |
| 3 | `http-api` | Embedded web server with JSON API |
| 4 | `websocket-client` | Real-time bidirectional communication |
| 5 | `ble-peripheral` | Bluetooth Low Energy GATT server |
| 6 | `lora-transceiver` | Long-range low-power communication |

### Data Logging & Storage
| # | Project | Description |
|---|---------|-------------|
| 1 | `sd-card-logger` | FAT filesystem data logging |
| 2 | `eeprom-manager` | Wear-leveled config storage |
| 3 | `ring-buffer` | Circular buffer for streaming data |
| 4 | `flash-filesystem` | LittleFS or SPIFFS implementation |
| 5 | `timeseries-db` | Efficient sensor data storage |

### Display & User Interface
| # | Project | Description |
|---|---------|-------------|
| 1 | `lcd-driver` | Character LCD (HD44780) or graphic TFT |
| 2 | `oled-graphics` | SSD1306 with drawing primitives |
| 3 | `menu-system` | Hierarchical menu with encoder/buttons |
| 4 | `touchscreen` | Resistive/capacitive touch handling |
| 5 | `epaper` | Low-power e-ink interface |

### Build & Development Tools
| # | Project | Description |
|---|---------|-------------|
| 1 | `cross-compiler` | Set up ARM/RISC-V toolchain |
| 2 | `yocto-layer` | Custom layer for embedded Linux |
| 3 | `device-tree` | Write and compile device tree overlays |
| 4 | `debug-probe` | OpenOCD, GDB remote debugging |
| 5 | `unit-test-harness` | Embedded unit testing framework |

### Embedded Security
| # | Project | Description |
|---|---------|-------------|
| 1 | `secure-boot` | Verified boot chain implementation |
| 2 | `crypto-library` | AES, SHA on constrained devices |
| 3 | `key-storage` | Secure element or protected flash |
| 4 | `tls-client` | Minimal TLS for resource-limited devices |

---

## Distributed Systems

Distributed computing, consensus, coordination, and scalable architectures.

### Consensus & Coordination
| # | Project | Description |
|---|---------|-------------|
| 1 | `raft` | Leader election, log replication, snapshots |
| 2 | `paxos` | Single-decree Paxos consensus |
| 3 | `two-phase-commit` | Distributed transaction coordinator |
| 4 | `vector-clocks` | Causality tracking for events |
| 5 | `lamport-timestamps` | Logical clock ordering |

### Distributed Storage
| # | Project | Description |
|---|---------|-------------|
| 1 | `kv-store` | Distributed KV with replication |
| 2 | `consistent-hashing` | Ring-based partitioning with virtual nodes |
| 3 | `distributed-cache` | Memcached-like distributed caching |
| 4 | `log-structured-store` | Append-only storage with compaction |
| 5 | `replicated-state-machine` | State machine with consensus |
| 6 | `distributed-fs` | Chunk-based file storage (mini-GFS) |

### Message Queues & Streaming
| # | Project | Description |
|---|---------|-------------|
| 1 | `message-broker` | Pub/sub with topics and queues |
| 2 | `event-log` | Append-only log with consumer groups |
| 3 | `dead-letter-queue` | Failed message handling |
| 4 | `priority-queue` | Distributed priority-based delivery |
| 5 | `stream-processor` | Real-time event processing pipeline |

### RPC & Communication
| # | Project | Description |
|---|---------|-------------|
| 1 | `rpc-framework` | Request/response with serialization |
| 2 | `grpc-service` | Protocol buffers based RPC |
| 3 | `service-mesh` | Sidecar proxy for service communication |
| 4 | `circuit-breaker` | Failure detection and recovery |
| 5 | `retry-backoff` | Exponential backoff with jitter |

### Service Discovery
| # | Project | Description |
|---|---------|-------------|
| 1 | `service-registry` | Register/discover services dynamically |
| 2 | `health-checker` | Heartbeat-based liveness detection |
| 3 | `dns-discovery` | Service discovery via DNS |
| 4 | `leader-election` | Distributed leader election service |
| 5 | `config-store` | Distributed config with watches |

### Load Balancing & Routing
| # | Project | Description |
|---|---------|-------------|
| 1 | `load-balancer` | Round-robin, least-conn, weighted |
| 2 | `reverse-proxy` | HTTP proxy with routing rules |
| 3 | `rate-limiter` | Distributed rate limiting (token bucket) |
| 4 | `api-gateway` | Request routing, auth, rate limiting |
| 5 | `consistent-hash-lb` | Sticky sessions with consistent hashing |

### Fault Tolerance
| # | Project | Description |
|---|---------|-------------|
| 1 | `failure-detector` | Phi accrual or heartbeat-based detection |
| 2 | `bulkhead` | Resource isolation for failures |
| 3 | `saga-orchestrator` | Long-running transaction compensation |
| 4 | `idempotency-layer` | Exactly-once semantics with dedup |
| 5 | `chaos-monkey` | Random failure injection for testing |

### Distributed Algorithms
| # | Project | Description |
|---|---------|-------------|
| 1 | `gossip-protocol` | Epidemic information dissemination |
| 2 | `crdt` | Conflict-free replicated data types |
| 3 | `bloom-filter-sync` | Efficient set reconciliation |
| 4 | `merkle-tree` | Data integrity verification |
| 5 | `snapshot-algorithm` | Chandy-Lamport global snapshots |

### Monitoring & Observability
| # | Project | Description |
|---|---------|-------------|
| 1 | `metrics-collector` | Aggregate metrics from services |
| 2 | `distributed-tracing` | Request tracing across services |
| 3 | `log-aggregator` | Centralized log collection |
| 4 | `alerting-system` | Threshold-based alert notification |
| 5 | `dashboard` | Real-time metrics visualization |

### Cluster Management
| # | Project | Description |
|---|---------|-------------|
| 1 | `job-scheduler` | Distribute tasks across workers |
| 2 | `resource-manager` | CPU/memory allocation for jobs |
| 3 | `node-manager` | Worker node lifecycle management |
| 4 | `auto-scaler` | Scale workers based on load |
| 5 | `rolling-deployer` | Zero-downtime deployment |

### Distributed Data Processing
| # | Project | Description |
|---|---------|-------------|
| 1 | `map-reduce` | Distributed map and reduce framework |
| 2 | `batch-processor` | Large-scale batch job execution |
| 3 | `stream-joiner` | Join multiple event streams |
| 4 | `windowed-aggregation` | Time-window based aggregations |

---

## Web & API Development

Web servers, REST APIs, GraphQL, authentication, and microservices.

### HTTP Server Fundamentals
| # | Project | Description |
|---|---------|-------------|
| 1 | `http-server` | Parse requests, route handlers, send responses |
| 2 | `static-file-server` | Serve files with MIME types, caching headers |
| 3 | `router` | Path matching, params, middleware chain |
| 4 | `request-logger` | Log method, path, status, timing |
| 5 | `compression` | Gzip/Brotli response compression |

### REST API Design
| # | Project | Description |
|---|---------|-------------|
| 1 | `crud-api` | Create, read, update, delete with proper verbs |
| 2 | `pagination` | Offset, cursor, keyset pagination |
| 3 | `filtering-sorting` | Query params for filtering, sorting |
| 4 | `versioning` | URL, header, or content-type versioning |
| 5 | `hateoas` | Hypermedia links in responses |
| 6 | `openapi-spec` | Generate/consume OpenAPI documentation |

### Authentication & Authorization
| # | Project | Description |
|---|---------|-------------|
| 1 | `jwt-auth` | Issue, validate, refresh JWT tokens |
| 2 | `oauth2-server` | Authorization code, client credentials flows |
| 3 | `oauth2-client` | Integrate with Google, GitHub OAuth |
| 4 | `session-auth` | Cookie-based sessions with store |
| 5 | `api-keys` | Key generation, validation, rotation |
| 6 | `rbac` | Role-based access control middleware |

### Real-Time Communication
| # | Project | Description |
|---|---------|-------------|
| 1 | `websocket-server` | Bidirectional real-time messaging |
| 2 | `chat-server` | Multi-room chat with presence |
| 3 | `sse-endpoint` | Server-sent events for push updates |
| 4 | `long-polling` | Fallback real-time for older clients |
| 5 | `pubsub-hub` | Real-time event broadcasting |

### GraphQL
| # | Project | Description |
|---|---------|-------------|
| 1 | `graphql-server` | Schema, resolvers, queries, mutations |
| 2 | `dataloader` | Batch and cache database queries |
| 3 | `subscriptions` | Real-time GraphQL with WebSockets |
| 4 | `schema-stitching` | Combine multiple GraphQL schemas |
| 5 | `persisted-queries` | Query whitelisting for security |

### API Security
| # | Project | Description |
|---|---------|-------------|
| 1 | `rate-limiter` | Token bucket, sliding window per client |
| 2 | `input-validation` | Schema validation, sanitization |
| 3 | `cors-handler` | Cross-origin resource sharing config |
| 4 | `csrf-protection` | Token-based CSRF prevention |
| 5 | `sqli-guard` | Parameterized queries, escaping |
| 6 | `request-signing` | HMAC signature verification |

### Performance & Caching
| # | Project | Description |
|---|---------|-------------|
| 1 | `response-cache` | HTTP caching with ETags, Last-Modified |
| 2 | `redis-cache` | Cache API responses in Redis |
| 3 | `connection-pool` | Database connection pool management |
| 4 | `async-handlers` | Non-blocking I/O for high concurrency |
| 5 | `request-batching` | Combine multiple requests into one |

### Microservices Patterns
| # | Project | Description |
|---|---------|-------------|
| 1 | `api-gateway` | Route, auth, rate limit, aggregate |
| 2 | `service-registry` | Service discovery integration |
| 3 | `health-endpoints` | Liveness, readiness probes |
| 4 | `circuit-breaker` | Fail-fast with fallback responses |
| 5 | `distributed-config` | Externalized configuration |

### Background Jobs
| # | Project | Description |
|---|---------|-------------|
| 1 | `job-queue` | Async task processing with workers |
| 2 | `scheduled-jobs` | Cron-like recurring tasks |
| 3 | `webhooks` | Send and receive webhook events |
| 4 | `email-queue` | Async email sending with retries |
| 5 | `file-processor` | Background file upload processing |

### Database Integration
| # | Project | Description |
|---|---------|-------------|
| 1 | `orm-builder` | Type-safe database queries |
| 2 | `migrations` | Schema versioning and migrations |
| 3 | `transactions` | ACID transactions with rollback |
| 4 | `multi-tenancy` | Schema or row-level isolation |
| 5 | `read-replicas` | Route reads to replicas |

### Testing & Documentation
| # | Project | Description |
|---|---------|-------------|
| 1 | `integration-tests` | Test API endpoints end-to-end |
| 2 | `mock-server` | Stub external APIs for testing |
| 3 | `contract-tests` | Consumer-driven contract tests |
| 4 | `api-docs` | Auto-generate docs from code |

---

## 🛠️ Language-Specific Setup

### Go
```bash
go mod init github.com/yourusername/10x
```

### Python
```bash
python -m venv venv && source venv/bin/activate
pip install pytest requests
```

### C
```bash
# Use CMake or Make
sudo apt install build-essential cmake
```

### Rust
```bash
cargo init
```

### Java
```bash
# Use Gradle or Maven
gradle init --type java-application
```

### C++
```bash
# Use CMake
cmake -B build && cmake --build build
```

### Dart
```bash
dart create project_name
```


---

## Contributing

1. Fork the repository
2. Create a feature branch
3. Implement a project in your chosen language
4. Add tests and documentation
5. Submit a pull request

---

## License

MIT License - feel free to use these projects for learning and portfolio building.
