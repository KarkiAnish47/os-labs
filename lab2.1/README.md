# Lab 2.1: C Libraries, Linking, and ELF Executable Structure

## Files
| File | Description |
|------|-------------|
| procinfo.c | Prints PID, parent PID, time and executable path |
| Lab2.1_Documentation.pdf | Full report with screenshots |

## Build
gcc procinfo.c -o procinfo_dynamic
gcc -static procinfo.c -o procinfo_static

## Inspect
readelf -h procinfo_dynamic
readelf -l procinfo_dynamic
readelf -d procinfo_dynamic
ldd procinfo_dynamic
