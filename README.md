PS-NimbleStorage
================

Just a collection of PowerShell functions I've built and partially consolidated from others along the way, to assist in automating the optimization of Nimble Storage array volumes integrated into VMware ESXi infrastructure.

Fuction1: Set-NimbleIopsRR - this function will step through each Nimble Storage disk attached to an ESXi host and set the recommended IO path switching values per Nimble Storage best practices.

Function2: Set-NimblePSP - this function will step through each Nimble Storage disk attached to an ESXi host and set the recommended IO paths switching values as well as the recommended path selection policy (VMW) per Nimble Storage best practices.
