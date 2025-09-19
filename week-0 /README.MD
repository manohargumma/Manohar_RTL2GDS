# TOOL INSTALATION
# yosys
$ sudo apt-get update<br>
$ git clone https://github.com/YosysHQ/yosys.git<br>
$ cd yosys
$ sudo apt install make              <br>
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev<br>
$ make config-gcc<br>

$ git submodule update --init --recursive <br>
$ make <br>
$ sudo make install<br>
<a href="https://ibb.co/8ndMQqSG"><img src="https://i.ibb.co/8ndMQqSG/Screenshot-from-2025-09-19-22-01-43.png" alt="Screenshot-from-2025-09-19-22-01-43" border="100" align="center"></a>
