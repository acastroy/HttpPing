# HttpPing

[![](https://img.shields.io/badge/version-1.0-brightgreen.svg)]() ![](https://img.shields.io/maintenance/yes/2018.svg)

A small tool that sends HTTP requests, presented in a ping-like style with status codes and colored results.

Download it here: [[Stable Releases]](https://github.com/Killeroo/HttpPing/releases)
***
![alt text](docs/Screenshots/screenshot1.png "HttpPing in action")
![alt text](docs/Screenshots/screenshot2.png "Supports Common Log Format")
![alt text](docs/Screenshots/screenshot3.png "and with no color too!")

## Features

- Results coloration 
- Ping like functionality
- HTTP and HTTPS support
- Common Log Format (NCSA log format)

## Usage: 
     Requester web_address [-d] [-t] [-ts] [-n count] [-i interval]
               
## Arguments:
     [-d]           Detailed mode: shows server and cache info
     [-t]           Infinite mode: Keep sending requests until stopped (Ctrl-C)
     [-n count]     Send a specific number of requests
     [-ts]          Include timestamp of when each request was sent
     [-i interval]  Interval between each request in milliseconds (default 30000)
     [-l]           Use Common Log Format (https://en.wikipedia.org/wiki/Common_Log_Format)
     [-nc]          No color
     
## License

Requester is licensed under the [MIT license](LICENSE).

*Written by Matthew Carney [matthewcarney64@gmail.com] =^-^=*
