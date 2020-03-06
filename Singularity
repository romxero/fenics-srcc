Bootstrap: docker
From: ubuntu:18.04

%labels
Author "Randall Cab White - rcwhite@stanford.edu"

#########
#%setup
#########

##Just grabbing default packages from ubuntu repository
%post



apt-get -ym update
apt-get -ym install fenics python-pip python3-pip libatlas-base-dev libatlas3-base libopenblas-base libopenblas-dev libhdf5-dev

pip install pandas numpy matplotlib scipy

#%runscript


%environment
	export IMAGE_NAME="fenics"



