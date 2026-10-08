Test code samples written in C/C++ using Windows APIs.

# Samples
## [MessageBox](https://learn.microsoft.com/en-us/windows/win32/api/winuser/nf-winuser-messagebox)
| Name | Functionality | WINE compatibility | ReactOS compatibility |
| :--- | :--- | :---: | :---: |
| [messagebox_helloworld.c](https://github.com/Armen12345/w32-test/blob/main/MessageBox/messagebox_helloworld.c) (`messagebox_helloworld.exe`) | Creates a simple message box. Features an `OK` button. | ✅ (tested with 11.0 Staging) | ✅ (tested with i386 20261005-0.4.17-dev-1000-g4f829e6.GNU_8.4.0 nightly build) |
| [messagebox_error.c](https://github.com/Armen12345/w32-test/blob/main/MessageBox/messagebox_error.c) (`messagebox_error.exe`) | Creates a simple message box. Sets LPCTSTR lpCaption to `NULL` which causes the "Error" title. Includes `Retry` and `Cancel` buttons. | ✅ (tested with 11.0 Staging) | ✅ (tested with i386 20261005-0.4.17-dev-1000-g4f829e6.GNU_8.4.0 nightly build) |

# What can I use it for?
This is not a standalone production software. These samples are created for testing and troubleshooting Win32/NT-like environments, as well as practicing and learning Windows API usage.

All files are licensed under the BSD-3-Clause License. You are welcome to contribute to or fork this repository!
