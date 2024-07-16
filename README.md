# wx_visitor_tutorial

Serializing class hierarchies using the Visitor pattern.

This tutorial is a part of the series about building a multiplatform Paint App in C++ with wxWidgets: https://www.youtube.com/watch?v=Spt5VF1aSps&list=PL0qQTroQZs5sxKZDdJrn8fEjNXCPT7f5T

## Requirements

This works on Windows, Mac, and Linux. You'll need `cmake` and a C++ compiler (tested on `clang`, `gcc`, and MSVC).

Linux builds require the GTK3 library and headers installed in the system.

## Building

To build the project, use:

```bash
cmake -S. -Bbuild
cmake --build build
```

This will create a directory named `build` and create all build artifacts there. The main executable can be found in the `build/subprojects/Build/wx_visitor_tutorial_core` folder.

---
Check out the blog for more! [www.justdevtutorials.com](https://www.justdevtutorials.com)
---

#   A r t p a d  
 