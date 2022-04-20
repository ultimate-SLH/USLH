# USLH

### How to compile it
Replace the X86SpeculativeLoadHardening.cpp under folder /llvm/lib/Target/X86/

### How to use it
To enable differnt functionalities, use command -mllvm -x86-slh-xxxx

### PoCs
The zip file contain three IR files.
SMoTher PoC is tested on i7-6700K
False Dependency PoC is tested on i7-6700K, i7-10710U
Resource Contention PoC is tested on i7-10710U, i5-8265U
