.. _installing:

.. |nbsp| unicode:: 0xA0
   :trim:

.. |reg| unicode:: U+00AE
   :ltrim:

========================================
Installing SUSE Manager |reg| Evaluation
========================================

-------------------
System Requirements
-------------------

To install and run SUSE Linux Enterprise Server (SLES) and SUSE Manager |reg|
Evaluation on a virtual machine, the minimum system requirements are:

* CPU: Multi-core, 64-bit (x86-64)
* RAM: 16 |nbsp| GB or more
* Disk space: 100 |nbsp| GB or more

------------
Installation
------------

1. Download the ISO image from the `Downloads page <https://www.suse.com/products/suse-manager/download/>`_

2. Create a Customer Center account. You will be emailed a registration code
   which you will require later.

3. Validate the MD5 Checksum of the file you have downloaded by switching to
   to the download directory and executing this command:

   .. code-block:: bash

      $ md5sum SLE-12-SP2-Server-DVD-x86_64-GM-DVD1.iso

   Check the resulting code against the corresponding MD5 checksum on the
   Downloads Page.

4. Using your preferred Virtual Machine Manager, create a new virtual machine
   with these specifications:

   =====================  ====================================================
   Installation Method    Local installation media (downloaded ISO image)
   Operating System       Linux
   Memory                 4096 |nbsp| MB
   CPUs                   2
   Storage                3 |nbsp| GB
   =====================  ====================================================

5. Follow the prompts to install SLES. When prompted, enter your registration
   key.

6. At the ``Extension and Module selection`` page, select ``SUSE Manager
   Server``.

   .. image:: /Images/SUSEManager_ExtensionSelection.png
      :scale: 50%
      :align: center
      :alt: A screenshot of the SUSE Manager Extension and Module Selection
            screen with SUSE Manager server selected

7. Complete the SLES installation and launch SUSE Manager |reg| Evaluation.
