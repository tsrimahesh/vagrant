# vagrant
steps to create a vagrant box from VirtualBox
vagrant package --base vmname
e.g:
vagrant package --base my-lubuntu-base-clone-docker

vagrant box add boxname package.box
e.g:
vagrant box add mylubuntubox package.box
