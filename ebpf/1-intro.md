# Introduction to eBPF

eBPF (extended Berkeley Packet Filter) is a powerful technology in the Linux kernel that allows users to run sandboxed programs in kernel space. Originally designed for packet filtering, eBPF has evolved to support a wide range of use cases, including networking, security, tracing, and observability.

## Definition

BPF is a flexible and efficient technology composed of an instruction set, storage objects, and helper functions. It can be considered a virtual machine due to its virtual instruction set specification. These instructions are executed by a Linux kernel BPF runtime, which includes an interpreter and a JIT compiler for turning BPF instructions into native instructions for execution. BPF instructions must first pass through a verifier that checks for safety, ensuring that the BPF program will not crash or corrupt the kernel.

Three main uses of BPF:

- networking
- observability
- security