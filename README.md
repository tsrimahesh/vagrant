 VBoxManage list vms

# vagrant <br />
steps to create a vagrant box from VirtualBox <br />
vagrant package --base vmname <br />
If the vmname option does not work <br />
vagrant package --base uuid <br />
e.g: <br />
vagrant package --base my-lubuntu-base-clone-docker<br />
<br />
vagrant box add boxname package.box <br />
e.g: <br />
vagrant box add mylubuntubox package.box <br />
