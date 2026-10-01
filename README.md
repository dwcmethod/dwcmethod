<div align="center">

# dwc

`kernel dev` · `reverse engineering` · `dfir` · `cheat development`

<br/>

<img src="https://camo.githubusercontent.com/0ac7f165370821b30a1138c9e13003df16578b5efbe0fca19e020aa87dcc8064/68747470733a2f2f636f756e7465722e6c756e6f7869612e6e65742f6765742f40766d7070726f746563743f7468656d653d61736f756c" alt="Profile counter" />

</div>

---

| | |
| :--- | :--- |
| **alias** | dwc |
| **focus** | windows kernel drivers, binary reversing, execution forensics, low-level internals |
| **languages** | c++ · c · assembly · c# |
| **tooling** | ida pro · ghidra · binary ninja · x64dbg · windbg |
| **target** | windows kernel & user mode (x64) |

I focus on low-level analysis, writing kernel drivers, and analyzing system execution behavior. Most of my work involves reversing native binaries, inspecting kernel structures, and recovering volatile disk/memory artifacts.

---

## Technical Focus

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Kernel Development</h3>
      <p>Developing KMDF & WDM drivers, exploring Windows internals, handling kernel callbacks (<code>ObRegisterCallbacks</code>, <code>PspCreateProcessNotifyRoutine</code>) and IRP dispatch routines.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Reverse Engineering</h3>
      <p>Static and dynamic disassembly of native x86/x64 binaries. PE header analysis, control flow tracing, unpacking, and reversing undocumented APIs.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Digital Forensics (DFIR)</h3>
      <p>Deep analysis of disk and volatile memory artifacts. Reconstructing activity via MFT, USN Journal, Prefetch, BAM/DAM, Shimcache, Amcache, and registry transaction logs.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Cheat Development</h3>
      <p>Low-level game internals research, memory manipulation, pattern scanning, manual mapping, and analyzing process execution flow.</p>
    </td>
  </tr>
</table>

---

## Stack & Tools

<p align="left">
  <img height="38" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" alt="C++" />
  &nbsp;&nbsp;
  <img height="38" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" alt="C" />
  &nbsp;&nbsp;
  <img height="38" src="https://img.shields.io/badge/ASM-6E4C13?style=flat-square" alt="Assembly" />
  &nbsp;&nbsp;
  <img height="38" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/csharp/csharp-original.svg" alt="C#" />
</p>

<p align="left">
  <img src="https://img.shields.io/badge/IDA%20Pro-30343b?style=flat-square" alt="IDA Pro" />
  <img src="https://img.shields.io/badge/Ghidra-30343b?style=flat-square" alt="Ghidra" />
  <img src="https://img.shields.io/badge/Binary%20Ninja-30343b?style=flat-square" alt="Binary Ninja" />
  <img src="https://img.shields.io/badge/x64dbg-30343b?style=flat-square" alt="x64dbg" />
  <img src="https://img.shields.io/badge/Windows-0078D4?style=flat-square&logo=windows&logoColor=white" alt="Windows" />
</p>
