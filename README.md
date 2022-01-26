# Security Vulnerabilities caused by Memory Errors

This is a collection of important security vulnerabilities caused by memory errors, e.g., buffer overflows.
We focus on security vulnerabilities in critical and widely used (or otherwise very important) software.

- **pwnkit: Local Privilege Escalation in polkit's pkexec**  (2022/01/25)  
  https://seclists.org/oss-sec/2022/q1/80  
  Array-out-of-bounds access in essential linux program `pkexec` allows unprivileged user to obtain full root access.
  
