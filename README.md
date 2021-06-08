# ns-3-dev-mptcp
ns-3-dev with mptcp intergration
Installations
Clone the MPTCP's repository
git clone https://github.com/Kashif-Nadeem/ns-3-dev-git

Configure and build
cd ns-3-dev-git
cd /.waf3-1.8.19-b1fc8f7baef51bd2db4c2971909a568d/waflib
gedit Node.py

Delete line 312 of Node.py 
CXXFLAGS="-Wall" ./waf configure build

Simulations
A simulation script is available here









