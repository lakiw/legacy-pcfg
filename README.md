# Previous Versions and Legacy Code for the PCFG Password Cracker


## Overview

Note, none of these versions are still being maintained. 

- Honeywords: The original honeyword generation code using PCFGs. This was part of an unreleased paper that I collaborated with Ron Rivest, and several researchers at RSA Labs

- PCFGv3: This is the general purpose PCFG that has been adapted for password cracking. Unlike PCFGv4 which is the current version, this supports recursion and a more generic grammar. This comes at a cost of complexity and slower speed, which is why those features are no longer supported

- c_pcfg_cracker_v2: This is a C++ version of the PCFG password cracker. This is still the fastest version of the code I've written, though the grammar is significantly simpler than what is found in v4. I expect I'll be reusing much of this code to create a new pure-C version for inclusion into Hashcat and John the Ripper

- passphrase_research: This was from me playing around with creating a passphrase generator using PCFGs. It is based on the C++ version of the cracker


