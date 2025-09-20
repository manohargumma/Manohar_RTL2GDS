# TOOL CHECK
# <u>yosys</u>
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
<a href="https://ibb.co/8ndMQqSG"><img src="https://i.ibb.co/BHrLYbSv/Screenshot-from-2025-09-19-22-01-43.png" alt="Screenshot-from-2025-09-19-22-01-43" border="0"></a><br />
# <u>iverilog</u>
$ sudo apt-get update<br>
$ sudo apt-get install iverilog<br>
<a href="https://ibb.co/h1nhWF1c"><img src="https://i.ibb.co/YTKYkBTX/Screenshot-from-2025-09-19-22-22-25.png" alt="Screenshot-from-2025-09-19-22-22-25" border="0"></a><br>
# gtkwave 

$sudo apt-get update<br>
$sudo apt install gtkwave <br>
<a href="https://imgbb.com/"><img src="https://i.ibb.co/Xx35s7Sv/Screenshot-from-2025-09-19-22-28-02.png" alt="Screenshot-from-2025-09-19-22-28-02" border="0"></a><br>
# OpenTimer
$ git clone https://github.com/OpenTimer/OpenTimer<br>
$ cd OpenTimer<br>
$ mkdir build<br>
$ cd build<br>
$ cmake ../
$ make <br>
<a href="https://ibb.co/Hf6RkHsv"><img src="https://i.ibb.co/21xRfkQ2/Screenshot-from-2025-09-19-22-41-46.png" alt="Screenshot-from-2025-09-19-22-41-46" border="0"></a><br>
# ngspice 
$sudo apt install ngspice<br>
[sudo] password for manohar-g: <br>
Reading package lists... Done<br>
Building dependency tree... Done<br>
<a href="https://ibb.co/bMS9cgw4"><img src="https://i.ibb.co/673CjR9K/Screenshot-from-2025-09-19-22-45-25.png" alt="Screenshot-from-2025-09-19-22-45-25" border="0"></a><br />
# magic
$ sudo apt-get install m4<br>
$ sudo apt-get install tcsh<br>
$ sudo apt-get install csh<br>
$ sudo apt-get install libx11-dev<br>
$ sudo apt-get install tcl-dev tk-dev<br>
$ sudo apt-get install libcairo2-dev<br>
$ sudo apt-get install mesa-common-dev libglu1-mesa-dev<br>
$ sudo apt-get install libncurses-dev
git clone https://github.com/RTimothyEdwards/magic
cd magic<br>
$./configure<br>
$make<br>
$make install <br>
<a href="https://ibb.co/ZpBRNknm"><img src="https://i.ibb.co/Rk3G7Vxy/Screenshot-from-2025-09-19-22-54-03.png" alt="Screenshot-from-2025-09-19-22-54-03" border="0"></a><br>

# OpenLANE
$sudo apt-get update<br>
$sudo apt-get upgrade<br>
$sudo apt install -y build-essential python3 python3-venv python3-pip make git<br> 
$sudo apt install apt-transport-https ca-certificates curl software-properties-common -y<br>
$curl -fsSL https://download.docker.com/linux/ubuntu/gpg | \
sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg<br>
$echo \
  "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] \
  https://download.docker.com/linux/ubuntu \
  $(lsb_release -cs) stable" | \
  sudo tee /etc/apt/sources.list.d/docker.list > /dev/null<br>
$sudo apt install docker-ce docker-ce-cli containerd.io -y<br>
$sudo apt update<br>
$sudo apt install docker-compose-plugin -y<br>
$docker compose version<br>
$sudo usermod -aG docker $USER
newgrp docker<br>
$sudo reboot<br>



# Check 
$git --version<br>
$docker --version<br>
$python3 --version<br>
$python3 -m pip --version<br>
$make --version<br>
$python3 -m venv -h<br> 

<a href="https://ibb.co/DPRtZbNC"><img src="https://i.ibb.co/HLHVj20z/Screenshot-from-2025-09-20-16-25-11.png" alt="Screenshot-from-2025-09-20-16-25-11" border="0"></a><br>
# PDKs and Tools 
$cd $HOME<br>
$git clone https://github.com/The-OpenROAD-Project/OpenLane<br>
$cd OpenLane <br>
$./venv/bin/ciel list --pdk-family sky130<br>
$ls -ld ~/.ciel<br>
$sudo chown -R manohar-g:manohar-g ~/.ciel<br>
$./venv/bin/ciel ls-remote --pdk-family sky130<br>
<a href="https://ibb.co/tpzSSCbJ"><img src="https://i.ibb.co/9HhJJYqr/Screenshot-from-2025-09-20-18-32-29.png" alt="Screenshot-from-2025-09-20-18-32-29" border="0"></a><br />
$./venv/bin/ciel enable --pdk-family sky130 0fe599b2afb6708d281543108caf8310912f54af<br>
<a href="https://ibb.co/d4SGV6FT"><img src="https://i.ibb.co/LdMnc6mF/Screenshot-from-2025-09-20-18-35-10.png" alt="Screenshot-from-2025-09-20-18-35-10" border="0"></a><br>

$ls ~/.ciel/sky130A<br>
$make test<br>
<a href="https://ibb.co/5XDLkm03"><img src="https://i.ibb.co/WN9f0ZhX/Screenshot-from-2025-09-20-18-52-06.png" alt="Screenshot-from-2025-09-20-18-52-06" border="0"></a><br />
# <centare>Ready to Start Your Designs</centare>
