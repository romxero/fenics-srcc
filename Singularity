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
apt-get -ym install fenics

#%runscript


%environment
	export IMAGE_NAME="fenics"



