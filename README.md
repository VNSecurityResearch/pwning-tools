Pwn tools
- Allow you write ctf exploit easier
- Provide some shellcode
- Current version : 0.4
- gdb_attach : help you debug socat child process in gdb, copy to /usr/bin
- libc_collection.json : is my libc offset collection copy it into your home folder (cp pwn.json ~/.libc_collection.json)
- libc_collection.py is a script that extracts libc symbol, that help get_libc_offset method work smoothly.

Requires:
- pyelftools (pip install pyelftools)

Added:
- Sublime text snippet : 
  + copy pwnlib_snippets.sublime-snippet Sublime\ Text\ 2/Packages/User/
  + create new file py and type pwn + <tab> :)
- read_flag_enc shellcode
- exec_enc_command shelllcode