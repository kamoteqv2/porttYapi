## porttYapi.exe

**porttYapi.exe** is a command-line tool that helps users connect their Arduino Uno to a network without using an Ethernet shield. This API program interfaces with the Arduino serial and serves as an API server to middleman HTTP POST requests from the OpenHAB application to the Arduino via the command line.

## Installation
To use **porttYapi.exe**, you will need to download the executable file and save it on your computer. You can do this by clicking the "Download" button on the GitHub repository.

## Usage
The command-line syntax for porttYapi.exe is as follows:

```
porttyapi --ip IP --hport PORT --cport SERIAL-COM-PORT --debug True/False
```

If --ip is not specified, the default is 127.0.0.1. The default for --hport is 5000, the default for --cport is com11, and the default for --debug is False.

To use **porttYapi.exe**, open a command prompt and navigate to the directory where you saved the executable file. Then, enter the command with the appropriate options for your setup. For example:

```
porttyapi --ip 192.168.1.2 --hport 8080 --cport com3 --debug True
```

This would start **porttYapi.exe** with an IP address of 192.168.1.2, an HTTP port of 8080, a serial COM port of com3, and debug mode enabled.

## Support
If you have any issues with porttYapi.exe, please open an issue on the GitHub repository.

## Contributing
If you would like to contribute to porttYapi.exe, please open a pull request on the GitHub repository.

## License
**porttYapi.exe** is licensed under the MIT license. See the LICENSE file for more details.


Credit: This application was developed by KMQ Tech TV (https://www.youtube.com/@kamoteqv2), a Youtube channel dedicated to teaching and promoting Free DIY technology.
