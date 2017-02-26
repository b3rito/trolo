# trolo
a easy to use script for generating Payloads that bypasses antivirus

# Requirements
Metasploit Framework

(PowerSploit)

# Author
Written by b3rito at mes3hacklab

# Installation
    chmod +x trolo.sh

# Usage
./trolo.sh

    b3rito@antani ~/trolo $ ./trolo.sh 
      ================================================================================
                                 +(\            b3rito@mes3hacklab.org
                        ______ +/  .|   _____  ____  ____  _     ____
                   >== '|     b3  \_|  /__ __\/  __\/  _ \/ \   /  _ \
                     /  |trust| \/       / \  |  \/|| / \|| |   | / \|
                     |_ | me  |__|       | |  |    /| \_/|| |_/\| \_/|
                    (  )|_____(  )       \_/  \_/\_\\____/\____/\____/
                    (__)      (__)         KEEPING IT SIMPLE!   v1.0
      ================================================================================
      https://github.com/b3rito/trolo
      Usage: ./trolo.sh -i [IP] -p [PORT] -n [NAME] -f [FORMAT] -a [ARCH. x86/x64]

        -i:	  Local host IP address
        -p:	  Local host port number (default: 443)
        -n:	  Output file name (default: PAYLOAD)
        -a:   Architecture x86/x64 (default: x64)
        -f:   Output format: hta, js, vbs, custom
        -g:   Enter the full URL where powershell grabs the txt file from
              (default: "http://YourIp/FileName.txt")
        -q:   Enter alternative URL where powershell grabs Invoke-Shellcode.ps1 from
        -u:   Update

      insert your IP:
