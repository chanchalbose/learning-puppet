# learning-puppet
Repository for puppet resources.
You can download mostlylinux72.ova from this url
http://download.mostlylinux.com/7/mostlylinux72.ova
mostlylinux72.ova appliance includes puppet-server and ansible.
For using it in VirtualBox download mostlylinux72.ova and then run Vitualbox
-> File -> Import Appliance.. and browse to the downloaded file.

If you want use mostlylinux72.ova in kvm use following commands 

tar xvf mostlylinux72.ova

qemu-img convert -f vmdk -O qcow2 mostlylinux72-disk1.vmdk mostlylinux72-disk1.qcow2
