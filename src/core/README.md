# core/

This directory contains foundational, public-safe modules used across the
VinMin project under TLTE C.I.C.

Modules placed here should be:

- reusable  
- framework-agnostic  
- secure  
- non-sensitive  
- appropriate for open-source release  

Examples of what may go here:

- shared utility classes  
- basic data structures  
- safe helper logic  
- configuration loaders (without secrets)

Internal or security-sensitive core systems are **not** included in this
repository and remain private within TLTE C.I.C.
