# Open-RF
The Open-RF project is dedicated to providing FOSS utilities for wireless communication. This includes libraries, open firmwares and potentially software stacks.
## Philosophy
Communication is for everyone and therfore everyone should've access to it. Standards like WiFi are great for this, but most devices are shackled by closed firmwares, which don't allow hacking and experimenting on them. 
The software made available by Open-RF can be used by anyone, but isn't intended for malicious use, which we don't condone and take any responsibility for.
## Programming Language
Due to the potentially sensitive nature of the data, which is handled by Open-RF software, security vulnerabilites are critical. Experience has shown, that yes writing memory safe C code is totatlly possible, but also incredibly unlikely. Therefore we use Rust to write our software, which provides the same performance, but without opening the door for malicious actors.
