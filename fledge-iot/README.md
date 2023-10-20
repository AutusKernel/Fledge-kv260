# Build fledge-iot rpm for KV260

Based on the following two reasons，We can only choose to build the rpm package ourselves :

1. Deb manager conflict with Vitis package
2. Provided RPM-GPG-KEY-fledge only support for x86_64

During the construction process, there will be version conflicts between dependent dynamic libraries（.so) .  
Modules that depend on python will also have syntax errors and other problems depending on the python version.

**Currently, follow the steps below to build it:**

## 1. Build libpg  
## 2. Build postgresql  
## 3. Build fledge-iot

