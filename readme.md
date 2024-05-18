# Checksum

## Realworld
- https://archive.apache.org/dist/openoffice/4.1.14/binaries/en-US/
```
[   ] Apache_OpenOffice_4.1.14_MacOS_x86-64_langpack_en-US.dmg               2023-02-09 18:29   17M  
[TXT] Apache_OpenOffice_4.1.14_MacOS_x86-64_langpack_en-US.dmg.asc           2023-02-13 15:41  833   
[TXT] Apache_OpenOffice_4.1.14_MacOS_x86-64_langpack_en-US.dmg.sha256        2023-02-13 15:41  123   
[TXT] Apache_OpenOffice_4.1.14_MacOS_x86-64_langpack_en-US.dmg.sha512        2023-02-13 15:41  187
```
- Verify downloaded file:
1. Generate checksum for downloaded file 
```sh
% shasum -a 256 Apache_OpenOffice_4.1.14_MacOS_x86-64_langpack_en-US.dmg
83eacea506abd7391df4f40607a9d384a7a2713ef18ac251b83822cfc6fe0088  Apache_OpenOffice_4.1.14_MacOS_x86-64_langpack_en-US.dmg
```
2. Compare if it's same as one provided from server: https://archive.apache.org/dist/openoffice/4.1.14/binaries/en-US/Apache_OpenOffice_4.1.14_MacOS_x86-64_langpack_en-US.dmg.sha256
