<div align="center">

# dwc

`kernel dev` · `reverse engineering` · `dfir` · `low-level research`

<br/>

<img src="https://camo.githubusercontent.com/0ac7f165370821b30a1138c9e13003df16578b5efbe0fca19e020aa87dcc8064/68747470733a2f2f636f756e7465722e6c756e6f7869612e6e65742f67682f40766d7070726f746563743f7468656d653d61736f756c" alt="Profile counter" />

</div>

---

| | |
| :--- | :--- |
| **alias** | dwc |
| **focus** | windows kernel drivers, binary reversing, artifact analysis |
| **languages** | c++, c, x86/x64 assembly, c# |
| **tooling** | windbg, ida pro, ghidra, binary ninja, x64dbg |
| **target** | windows kernel & user mode (x64) |

I write kernel drivers, reverse native Windows binaries, and analyze system execution artifacts.

---

## Technical Focus

### Kernel Development
- Developing KMDF & WDM drivers and exploring Windows internals.
- Kernel callbacks (`ObRegisterCallbacks`, `PspCreateProcessNotifyRoutine`), IRP handling, and system structures.

### Reverse Engineering
- Static and dynamic analysis of x86/x64 native binaries.
- PE header analysis, unpacking, reversing undocumented APIs, and control flow tracing.

### Digital Forensics
- Disk and memory artifact extraction and timeline reconstruction.
- Parsing MFT, USN Journal, Prefetch, BAM/DAM, Shimcache, Amcache, and registry transaction logs.

### Game Internals
- Low-level process memory interaction, hooking techniques, pattern scanning, and manual mapping.

---

## Languages & Tools

<p align="left">
  <a href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg"><img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" /></a>
  &nbsp;&nbsp;
  <a href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg"><img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C" /></a>
  &nbsp;&nbsp;
  <a href="https://img.shields.io/badge/ASM-6E4C13?style=flat-square"><img height="36" src="https://img.shields.io/badge/ASM-6E4C13?style=flat-square" alt="Assembly" /></a>
  &nbsp;&nbsp;
  <a href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg"><img height="36" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" /></a>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/WinDbg-30343b?style=flat-square" alt="WinDbg" />
  <img src="https://img.shields.io/badge/IDA%20Pro-30343b?style=flat-square" alt="IDA Pro" />
  <img src="https://img.shields.io/badge/Ghidra-30343b?style=flat-square" alt="Ghidra" />
  <img src="https://img.shields.io/badge/Binary%20Ninja-30343b?style=flat-square" alt="Binary Ninja" />
  <img src="https://img.shields.io/badge/x64dbg-30343b?style=flat-square" alt="x64dbg" />
  <img src="https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Windows" />
</p>
