# Where You Are

To better understand the host that you're on, run the following commands:

- `grep -H . /etc/*release`
  - For the above command, understand both the implications of the filename that the text came out of, and the meaning of the text itself.
- `uname -a`
- `ldd --version`
- `gcc --version`
- `lscpu`
- `printenv | grep XDG`
- `loginctl show-session`
- `sudo dmidecode -t system | grep -E "Manufacturer:|Product Name:|Family:|Chassis Type:"`
- `lscpu | grep -E "Architecture:|Vendor ID:|Model name:|CPU family:|CPU(s):|Core(s) per socket:|Thread(s) per core:"`
