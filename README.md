warehouse
=========
A common place for OpenStack-Citrix related files.


tty.tgz
=======
http://github.com/downloads/citrix-openstack/warehouse/tty.tgz

Cirros Image for OpenStack on XenServer
=======================================
This image is a cirros image (actually a tgz -ed vhd) for the XenServer/OpenStack combo.
 * [cirros-0.3.0-x86_64-disk.vhd.tgz](https://github.com/downloads/citrix-openstack/warehouse/cirros-0.3.0-x86_64-disk.vhd.tgz)

You can upload it to glance with:

    glance image-create --name cirros \
    --copy-from=https://github.com/downloads/citrix-openstack/warehouse/cirros-0.3.0-x86_64-disk.vhd.tgz \
    --container-format=ovf --disk-format=vhd

The instructions to create such image could be found at:
 * [Convert a raw image to XenServer – VHD](http://blogs.citrix.com/2012/10/04/convert-a-raw-image-to-xenserver-vhd/)
 * [Upload custom images to a XenServer powered OpenStack Cloud](http://blogs.citrix.com/2012/10/17/upload-custom-images-to-a-xenserver-powered-openstack-cloud/)


Guest utilities
===============
6.1 debs
--------
 * [i386](https://github.com/downloads/citrix-openstack/warehouse/xe-guest-utilities_6.1.0-1033_i386.deb)
 * [amd64](https://github.com/downloads/citrix-openstack/warehouse/xe-guest-utilities_6.1.0-1033_amd64.deb)

5.6 debs
--------
 * [i386](https://github.com/downloads/citrix-openstack/warehouse/xe-guest-utilities_5.6.100-651_i386.deb)
 * [amd64](https://github.com/downloads/citrix-openstack/warehouse/xe-guest-utilities_5.6.100-651_amd64.deb)
