Get Started
===========

Installing the nBox UI required the installation of the **nboxui** package.
Please find below instructions according to the Linux distribution.

Debian/Ubuntu
~~~~~~~~~~~~~

.. code-block:: console

   apt install nboxui


You can run the service as

.. code-block:: console

   service cockpit start

   
RedHat/Rocky Linux
~~~~~~~~~~~~~~~~~~

.. code-block:: console

   yum install nboxui
   systemctl enable --now cockpit.socket

After installing the package, it is possible to access the GUI connecting to the 
machine's IP address using a browser on port 9090 (e.g. http://192.168.1.1:9090).

ntop Branding
~~~~~~~~~~~~

After nboxui installation copy on the target machine the files present in this directory
https://github.com/ntop/cockpit-ntop/tree/dev/branding to /usr/share/cockpit/branding/ubuntu/

.. code-block:: console

   git clone https://github.com/ntop/cockpit-ntop.git
   cd cockpit-ntop
   cp -r branding/* /usr/share/cockpit/branding/ubuntu/



