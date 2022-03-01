## wired up
```
DHT11      ESP32
VCC   ---> VIN
DATA  ---> D4
GND   ---> GND
```
Compile is based on esp-idf project. https://github.com/espressif/esp-idf.git
I have search several code, all didn't work, this an avail one.

## Example folder contents

The project **sample_project** contains one source file in C language [main.c](main/main.c). The file is located in folder [main](main).

ESP-IDF projects are built using CMake. The project build configuration is contained in `CMakeLists.txt`
files that provide set of directives and instructions describing the project's source files and targets
(executable, library, or both). 

Below is short explanation of remaining files in the project folder.

```
├── CMakeLists.txt
├── main
│   ├── CMakeLists.txt
│   └── main.c
└── README.md            <---- This is the file you are currently reading
```
