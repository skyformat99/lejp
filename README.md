# Lightweight Embedded JSON Parser mbed3 port

 - MBED3 project
 - C code callable from C++
 - builds to <2KBytes ARM v7 code
 - 280 byte parsing context struct only needed while parsing
 - no malloc or other allocations
 - strictly bytewise and single pass
 - complete robust JSON parser implementation including floats
 - calls back to user supplied routine when something parsed
 - LGPL2.1 + Static Linking Exception

 This is the library itself, build the lejp-demo-dump application that
 uses this library for a prebuilt demo.
 
