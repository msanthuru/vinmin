# config/

This directory contains public-safe configuration files and templates for the
VinMin project under TLTE C.I.C. These files are intended to support open-source
development without exposing any sensitive or internal information.

Only the following types of configuration are allowed here:

- default settings  
- non-secret environment templates  
- sample configuration formats  
- public constants  
- formatting or linting configs  
- safe, generic placeholders  

The following MUST NOT appear in this directory:

- API keys  
- authentication credentials  
- internal service URLs  
- infrastructure endpoints  
- private integration details  
- region-sensitive configuration  

Any sensitive configuration remains securely stored in private TLTE C.I.C.
environments and is not part of this repository.
