# pe_to_shellcode
[![Build status](https://ci.appveyor.com/api/projects/status/w3dy81u0k3up7459?svg=true)](https://ci.appveyor.com/project/hasherezade/pe-to-shellcode)
[![GitHub release](https://img.shields.io/github/release/hasherezade/pe_to_shellcode.svg)](https://github.com/hasherezade/pe_to_shellcode/releases)

Converts PE so that it can be then injected just like a normal shellcode. (At the same time, the output file remains to be a valid PE).<br/>
Currently only 32 bit PE files are supported.<br/>

Clone:
-
Use recursive clone to get the repo together with all the submodules:
<pre>
git clone --recursive https://github.com/hasherezade/pe_to_shellcode.git
</pre>
Latest builds*:
-
*those builds are available for testing and they may be ahead of the official release:
+ [pe2shc32.exe](https://goo.gl/LfJaVZ) - PE to shellcode converter
+ [runshc32.exe](https://goo.gl/xi3fzQ) - a utility to run/test shellcode (loads and deploys)
<hr/>
