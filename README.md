### Systems & Security Software Developer
Specializing in Modern C++ (C++20), Windows Internals, and Runtime Instrumentation.

---

### Overview

Software developer with a systems-first approach. Experienced in designing low-latency user-mode execution runtimes, native memory manipulation, and telemetry infrastructure operating under real-world constraints.

- **Low-Level Systems:** Portable Executable (PE) in-memory parsing, manual relocation, Import Address Table (IAT) resolution, and dynamic API hooking.
- **Runtime Interoperability:** Native Java Native Interface (JNI) integration, JVM internal structures, and real-time network protocol instrumentation.
- **Machine Learning & Signal Analysis:** Real-time statistical feature extraction (timing jitter, frequency distributions) and classification models (Random Forest) for behavioral analysis.
- **System Architecture:** Clean separation of native performance cores (C++), isolated user interfaces (WebView2), and serverless telemetry pipelines.

---

### Selected Systems & Architecture Case Studies

- **[In-Memory PE Runtime & Integrity Protection Engine (C++20)](https://github.com/MarcosKauanS/inmemory-pe-runtime)**  
  Architected an in-memory execution pipeline eliminating disk artifacts via custom PE mapping, base relocations, and manual IAT resolution. Hardened against reverse engineering and symbolic solvers (MBA/ASE) with sub-500µs edge telemetry.

- **[Real-Time Behavioral Kinematics & Statistical Telemetry Runtime (JVM / Python)](https://github.com/MarcosKauanS/kinematic-anticheat-runtime)**  
  Engineered a zero-dependency server-side anomaly detection engine. Transpiled an 11-dimensional Random Forest classifier (0.9084 ROC-AUC) directly into native JVM conditional bytecode, executing evaluations in ~420ns with zero heap allocations.

- **Global Telemetry & Distribution Infrastructure (Edge)**  
  Designed serverless routing and telemetry services handling 8,000+ monthly requests across 30+ global edge nodes. Maintained sub-millisecond execution times (<500µs CPU) and a 0.00% operational error rate.

---

### Technical Focus

- **Languages:** C++20, Java, C, TypeScript, Python, x86/x64 Assembly
- **Systems & Internals:** Win32 API, Memory Virtualization, JNI, JVM Internals, Netty
- **Analysis & Diagnostics:** x64dbg, Ghidra, Wireshark, CMake, Git
- **Infrastructure & Services:** Cloudflare Workers, Node.js, WebSockets, REST