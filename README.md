# Hi there, I'm Aki Subramaniam

Electrical Engineering, UCLA '28, interested in computer architecture, ASIC design, channel coding, etc.

## Technologies & Tools

- **Languages:** SystemVerilog, Tcl, SVA, CUDA, C, C++, Python
- **Tools:** Vivado, Verilator, GTKWave, cocotb, LibreLane, OpenROAD, OpenSTA

## GitHub Stats

![Suijester's GitHub stats](https://github-readme-stats.vercel.app/api?username=Suijester&show_icons=true&theme=radical)

## Projects
- **[8-bit RISC-V, TinyTapeout](https://github.com/UCLA-Tapeout-Club/risc_v):** 8-bit CPU design submitted to TinyTapeout, for their SKY 26c shuttle this September (estimated return date of May 2027). Implemented the CPU core logic (ALU, control logic, register file, datapath, etc.) for this project, and ran STA through LibreLane Actions, achieving clean hold at every corner, and closing at 64.5 MHz, while submitting at 50 MHz. The TinyTapeout-specific repository can be found [here](https://github.com/UCLA-Tapeout-Club/risc_v_tt), since we had to move it to a specific template repository.
- **[ELF-TBCC Spectrum Analyzer](https://github.com/UCLA-Communications-Systems-Lab/elf-tbcc-spectrum):** Open-source CUDA distance-spectrum analyzer for expurgated tail-biting convolutional codes (ELF-TBCC codes). Searches millions of candidate codes in hours using NVIDIA CGBN for wide block lengths and performs symmetry-based pruning of identical and catastrophic codes to reduce the sample space. Associated tool for our accepted ITW '26 paper.
- **[Aki-TPU](https://github.com/Suijester/aki-tpu):** TPU-style matmul accelerator, implementing scalable systolic arrays for rapid calculations, ReLU unit for full neural network layer execution, and double buffering to conceal I/O write latency; achieved 183 MHZ with 23.5 GOP/s for 8x8 MMUL with INT16 data types. Can be parameterized for different matrix sizes and data widths.
- **[RISC-V](https://github.com/Suijester/risc-v):** Lightweight pipelined RV32I soft-core implementation, featuring L1 Cache for instruction memory, static branch prediction, hazard handling, and register forwarding; achieved 105 MHz clock speed with 0.5ns positive slack, and <10% resource area usage when synthesized in Vivado on Artix-7.
- **[Aki-RTOS](https://github.com/Suijester/aki-rtos):** High-performance real-time operating system for STM32 Microcontrollers, implementing preemptive scheduling with semaphore-based blocking, priority-based interrupt handling, lightweight inter-task communication through message queues, and O(1) task scheduling with priority-ready lists. Achieved 4.309µs context switching, 11.309µs scheduler boot time, 16.44µs task creation to execution.
- **[LZ77-Hardware](https://github.com/Suijester/lz77-hardware):** Low-latency parameterizable & parallelized search greedy compressor intended for FPGA deployment, achieving almost 2x compression on Alice in Wonderland, designed to trade-off between throughput and compression dependent on resource area.
- **[REST-Connect](https://github.com/Suijester/REST-Connect):** Middleman CLI Tool and API that enables automated test-case generation, enabling users in identifying logic, runtime, or behavioral errors through GPT integration.
- **[Memorize](https://github.com/Suijester/Memorize):** Memo assistant wake word speech-to-text tool that enables memo generation and storage in Postgres, enabling users to query prior memos via vector search, serving as a Second Brain for informational recall.
