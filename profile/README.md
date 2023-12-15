# RC-UCR

**R**ocks**c**lusters - **U**nofficial **C**ommunity **R**elease is a non-profit, non-commercial, open-source, and community-based attempt to reactivate the ROCKS<sup>:tm:</sup> open-source Linux cluster distribution project, which has been dormant since 2017.

ROCKS<sup>:tm:</sup> continues to be important to the scientific community as well as to business users. The lack of further development since 2017 has been widely discussed and lamented in the support mailing lists. Likewise, the coming end of the CentOS 7 Linux distribution has raised fundamental questions about how Rocks can be further developed. Support for CentOS 7 ends on June 30, 2024. At the same time, Rocky Linux has established itself as a replacement for CentOS. This creates an opportunity to find ways to at least port the existing Rocks software base to Rocky Linux.

As a first step, RC-UCR is attempting to port the existing Rocks code for CentOS 7.9.2009, to document a simplified build process and to make the resulting first distribution 7.2.0-UCR available to the general public.

Contact: `info (at) rc-ucr.org `

## Latest Official Release

The latest official release of **ROCKS**<sup>:tm:</sup> 7.0 *Manzanita* (based CentOS 7.4) is available at http://www.rocksclusters.org/new/2017/2017/12/01/rocks-7-0-released.html and was released on Dec 1, 2017.

## Latest Unoffical Community Release 7.2.0-UCR

The latest unofficial community release **7.2.0-UCR** *Coffeeberry* (based on CentOS 7.9.2009, including all CentOS updates as of Dec 15, 2023) is available at:

- Central server: http://rc-ucr.org/7-2-0-UCR/install/rolls/
- ISO-images: http://rc-ucr.org/7-2-0-UCR/isos/x86_64/
- Linux kernel version: `3.10.0-1160.105.1.el7.x86_64 `

Official version 7.0 installation instructions (http://www.rocksclusters.org/docs/guides.html) are still applicable for RC-UCR. The following rolls are currently available via Internet on central server:

- Required for installation: `base`, `core`, `kernel`, `CentOS`, `Updates-CentOS-7.9.2009`
- Optional: `ganglia`, `sge`

## Development

RC-UCR follows the same repository layout as the original software. Each roll is developed in its own repository, forked from the original repository. There are some helper repositories as well as a master repository which is used for building the complete distribution.

- `build`: https://github.com/rc-ucr/build
- `rocks`: https://github.com/rc-ucr/rocks
- `rocksbuild`: https://github.com/rc-ucr/rocksbuild
- `core`: https://github.com/rc-ucr/core
- `base`: https://github.com/rc-ucr/base
- `kernel`: https://github.com/rc-ucr/kernel
- `ganglia`: https://github.com/rc-ucr/ganglia
- `sge`: https://github.com/rc-ucr/sge

There are no specific `CentOS` or `Update-CentOS` repositories, as these rolls are created together with `base` roll during build. Detailed buidling instructions are given in https://github.com/rc-ucr/build.

## Rocks Copyright

The Rocks Logo, the name ROCKS<sup>:tm:</sup>, and the name CentOS<sup>:tm:</sup> are registered trademarks with the United States Patent and Trademark Office and possibly other trademark offices.

```txt
Rocks(r)
                www.rocksclusters.org
                version 6.2 (SideWinder)
                version 7.0 (Manzanita)
 
 Copyright (c) 2000 - 2017 The Regents of the University of California.
 All rights reserved.
 
 Redistribution and use in source and binary forms, with or without
 modification, are permitted provided that the following conditions are
 met:
 
 1. Redistributions of source code must retain the above copyright
 notice, this list of conditions and the following disclaimer.
 
 2. Redistributions in binary form must reproduce the above copyright
 notice unmodified and in its entirety, this list of conditions and the
 following disclaimer in the documentation and/or other materials provided 
 with the distribution.
 
 3. All advertising and press materials, printed or electronic, mentioning
 features or use of this software must display the following acknowledgement: 
 
   "This product includes software developed by the Rocks(r)
   Cluster Group at the San Diego Supercomputer Center at the
   University of California, San Diego and its contributors."
 
 4. Except as permitted for the purposes of acknowledgment in paragraph 3,
 neither the name or logo of this software nor the names of its
 authors may be used to endorse or promote products derived from this
 software without specific prior written permission.  The name of the
 software includes the following terms, and any derivatives thereof:
 "Rocks", "Rocks Clusters", and "Avalanche Installer".  For licensing of 
 the associated name, interested parties should contact Technology 
 Transfer & Intellectual Property Services, University of California, 
 San Diego, 9500 Gilman Drive, Mail Code 0910, La Jolla, CA 92093-0910, 
 Ph: (858) 534-5815, FAX: (858) 534-7345, E-MAIL:invent@ucsd.edu
 
 THIS SOFTWARE IS PROVIDED BY THE REGENTS AND CONTRIBUTORS ``AS IS''
 AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO,
 THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR
 PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE REGENTS OR CONTRIBUTORS
 BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
 CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
 SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR
 BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY,
 WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE
 OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN
 IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.
```

