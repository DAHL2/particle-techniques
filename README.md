# Setting up

cc7 #(to change to centos7)  
mkdir EPPT  
cd EPPT  
source /cvmfs/sft.cern.ch/lcg/views/LCG_94/x86_64-centos7-gcc8-opt/setup.sh  
git clone https://github.com/knikolop-bham/MPAGS-EPPT-B5.git  
mkdir build  
cd build  
cmake ../MPAGS-EPPT-B5/  
make -j 10  
./exampleB5 run1.mac  
