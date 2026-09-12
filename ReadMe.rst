==============
Project2win by maili woo bell
==============

A modern, feature-rich, cross-platform firmware development
environment for the UEFI and PI specifications from www.uefi.org.

>
Core CI Build Status
--------------------

====================================== ================= ================ ===================
 Host Type & Toolchain                 Build Status      Test Status      Code Coverage
====================================== ================= ================ ===================
Windows_VS_                            |WindowsCiBuild|  |WindowsCiTest|  |WindowsCiCoverage|
Ubuntu_GCC_                            |UbuntuCiBuild|   |UbuntuCiTest|   |UbuntuCiCoverage|
Windows_CLANGPDB_                      |WinClgCiBuild|   |WinClgCiTest|   |WinClgCiCoverage|
Ubuntu_CLANGPDB_                       |UbuClgCiBuild|   |UbuClgCiTest|   |UbuClgCiCoverage|
Ubuntu_CLANGDWARF_                     |UbuCdwCiBuild|   |UbuCdwCiTest|   |UbuCdwCiCoverage|
====================================== ================= ================ ===================

`More CI Build information 

Platform CI Build Status
------------------------

Microsoft Windows Visual Studio (VS)
````````````````````````````````````

============================= ================= ============= ============= ==============
 Toolchain                    CONFIG            DEBUG         RELEASE       NOOPT
============================= ================= ============= ============= ==============
EmulatorPkg_Win_VS_           | X64             |em64d|       |em64r|       |em64n|
|                             | X64 FULL        |em64fd|      |em64fr|      |em64fn|
OvmfPkg_Win_VS_               | X64             |op64d|       |op64r|       |op64n|
============================= ================= ============= ============= ==============

Microsoft Windows CLANGPDB
``````````````````````````

============================= ================= ============= ============= ==============
 Toolchain                    CONFIG            DEBUG         RELEASE       NOOPT
============================= ================= ============= ============= ==============
EmulatorPkg_Win_CLANGPDB_     | X64             |emW64cd|     |emW64cr|     |emW64cn|
|                             | X64 FULL        |emW64cfd|    |emW64cfr|    |emW64cfn|
============================= ================= ============= ============= ==============



License Details
---------------

The majority of the content in the EDK II open source  upstream projects as git submodules
that are covered by additional licenses.

-  `BaseTools/Source/C/BrotliCompress/brotli <https://github.com/google/brotli/blob/666c3280cc11dc433c303d79a83d4ffbdd12cc8d/LICENSE>`__
-  `CryptoPkg/Library/OpensslLib/openssl <https://github.com/openssl/openssl/blob/e2e09d9fba1187f8d6aafaa34d4172f56f1ffb72/LICENSE>`__
-  `CryptoPkg/Library/MbedTlsLib/mbedtls <https://github.com/Mbed-TLS/mbedtls/blob/8c89224991adff88d53cd380f42a2baa36f91454/LICENSE>`__
-  `MdeModulePkg/Library/BrotliCustomDecompressLib/brotli <https://github.com/google/brotli/blob/666c3280cc11dc433c303d79a83d4ffbdd12cc8d/LICENSE>`__
-  `MdeModulePkg/Universal/RegularExpressionDxe/oniguruma <https://github.com/kkos/oniguruma/blob/abfc8ff81df4067f309032467785e06975678f0d/COPYING>`__
-  `UnitTestFrameworkPkg/Library/CmockaLib/cmocka <https://github.com/tianocore/edk2-cmocka/blob/f5e2cd77c88d9f792562888d2b70c5a396bfbf7a/COPYING>`__
-  `UnitTestFrameworkPkg/Library/GoogleTestLib/googletest <https://github.com/google/googletest/blob/86add13493e5c881d7e4ba77fb91c1f57752b3a4/LICENSE>`__
-  `UnitTestFrameworkPkg/Library/SubhookLib/subhook <https://github.com/tianocore/edk2-subhook/blob/83d4e1ebef3588fae48b69a7352cc21801cb70bc/LICENSE.txt>`__
-  `RedfishPkg/Library/JsonLib/jansson <https://github.com/akheron/jansson/blob/2882ead5bb90cf12a01b07b2c2361e24960fae02/LICENSE>`__
-  `MdePkg/Library/BaseFdtLib/libfdt <https://github.com/devicetree-org/pylibfdt/blob/f39368a217496d32c4091a2dba4045b60649e3a5/BSD-2-Clause>`__
-  `MdePkg/Library/MipiSysTLib/mipisyst <https://github.com/MIPI-Alliance/public-mipi-sys-t/blob/aae857d0d05ac65152ed24992a4acd834a0a107c/LICENSE>`__
-  `SecurityPkg/DeviceSecurity/SpdmLib/libspdm <https://github.com/DMTF/libspdm/blob/main/LICENSE.md>`__
-  `TcgTpmPkg/Library/TpmLib/TPM <https://github.com/TrustedComputingGroup/TPM/blob/main/LICENSE>`__

The EDK II Project is composed of packages. The maintainers for each package
are listed in `Maintainers.txt <Maintainers.txt>`__.

Resources
---------

-  `TianoCore <http://www.tianocore.org>`__
-  `EDK
   II <https://www.tianocore.org/tianocore-wiki.github.io>`__
-  `Getting Started with EDK
   II <https://www.tianocore.org/tianocore-wiki.github.io/development/tutorials-howto/getting_started_with_edk_ii.html>`__
-  `Mailing
   Lists <https://www.tianocore.org/tianocore-wiki.github.io/community/communications/mailing_lists.html>`__
-  `How To
   Contribute <https://www.tianocore.org/tianocore-wiki.github.io/development/contribution-guides/how_to_contribute.html>`__
-  `Release
   Planning <https://www.tianocore.org/tianocore-wiki.github.io/releases-history/planning-roadmaps/edk_ii_release_planning.html>`__

Code Contributions
------------------

To make a contribution to a TianoCore project, follow these steps.

#. Create a change description in the format specified below to
    use in the source control commit log.
#. Your commit message must include your ``Signed-off-by`` signature
#. Submit your code to the TianoCore project using the process
    that the project documents on its web page. If the process is
    not documented, then submit the code on development email list
    for the project.
#. It is preferred that contributions are submitted using the same
    copyright license as the base project. When that is not possible,
    then contributions using the following licenses can be accepted:

-  Apache License, Version 2.0: https://opensource.org/license/apache-2-0/
-  BSD (2-clause): https://opensource.org/license/BSD-2-Clause
-  BSD (3-clause): https://opensource.org/license/BSD-3-Clause
-  MIT: https://opensource.org/license/MIT
-  Python-2.0: https://opensource.org/license/Python-2.0
-  Zlib: https://opensource.org/license/Zlib

For documentation:

-  FreeBSD Documentation License
    https://www.freebsd.org/copyright/freebsd-doc-license.html

Contributions of code put into the public domain can also be accepted.

Contributions using other licenses might be accepted, but further
review will be required.

Developer Certificate of Origin
-------------------------------

Your change description should use the standard format for a
commit message, and must include your ``Signed-off-by`` signature.

In order to keep track of who did what, all patches contributed must
include a statement that to the best of the contributor's knowledge
they have the right to contribute it under the specified license.

The test for this is as specified in the `Developer's Certificate of
Origin (DCO) 1.1 <https://developercertificate.org/>`__. The contributor
certifies compliance by adding a line saying

Signed-off-by: Developer Name developer@example.org

where ``Developer Name`` is the contributor's real name, and the email
address is one the developer is reachable through at the time of
contributing.

::

    Developer's Certificate of Origin 1.1

    By making a contribution to this project, I certify that:

    (a) The contribution was created in whole or in part by me and I
        have the right to submit it under the open source license
        indicated in the file; or

    (b) The contribution is based upon previous work that, to the best
        of my knowledge, is covered under an appropriate open source
        license and I have the right under that license to submit that
        work with modifications, whether created in whole or in part
        by me, under the same open source license (unless I am
        permitted to submit under a different license), as indicated
        in the file; or

    (c) The contribution was provided directly to me by some other
        person who certified (a), (b) or (c) and I have not modified
        it.

    (d) I understand and agree that this project and the contribution
        are public and that a record of the contribution (including all
        personal information I submit with it, including my sign-off) is
        maintained indefinitely and may be redistributed consistent with
        this project or the open source license(s) involved.

Sample Change Description / Commit Message
------------------------------------------

::

    From: Contributor Name <contributor@example.com>
    Subject: [Repository/Branch PATCH] Pkg-Module: Brief-single-line-summary

    Full-commit-message

    Signed-off-by: Contributor Name <contributor@example.com>

Notes for sample patch email
````````````````````````````

-  The first line of commit message is taken from the email's subject
   line following ``[Repository/Branch PATCH]``. The remaining portion
   of the commit message is the email's content.
-  ``git format-patch`` is one way to create this format

Definitions for sample patch email
``````````````````````````````````

-  ``Repository`` is the identifier of the repository the patch applies.
    This identifier should only be provided for repositories other than
    ``edk2``. For example ``edk2-BuildSpecification`` or ``staging``.
-  ``Branch`` is the identifier of the branch the patch applies. This
    identifier should only be provided for branches other than
   ``edk2/master``.
    For example ``edk2/UDK2015``,
   ``edk2-BuildSpecification/release/1.27``, or
    ``staging/edk2-test``.
-  ``Module`` is a short identifier for the affected code or
   documentation. For example ``MdePkg``, ``MdeModulePkg/UsbBusDxe``, ``Introduction``, or
    ``EDK II INF File Format``.
-  ``Brief-single-line-summary`` is a short summary of the change.
-  The entire first line should be less than ~70 characters.
-  ``Full-commit-message`` a verbose multiple line comment describing
    the change. Each line should be less than ~70 characters.
-  ``Signed-off-by`` is the contributor's signature identifying them
    by their real/legal name and their email address.

Submodules
----------

The current submodules used in EDK II are in `.gitmodules <.gitmodules>`__.

To get a full, buildable EDK II repository, use following steps of git
command

.. code-block:: bash

  git clone https://github.com/tianocore/edk2.git
  cd edk2
  git submodule update --init
  cd ..

If there are updates for submodules, use the following git commands to get
the latest submodules code.

.. code-block:: bash

  cd edk2
  git pull
  git submodule update

Note: When cloning submodule repos, '--recursive' option is not
recommended. EDK II itself will not use any code or features from
submodules within the submodules listed above. So using '--recursive' adds a
dependency on being able to reach servers we do not actually want
any code from, as well as needlessly downloading code we will not
use.

.. ===================================================================
.. This is a bunch of directives to make the README file more readable
.. ===================================================================

.. CoreCI

.. _Windows_VS: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=74&branchName=master
.. |WindowsCiBuild| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FWindows%20VS%20-%20CI?branchName=master
.. |WindowsCiTest| image:: https://img.shields.io/azure-devops/tests/tianocore/edk2-ci/74.svg
.. |WindowsCiCoverage| image:: https://img.shields.io/badge/coverage-coming_soon-blue

.. _Ubuntu_GCC: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=76&branchName=master
.. |UbuntuCiBuild| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FUbuntu%20GCC%20-%20CI?branchName=master
.. |UbuntuCiTest| image:: https://img.shields.io/azure-devops/tests/tianocore/edk2-ci/76.svg
.. |UbuntuCiCoverage| image:: https://img.shields.io/badge/coverage-coming_soon-blue

.. _Windows_CLANGPDB: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=89&branchName=master
.. |WinClgCiBuild| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FWindows%20-%20CLANGPDB?branchName=master
.. |WinClgCiTest| image:: https://img.shields.io/azure-devops/tests/tianocore/edk2-ci/89.svg
.. |WinClgCiCoverage| image:: https://img.shields.io/badge/coverage-coming_soon-blue

.. _Ubuntu_CLANGPDB: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=83&branchName=master
.. |UbuClgCiBuild| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FUbuntu%20-%20CLANGPDB?branchName=master
.. |UbuClgCiTest| image:: https://img.shields.io/azure-devops/tests/tianocore/edk2-ci/83.svg
.. |UbuClgCiCoverage| image:: https://img.shields.io/badge/coverage-coming_soon-blue

.. _Ubuntu_CLANGDWARF: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=82&branchName=master
.. |UbuCdwCiBuild| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FUbuntu%20-%20CLANGDWARF?branchName=master
.. |UbuCdwCiTest| image:: https://img.shields.io/azure-devops/tests/tianocore/edk2-ci/82.svg
.. |UbuCdwCiCoverage| image:: https://img.shields.io/badge/coverage-coming_soon-blue

.. ArmVirtPkg

.. _ArmVirtPkg_Ubuntu_GCC: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=79&branchName=master
.. |avAArch64du| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FArmVirtPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20QEMU_AARCH64_DEBUG
.. |avAArch64ru| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FArmVirtPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20QEMU_AARCH64_RELEASE
.. |avAArch64nu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FArmVirtPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20QEMU_AARCH64_NOOPT

.. _ArmVirtPkg_Ubuntu_CLANGPDB: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=88&branchName=master
.. |avAArch64cpu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FArmVirtPkg%20-%20Ubuntu%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20QEMU_AARCH64_DEBUG
.. |avAArch64rpu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FArmVirtPkg%20-%20Ubuntu%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20QEMU_AARCH64_RELEASE
.. |avAArch64npu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FArmVirtPkg%20-%20Ubuntu%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20QEMU_AARCH64_NOOPT

.. _ArmVirtPkg_Ubuntu_CLANGDWARF: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=84&branchName=master
.. |avAArch64cdu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FArmVirtPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20QEMU_AARCH64_DEBUG
.. |avAArch64rdu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FArmVirtPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20QEMU_AARCH64_RELEASE
.. |avAArch64ndu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FArmVirtPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20QEMU_AARCH64_NOOPT

.. EmulatorPkg

.. |TCBZ_2639| image:: https://img.shields.io/github/issues/tianocore/edk2?baseUrl=https%3A%2F%2Fgithub.com
.. _TCBZ_2639: https://github.com/tianocore/edk2/issues/9905

.. _EmulatorPkg_Win_VS: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=73&branchName=master
.. _EmulatorPkg_Ubuntu_GCC: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=78&branchName=master
.. _EmulatorPkg_Win_CLANGPDB: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=90&branchName=master
.. _EmulatorPkg_Ubuntu_CLANGDWARF: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=85&branchName=master

.. |em64d| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20VS%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_DEBUG
.. |em64r| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20VS%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_RELEASE
.. |em64n| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20VS%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_NOOPT
.. |em64fd| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20VS%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_DEBUG
.. |em64fr| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20VS%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_RELEASE
.. |em64fn| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20VS%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_NOOPT

.. |em64du| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_DEBUG
.. |em64ru| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_RELEASE
.. |em64nu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_NOOPT
.. |em64fdu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_DEBUG
.. |em64fru| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_RELEASE
.. |em64fnu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_NOOPT

.. |emW64cd| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_DEBUG
.. |emW64cr| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_RELEASE
.. |emW64cn| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_NOOPT
.. |emW64cfd| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_DEBUG
.. |emW64cfr| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_RELEASE
.. |emW64cfn| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Windows%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_NOOPT

.. |emU64cdd| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_DEBUG
.. |emU64cdr| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_RELEASE
.. |emU64cdn| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_NOOPT
.. |emU64cdfd| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_DEBUG
.. |emU64cdfr| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_RELEASE
.. |emU64cdfn| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FEmulatorPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20EmulatorPkg_X64_FULL_NOOPT

.. OvmfPkg

.. _OvmfPkg_Win_VS: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=72&branchName=master
.. _OvmfPkg_Ubuntu_GCC: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=77&branchName=master
.. _OvmfPkg_Ubuntu_CLANGPDB: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=87&branchName=master
.. _OvmfPkg_Ubuntu_CLANGDWARF: https://dev.azure.com/tianocore/edk2-ci/_build/latest?definitionId=86&branchName=master

.. |op64d| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Windows%20VS%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_DEBUG
.. |op64r| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Windows%20VS%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_RELEASE
.. |op64n| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Windows%20VS%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_NOOPT

.. |op64du| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_DEBUG
.. |op64ru| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_RELEASE
.. |op64nu| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Ubuntu%20GCC%20-%20CI?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_NOOPT

.. |opU64cpd| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Ubuntu%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_DEBUG
.. |opU64cpr| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Ubuntu%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_RELEASE
.. |opU64cpn| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Ubuntu%20-%20CLANGPDB?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_NOOPT

.. |opU64cdd| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_DEBUG
.. |opU64cdr| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_RELEASE
.. |opU64cdn| image:: https://dev.azure.com/tianocore/edk2-ci/_apis/build/status%2FCI%2FOvmfPkg%20-%20Ubuntu%20-%20CLANGDWARF?branchName=master&jobName=Platform_CI&configuration=Platform_CI%20OVMF_X64_NOOPT



this was created by principle owner of apache 2.0 2026.

._collect 0.0.0.0, always pull, automatically 
al website of the United States government

Here’s how you know

Here's how you know

Menu
FPKI Ecosystem Changes
Upcoming FBCA G5 Migration
The FBCA G4 is going to be replaced by the FBCA G5 starting on August 27th, 2026. This is to comply with CA certificate lifecycle management and Federal cryptographic strength requirements and may require applications to update their trust stores with new intermediate CA certificates to ensure interoperability with FBCA affiliate issued credentials.

You can find additional information regarding the full migration plan in the following FPKI announcement to include a link containing instructions on distributing needed cross-certificates to include the new DoD Interoperability Root CA 3.


Non-DoD Applications that Authenticate CAC! Note that in parallel with the FBCA G5 migration, DoD will be migrating from their Interoperability Root CA 2 to a newer Interoperability Root CA 3. IRCA3 will also be issuing new cross-certificates to the DoD and ECA Root CAs which may need to be included in your application trust stores for continued CAC authentication support.

This page contains information that is helpful in identifying changes in the Federal PKI. This includes identifying PIV issuing CA and operational changes such as URL endpoints and system outages.

FPKI Announcements - Hot topics impact the Federal PKI.
FPKI Graph - The FPKI Graph displays the relationships between the certification authorities in the Federal PKI (FPKI) ecosystem
PIV Issuer Information - List of active PIV issuing CAs with end entity certificate distribution points.
FPKI System Change and Notification - List of changes to FPKI CA endpoint URL such as Certificate Revocation List Distribution Points, Online Certificate Status Protocol (OCSP) endpoints and other CA certificate activity.
FPKI Announcements
These announcements and hot topics concern Federal Public Key Infrastructure changes that may affect your agency’s operations. Announcements are removed after three years.

Title	Date	Description
FBCA G5 Migration Plan	August 12, 2026	The FBCA G5 migration plan, this will impact relying party trust store configurations.
CCT Tool v1.0.9 Release	October 16, 2024	An updated version of the CCT Tool was released with the addition of current federal and test trust chains to the JavaKey Store (JKS) to reduce false positives/errors.
CPCT Tool v2.0.1 Update	July 05, 2024	To provide current security updates to the software components used in the CPCT Tool, a new version of the tool has been released (v2.0.1).
CPCT Tool Update:
New Certificate Profiles	October 18, 2023	The Certificate Profiles used by the CPCT Tool have updated to Common SSP (v2.5) and FBCA (v3.2). CPCT Tool update required.
Public Trust PKI Certificate Policy	February 10, 2023	The US Federal Public Trust PKI Certificate Policy v1.0 is now archived and undergoing revision.
CPCT Tool Update	January 12, 2023	The Certificate Profile Conformance Tool (CPCT) has been updated to account for Common Profiles v2.2.
CPCT Tool transition from Cloud.gov	October 21, 2022	The Certificate Profile Conformance Tool (CPCT) will transition from Cloud.gov.
FCPCA SIA LDAP Decommissioning	October 11, 2022	The FPKIMA will be decommissioning the LDAP service associated with the old FCPCA root's SIA repository.
New FPKI Tools Available	May 18, 2021	Release announcement for the Federal PKI Card Conformance Tool (CCT) and Certificate Profile Conformance Tool (CPCT).
FPKI Graph
Last Update: September 08, 2026


Search graph
 
The FPKI Graph displays the relationships between the certification authorities in the Federal PKI (FPKI) ecosystem. It graphically depicts how each certification authority links to another, through cross-certificates, subordinate certificates, or bridge CAs. A P7B file of the weekly FPKI Graph run is available here. Note that the Common Policy Root Certificate is included in this bundle. Before installing it in a trusted root store, verify the authenticity of the certificate by comparing the thumbprint as documented here

The Federal Common Policy Certification Authority (CA) G2 (“COMMON”) is shown at the center of the graph, and the rings of dots represent the outbound CAs.

Click on any dot in the graph to see a CA’s inbound and outbound CA certificates.
Inbound means the CA certificate is signed by the Inbound CA.
Outbound means the CA has signed the Outbound CA certificate.
The Search function is on the upper right-hand corner.
The Zoom scroll bar is in the upper left-hand corner.
You cannot download the certificates from the graph. To download the certificates, you need to retrieve the certificates from the Authority Information Access (AIA) or Subject Information Access (SIA) URIs. (See below for more information on AIAs and SIAs.)

How the FPKI Graph Works
The graph uses information published in each CA certificate’s AIA and SIA extensions. This is public information:  all CAs in the FPKI are required to publish and maintain their AIA certificate bundles.

All CA and End Entity certificates that have a certificate path (trust chain) to COMMON will have an AIA extension in their public certificates. An AIA extension contains a URI where you can find the certificate(s) used to sign that CA or End Entity certificate.

Most CA certificates will also have an SIA extension with a URI to the CA certificates that have been issued by that CA. For example, you can find the SIA for COMMON at http://repo.fpki.gov/fcpca/caCertsIssuedByfcpcag2.p7c.

To use this SIA, retrieve the file (.p7c) using the link above and open it.
You will find a dozen or more certificates that are issued by COMMON (Root) to other intermediate or issuing CAs.
The SIA URIs from each of these certificates can then be retrieved to find the next set of signed certificates.
PIV Issuer Information
The page lists the certification authorities currently used for Personal Identity Verification (PIV), PIV-Interoperable (PIV-I), or Derived PIV (dPIV) authentication certificates for federal government departments and agencies. Agency system administrators can leverage this list to configure systems and services for cross-government trust.

Active Issuing CA Certificate Details
These CAs associated with these CA certificates are actively issuing PIV , PIV-I and/or Derived PIV authentication certificates.

Department of Veterans Affairs CA
Subject: OU = Department of Veterans Affairs CA, OU = Certification Authorities, OU = Department of Veterans Affairs, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 633456a0
Validity: May 20, 2023 to May 20, 2033
SHA-1 Hash: d81577f94652b7a9eb9d0d4602060f7d16492413
CRL DP: http://pki.treas.gov/VA_CA3.crl
DHS CA4
Subject: OU = DHS CA4, OU = Certification Authorities, OU = Department of Homeland Security, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 63345616
Validity: April 29, 2023 to April 29, 2033
SHA-1 Hash: d8624442ccc91753aca89698f2cbcdf59f32d3f1
CRL DP: http://pki.treas.gov/DHS_CA4.crl
DoD Issuing CAs
DoD ID CA-81

Subject: CN = DOD ID CA-81, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 6, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 0176
Validity: January 23, 2025 to January 23, 2031
SHA-1 Hash: bdfa9d0ab661fb1880207d7bbbf0f0817c7315f3
CRL DP: http://crl.disa.mil/crl/DODIDCA_81.crl
DoD ID CA-80

Subject: CN = DOD ID CA-80, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 6, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 0175
Validity: January 23, 2025 to January 23, 2031
SHA-1 Hash: 6aaef812197286acfdb5136858e0509a1dc7f90f
CRL DP: http://crl.disa.mil/crl/DODIDCA_80.crl
DoD ID CA-79

Subject: CN = DOD ID CA-79, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 6, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 0174
Validity: January 23, 2025 to January 23, 2031
SHA-1 Hash: 87887e73aec1b617d417e420b82c0e046dc5cce0
CRL DP: http://crl.disa.mil/crl/DODIDCA_79.crl
DoD ID CA-78

Subject: CN = DOD ID CA-78, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 6, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 0173
Validity: January 23, 2025 to January 23, 2031
SHA-1 Hash: 38aea6b42463b3ed2ac6497506f8dc90dc0aa656
CRL DP: http://crl.disa.mil/crl/DODIDCA_78.crl
DoD ID CA-73

Subject: CN = DOD ID CA-73, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 6, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 49
Validity: May 16, 2023 to May 15, 2029
SHA-1 Hash: ce68b25fa532d959935aeb2c29e1358531903535
CRL DP: http://crl.disa.mil/crl/DODIDCA_73.crl
DoD ID CA-72

Subject: CN = DOD ID CA-72, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 6, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 48
Validity: May 16, 2023 to May 15, 2029
SHA-1 Hash: ce68b25fa532d959935aeb2c29e1358531903535
CRL DP: http://crl.disa.mil/crl/DODIDCA_72.crl
DoD ID CA-70

Subject: CN = DOD ID CA-70, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 6, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 47
Validity: May 16, 2023 to May 15, 2029
SHA-1 Hash: 6005f7e39bd475ce11dd4b74bc85b9c7182b9a53
CRL DP: http://crl.disa.mil/crl/DODIDCA_70.crl
DoD ID CA-71

Subject: CN = DOD ID CA-71, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 3, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 070c
Validity: December 6, 2022 to December 6, 2028
SHA-1 Hash: d398c9f709ea787f46afb2b31cbd964628afa3d4
CRL DP: http://crl.disa.mil/crl/DODIDCA_71.crl
DoD ID CA-65

Subject: CN = DOD ID CA-65, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 3, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 054c
Validity: June 1, 2021 to June 2, 2027
SHA-1 Hash: 2838d25ae351654a094f00348f4bd0ea3178d871
CRL DP: http://crl.disa.mil/crl/DODIDCA_65.crl
DoD ID CA-64

Subject: CN = DOD ID CA-64, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 3, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 054b
Validity: June 1, 2021 to June 2, 2027
SHA-1 Hash: d9991bd1e89ae5a8b1143c3c37f01103779b8db7
CRL DP: http://crl.disa.mil/crl/DODIDCA_64.crl
DoD ID CA-63

Subject: CN = DOD ID CA-63, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 3, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 050f
Validity: April 6, 2021 to April 7, 2027
SHA-1 Hash: 67b75160bd8299e2342f46cc8ac634b2afb33768
CRL DP: http://crl.disa.mil/crl/DODIDCA_63.crl
DoD ID CA-62

Subject: CN = DOD ID CA-63, OU = PKI, OU = DoD, O = U.S. Government, C = US
Issuer: CN = DoD Root CA 3, OU = PKI, OU = DoD, O = U.S. Government, C = US
Serial #: 054a
Validity: April 6, 2021 to April 7, 2027
SHA-1 Hash: 14f4cfd8364412a6a27e5bba82c5342ff9b337a7
CRL DP: http://crl.disa.mil/crl/DODIDCA_62.crl
Entrust NFI Medium Assurance SSP CA
Subject: OU = Entrust NFI Medium Assurance SSP CA, OU = Certification Authorities, O = Entrust, C = US
Issuer: OU = Entrust Managed Services NFI Root CA, OU = Certification Authorities, O = Entrust, C = US
Serial #: 4aa96994
Validity: October 12, 2021 to September 12, 2030
SHA-1 Hash: 31ef454001a9162cbc0498866f8d49070b799191
CRL DP: http://nfimediumsspweb.managed.entrust.com/CRLs/NFIMEDIUMSSPCA2.crl
Entrust NFI Medium Assurance SSP CA
Subject: OU = Entrust NFI Medium Assurance SSP CA, OU = Certification Authorities, O = Entrust, C = US
Issuer: OU = Entrust Managed Services NFI Root CA, OU = Certification Authorities, O = Entrust, C = US
Serial #: 4aa8b9ea
Validity: May 16, 2017 to November 16, 2027
SHA-1 Hash: 4b8818edc75e6983904ee71513c85e165f2d897c
CRL DP: http://nfimediumsspweb.managed.entrust.com/CRLs/NFIMEDIUMSSPCA1.crl
Entrust Managed PKI Federal Issuing CA G2
Subject: OU = Entrust Managed PKI Federal Issuing CA G2, OU = Certification Authorities, O = Entrust, C = US
Issuer: OU = Entrust Managed PKI Federal Root CA G2, OU = Certification Authorities, O = Entrust, C = US
Serial #: 6c64ace173da144034b6b67769838a4c
Validity: June 28, 2024 to June 28, 2034
SHA-1 Hash: 3b94eeab90e1d577f4892705a35abaa076d78849
CRL DP: http://fedrootg2crl.managed.entrust.com/CRLs/FedSSPIssuingCAG2.crl
Entrust Managed Services SSP CA
Subject: OU = Entrust Managed Services SSP CA, OU = Certification Authorities, O = Entrust, C = US
Issuer: OU = Entrust Managed Services Root CA, OU = Certification Authorities, O = Entrust, C = US
Serial #: 4481b22f
Validity: July 11, 2023 to November 11, 2030
SHA-1 Hash: 19fea49c468760edce9600a9da9657b484734d24
CRL DP: http://sspweb.managed.entrust.com/CRLs/EMSSSPCA4.crl
Entrust Derived Credential SSP CA
Subject: OU = Entrust Derived Credential SSP CA, OU = Certification Authorities, O = Entrust, C = US
Issuer: OU = Entrust Managed Services Root CA, OU = Certification Authorities, O = Entrust, C = US
Serial #: 44817ba9
Validity: May 9, 2022 to July 9, 2029
SHA-1 Hash: b3ddc2d8bc6c88883ef4c292a1175b1a267e7c23
CRL DP: http://feddcsweb.managed.entrust.com/CRLs/FedDCSCA1.crl
FTI Certification Authority
Subject: OU = FTI Certification Authority, OU = FTI PKI Trust Infrastructure, O = Foundation for Trusted Identity, C = US
Issuer: OU = STRAC Bridge Root Certification Authority, OU = STRAC PKI Trust Infrastructure, O = STRAC, C = US
Serial #: 0141
Validity: January 7, 2023 to January 6, 2026
SHA-1 Hash: cbbc028fae9da429e1b34a4ccadd9cd815b40d9c
CRL DP: http://pki.fti.org/fti_ca/crl/FTICA.crl
HHS-FPKI-Intermediate-CA-E1
Subject: CN = HHS-FPKI-Intermediate-CA-E1, OU = Certification Authorities, OU = HHS, O = U.S. Government, C = US
Issuer: OU = Entrust Managed Services Root CA, OU = Certification Authorities, O = Entrust, C = US
Serial #: 44817282
Validity: February 23, 2022 to July 23, 2029
SHA-1 Hash: 492a40e6477eed5c39a58c24d6f3d5bffb0e1083
CRL DP: http://hhspkicrl.managed.entrust.com/CRLs/HHSEntrustCA2.crl
NASA Operational CA
Subject: OU = NASA Operational CA, OU = Certification Authorities, OU = NASA, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 6334559d
Validity: April 8, 2023 to April 8, 2033
SHA-1 Hash: 67ddd6f4be3b69568f591bf999db2ef3085f7c5b
CRL DP: https://pki.treas.gov/NASA_Operational_CA5.crl
Senate PIV-I CA G6
Subject: CN = Senate PIV-I CA G5 PROD, OU = Office of the Sergeant at Arms, OU = U.S. Senate, O = U.S. Government, C = US
Issuer: CN = WidePoint NFI Root 2, OU = Certification Authorities, O = WidePoint, C = US
Serial #: 68b3a082d2817ab76183e371219642aa20e7816a
Validity: April 25, 2023 to December 31, 2030
SHA-1 Hash: 1d946c2a1724ed576e436604f02dbfc3f2dccff0
CRL DP: http://crl-server.orc.com/CRLs/SenatePIVICAG6.crl
Social Security Administration Certification Authority
Subject: OU = Social Security Administration Certification Authority, OU = SSA, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 6334553a
Validity: March 4, 2023 to March 4, 2033
SHA-1 Hash: 533f881329d791d5a197d4dd71bafae6f7222733
CRL DP: https://pki.treas.gov/SSA_CA4.crl
Treasury OCIO CA
Subject: OU = OCIO CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 6334565d
Validity: Mau 20, 2023 to May 20, 2033
SHA-1 Hash: 3f3a62c0d4b5a2d70054ea7de33c9a691937ec02
CRL DP: https://pki.treas.gov/OCIO_CA6.crl
U.S. Department of State PIV CA3
Subject: OU = U.S. Department of State PIV CA3, OU = Certification Authorities, OU = PIV, OU = Department of State, O = U.S. Government, C = US
Issuer: CN = U.S. Department of State AD Root CA, CN = AIA, CN = Public Key Services, CN = Services, CN = Configuration, DC = state, DC = sbu,
Serial #: 650cccc7
Validity: March 13, 2025 to March 13, 2035
SHA-1 Hash: 4a4e87b992264fbf9f92fcc4ab89840df6fcb89d
CRL DP: http://crls.pki.state.gov/crls/DoSADPKIPIVCA3.crl
U.S. Department of State PIV CA2
Subject: OU = U.S. Department of State PIV CA2, OU = Certification Authorities, OU = PIV, OU = Department of State, O = U.S. Government, C = US
Issuer: CN = U.S. Department of State AD Root CA, CN = AIA, CN = Public Key Services, CN = Services, CN = Configuration, DC = state, DC = sbu,
Serial #: 51b0b97f
Validity: January 24, 2020 to January 24, 2030
SHA-1 Hash: 68A4E9AB7A1FB8FB85316A770FF9CA874C020724
CRL DP: http://crls.pki.state.gov/crls/DoSADPKIPIVCA2-1.crl
U.S. Department of State DPC CA
Subject: CN = U.S.-Department-of-State-DPC-CA, DC = derived, DC = state, DC = sbu
Issuer: CN = U.S. Department of State AD Root CA, CN = AIA, CN = Public Key Services, CN = Services, CN = Configuration, DC = state, DC = sbu
Serial #: 5fc530ec
Validity: November 30, 2020 to November 30, 2030
SHA-1 Hash: a6e9c11ad29fc006ed65b06db32e36a927cb3a48
CRL DP: http://crls.pki.state.gov/crls/DoSDPCCA.crl
U.S. Department of Transportation Agency CA G7
Subject: CN = U.S. Department of Transportation CA G7, OU = U.S. Department of Transportation, O = U.S. Government, C = US
Issuer: CN = WidePoint SSP Intermediate CA 2, O = ORC PKI, C = US
Serial #: 37301ecbedc855076a07addbf2f56b1940cd9651
Validity: May 17, 2025 to February 13, 2035
SHA-1 Hash: 4078fe87dc2f655ce2b3220c2ff7fb25c29e1772
CRL DP: http://crl-server.orc.com/CRLs/DoTAgencyCAG7.crl
USPTO INTR CA1
Subject: CN = USPTO_INTR_CA1, CN = AIA, CN = Public Key Services, CN = Services, CN = Configuration, DC = uspto, DC = gov
Issuer: CN = USPTO_INTR_CA1, CN = AIA, CN = Public Key Services, CN = Services, CN = Configuration, DC = uspto, DC = gov
Serial #: 162a8a8ddfb79fa3460a7a92765926fb108fd6aa
Validity: October 19, 2023 to October 19, 2026
SHA-1 Hash: 02ecec9eb7229055c57caeaade6f1ae056fb4327
CRL DP: http://ipki.uspto.gov/IPKI/CRLs/CombinedCRL4.crl
WidePoint ORC NFI 4
Subject: CN = WidePoint ORC NFI 4, OU = Certification Authorities, O = WidePoint, C = US
Issuer: CN = WidePoint NFI Root 2, OU = Certification Authorities, O = WidePoint, C = US
Serial #: 3581750bd6e26757bcb9e0a4513da84946587ebf
Validity: February 18, 2020 to February 18, 2030
SHA-1 Hash: 5a95aea990a7aec492134a5b437cf3324f260793
CRL DP: http://crl.xca.xpki.com/CRLs/XTec_PIVI_CA1.crl
WidePoint ORC SSP 5
Subject: CN = WidePoint ORC SSP 5, O = ORC PKI, C = US
Issuer: CN = Federal Common Policy CA G2, OU = FPKI, O = U.S. Government, C = US
Serial #: 210b3f17db750e616eb25f3f0b4933e5a98c449b
Validity: November 19, 2020 to November 5, 2030
SHA-1 Hash: 80f4731a60fd5f2eb0468d0629310daa50ad210d
CRL DP: http://crl-server.orc.com/CRLs/WIDEPOINTORCSSP5.crl
WidePoint NFI CA 5
Subject: CN = WidePoint NFI CA 5, O = ORC PKI, C = US
Issuer: CN = WidePoint NFI Root 2, OU = Certification Authorities, O = WidePoint, C = US
Serial #: 671b355a39b72fddf67723f142ed726d4e0307b4
Validity: April 17, 2020 to April 18, 2030
SHA-1 Hash: 52a2b89934a8f53719d620697496a6eb82a06e13
CRL DP: http://crl-server.orc.com/CRLs/WIDEPOINTNFI5.crl
WidePoint NFI CA 6
Subject: CN = WidePoint NFI CA 6, O = ORC PKI, C = US
Issuer: CN = WidePoint NFI Root 2, OU = Certification Authorities, O = WidePoint, C = US
Serial #: 15707f8b78d4594f0fdc0d7884241c7659dd83e3
Validity: February 3, 2021 to December 31, 2030
SHA-1 Hash: 8a17d236acb45af809c0a4555f7142d82ae08736
CRL DP: http://crl-server.orc.com/CRLs/WIDEPOINTNFI6.crl
Maintenance Mode Issuing CA Certificate Details
These CA certificates have issued PIV, PIV-I and/or Derived PIV authentication certificates previously and are in maintenance mode only. Agency system administrators may need to include these CAs in configurations to ensure continued operation with valid credentials.

Department of Veterans Affairs CA (1 of 2)
Subject: OU = Department of Veterans Affairs CA, OU = Certification Authorities, OU = Department of Veterans Affairs, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 5ccb3215
Validity: June 22, 2019 to June 22, 2029
SHA-1 Hash: 76cc898f03eb0fc7e0877aac30a0c1340bb34879
CRL DP: http://pki.treas.gov/VA_CA2.crl
Department of Veterans Affairs CA (2 of 2)
Subject: OU = Department of Veterans Affairs CA, OU = Certification Authorities, OU = Department of Veterans Affairs, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 4e398179
Validity: October 17, 2015 to October 17, 2025
SHA-1 Hash: e2edb0df1fe8068717a08e38741b5bc4c38029d0
CRL DP: http://pki.treasury.gov/VA_CA1.crl
DHS CA4
Subject: OU = DHS CA4, OU = Certification Authorities, OU = Department of Homeland Security, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 5ccb31ca
Validity: June 6, 2019 to June 6, 2029
SHA-1 Hash: 58085a64e181573f4fd917c5c021eb1cf344dd5f
CRL DP: http://pki.treas.gov/DHS_CA3.crl
DoD Issuing CAs (Expired CAs have been removed)
Entrust Managed Services SSP CA
Subject: OU = Entrust Managed Services SSP CA, OU = Certification Authorities, O = Entrust, C = US
Issuer: OU = Entrust Managed Services Root CA, OU = Certification Authorities, O = Entrust, C = US
Serial #: 448107b6
Validity: August 13, 2019 to July 13, 2029
SHA-1 Hash: 722e8abbe6b66e47d1bcec3c7ec47aa5bbe4d3c5
CRL DP: http://sspweb.managed.entrust.com/CRLs/EMSSSPCA3.crl
NASA Operational CA
Subject: OU = NASA Operational CA, OU = Certification Authorities, OU = NASA, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 5ccb3196
Validity: May 4 2019 to May 4 2029
SHA-1 Hash: f504012b1fe57b4381e3bf5ba9f491144ed76ee1
CRL DP: https://pki.treas.gov/NASA_Operational_CA4.crl
NRC SSP Agency CA G4
Subject: CN = NRC SSP Agency CA G4, OU = U.S. Nuclear Regulatory Commission, O = U.S. Government, C = US
Issuer: CN = DigiCert Federal SSP Intermediate CA - G5, O = DigiCert, Inc., C = US
Serial #: 3a905c654791b26551e3b7077f27aa33
Validity: December 17, 2018 to December 12, 2028
SHA-1 Hash: 1a03581dcf159d206accd7bdd176c788a0862353
CRL DP: http://pki-crl.symauth.com/ca_23580f2ce24946eab1793386d8e1b510/LatestCRL.crl
NRC PROD G6 Fed SSP CA
Subject: CN = NRC SSP Agency CA G4, OU = U.S. Nuclear Regulatory Commission, O = U.S. Government, C = US
Issuer: CN = DigiCert Federal SSP Intermediate CA - G5, O = DigiCert, Inc., C = US
Serial #: 55C7AC031A83BEF41BAA8A73A68BC0CE
Validity: April 12, 2022 to March 15, 2032
SHA-1 Hash: 1F060CE528BDDFB3B429B7C76EEEB0F8B0FBC60A
CRL DP: http://pki-crl.symauth.com/ca_ce00affea217ea042db01becf36671a4/LatestCRL.crl
Senate PIV-I CA G5 PROD
Subject: CN = Senate PIV-I CA G5 PROD, OU = Office of the Sergeant at Arms, OU = U.S. Senate, O = U.S. Government, C = US
Issuer: CN = DigiCert Class 3 SSP Intermediate CA - G4, O = DigiCert, Inc., C = US
Serial #: 2eec611f22944f9d462a5a8bbee06485
Validity: March 24, 2021 to August 18, 2030
SHA-1 Hash: 816a2c18db2e5673205d17a98d0fffef8bf4777e
CRL DP: http://pki-crl.symauth.com/ca_fc26996dc726cf860f12aa77d4270098/LatestCRL.crl
Social Security Administration Certification Authority
Subject: OU = Social Security Administration Certification Authority, OU = SSA, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 5bf45959
Validity: April 7, 2019 to April 7, 2029
SHA-1 Hash: 897a79fd488d426d6c50d0ba026f698bca3334f4
CRL DP: https://pki.treas.gov/SSA_CA3.crl
Treasury OCIO CA
Subject: OU = OCIO CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Issuer: OU = US Treasury Root CA, OU = Certification Authorities, OU = Department of the Treasury, O = U.S. Government, C = US
Serial #: 5ccb31fe
Validity: June 22, 2019 to June 22, 2029
SHA-1 Hash: e651a5dc6a1305613a22e46548e1666650c2825f
CRL DP: https://pki.treas.gov/OCIO_CA5.crl
U.S. Department of Education Agency CA - G5
Subject: CN = U.S. Department of Education Agency CA - G5, OU = U.S. Department of Education, O = U.S. Government, C = US
Issuer: CN = DigiCert Federal SSP Intermediate CA - G5, O = DigiCert, Inc., C = US
Serial #: 5C23B98A6FF5F543B2768F6D19556C4C
Validity: June 9, 2020 to December 12, 2028
SHA-1 Hash: 6F48424AE8A01C2A77213A9D34F5761DAACD9EAC
CRL DP: http://pki-crl.symauth.com/ca_db1ff205d5a9b79af46c7896d15cb2a9/LatestCRL.crl
U.S. Department of State PIV CA2
Subject: OU = U.S. Department of State PIV CA2, OU = Certification Authorities, OU = PIV, OU = Department of State, O = U.S. Government, C = US
Issuer: CN = U.S. Department of State AD Root CA, CN = AIA, CN = Public Key Services, CN = Services, CN = Configuration, DC = state, DC = sbu,
Serial #: 51b02402
Validity: August 3, 2016 to August 3, 2026
SHA-1 Hash: ffe07fb428bcef4bf38ebbfae1e42339e03e7756
CRL DP: http://crls.pki.state.gov/crls/DoSADPKIPIVCA2.crl
U.S. Department of Transportation Agency CA G6
Subject: CN = U.S. Department of Transportation CA G6, OU = U.S. Department of Transportation, O = U.S. Government, C = US
Issuer: CN = WidePoint SSP Intermediate CA, O = ORC PKI, C = US
Serial #: 309b986d8a7fb52a7ea7dc858693c5e06e7ae33a
Validity: May 4, 2023 to April 7, 2033
SHA-1 Hash: 7b6dcb34ab284ec897f0ffe1a2f8f95082f09c74
CRL DP: http://crl-server.orc.com/CRLs/DoTAgencyCAG6.crl
U.S. Department of Transportation Agency CA G5
Subject: CN = U.S. Department of Transportation CA G5, OU = U.S. Department of Transportation, O = U.S. Government, C = US
Issuer: CN = DigiCert Federal SSP Intermediate CA - G5, O = DigiCert, Inc., C = US
Serial #: 0ed81c303ea3566787faca36899a931a
Validity: March 4, 2019 to December 12, 2028
SHA-1 Hash: b1d05e5b9e025ea4b3b3e30dc3f45a19f9ec51f6
CRL DP: http://onsite-crl.pki.digicert.com/USDepartmentofTransportationFAAPIVG5/LatestCRL.crl
USPTO INTR CA1
Subject: CN = USPTO_INTR_CA1, CN = AIA, CN = Public Key Services, CN = Services, CN = Configuration, DC = uspto, DC = gov
Issuer: CN = USPTO_INTR_CA1, CN = AIA, CN = Public Key Services, CN = Services, CN = Configuration, DC = uspto, DC = gov
Serial #: 4c296f47
Validity: April 7, 2018 to December 7, 2029
SHA-1 Hash: bc67b9e65ee05c3742c27187259ded3e6112a587
CRL DP: http://ipki.uspto.gov/IPKI/CRLs/CombinedCRL3.crl

https://github.com/mai-cyber88910  libandroid-stub


E
gh repo clone wooiesaysx3-afk/Release

