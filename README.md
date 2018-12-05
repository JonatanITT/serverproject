Production
==========

All files in Production have gone through a GitLab pipeline to test all script, and they should now be ready to be packed by Packer and deployed

Files in directories
-------------------------------------------------------

*  JumphostExternal
    * .sh script for update + upgrade + ufw?
    * .sh script for configure Jumphost
    * .sh script for adding key
    * .json file for packer
    * jumphostexternal.vmdk (image for deployment)

*  LibreNMS
    * .sh script for update + upgrade + ufw?
    * .sh script for configure LibreNMS
    * .sh script for adding key
    * .sh script for configure Mariana DB
    * .sh script for configure PHP
    * .sh script for configure Web Server
    * .json file for packer
    * librenms.vmdk (Image for deployment)

* ReverseWebProxy with Apache2
    * .sh script for update + upgrade + ufw?
    * .sh script for installing and configuring Apache2 to do web proxy
    * .json file for packer
    * reversewebproxy.vmdk (Image for deployment)
