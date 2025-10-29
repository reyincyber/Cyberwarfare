# [ACW903: Weaponizing Vulnerabilities - Exploit Development](https://github.com/reyincyber/Cyberwarfare/tree/main/ACW903)

## Overview
ACW903 is a technically focused module on exploit development and vulnerability weaponization. It walks students from automated bug discovery (fuzzing) through crash triage, proof-of-concept (PoC) creation, payload construction (shellcode, return-to-libc, ROP), and advanced mitigation bypasses (DEP/NX, ASLR, stack canaries, RELRO, CFG). The materials mix hands-on techniques, tool-oriented workflows (AFL++, Pwntools, GDB/WinDbg, IDA/Ghidra), and real-world case studies (EternalBlue, Baron Samedit) to teach both offensive engineering and practical defensive countermeasures.

## Files in this directory
- [ACW903_Weaponizing_Vulnerabilities.pdf](https://github.com/reyincyber/Cyberwarfare/blob/main/ACW903/ACW903_GROUP%20B%20Malware%20and%20Exploit%20Techniques.pdf) — Full technical paper / lab handbook (detailed methodology, examples, and case studies).  
- [ACW903_Weaponizing_Vulnerabilities_Slides](https://github.com/reyincyber/Cyberwarfare/blob/main/ACW903/ACW903_GROUP%202_Advanced%20Malware%20and%20Exploit%20Technique%20Slides.pptx) — Slide deck summarising the core lessons and workflows for briefings or teaching.

**Key Techniques & Tools covered** 
- Fuzzers: AFL++, libFuzzer, honggfuzz
- Debugging & triage: GDB, WinDbg, pwndbg, cyclic/pattern tooling
- Exploit scripting: Python + Pwntools; C PoCs where performance/low-level control required
- Gadget discovery: ROPgadget, rp++, manual assembly inspection
- Binary analysis: IDA Pro, Ghidra
- Bypass & mitigations: ASLR, DEP/NX, stack canaries, RELRO/PIE, CFG
- Case study toolchain: sqlmap/Metasploit are referenced where relevant to broader ops

## Licensing & Ethics
These materials are intended for **educational and defensive** purposes only. By using them you agree to abide by applicable laws and institutional policies. Do **not** use the techniques on systems you do not own or have explicit authorization to test. 

## Contact / References
For questions or to request additional lab material, open an issue in the repository or contact the module owner. 
Key references used in the materials include AFL++, Pwntools, MITRE ATT&CK, and published CVE writeups (EternalBlue, CVE-2021-3156).
