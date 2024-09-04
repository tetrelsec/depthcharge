.. _resources:

Resources
=========


.. _blogtalks:

Blog Posts and Talks
--------------------

Below are the blog posts and talks created by the original author of Depthcharge. These provide some insights into the motivations of the project and some higher-level methodologies. However, the API and command-line tools may change over time; always refer to the :ref:`index` for the most up-to-date information.

* NCC Group Blog Post: `Sinking U-Boots with Depthcharge`_  (via `archive.org <https://web.archive.org/web/20200730010820/https://research.nccgroup.com/2020/07/22/depthcharge/>`__)
* Hardwear.io Webinar: `...Effective Exploitation of Boot-time Security Debt`_
* NCC Group Blog Post: `...U-Boot Configuration Auditing Introduced in v0.2.0`_ (via `archive.org <https://web.archive.org/web/20201216143734/https://research.nccgroup.com/2020/12/16/depthcharge-v0-2-0>`__)
* OSFC 2020 Talk: `Guiding Engineering Teams Toward a More Secure Usage of U-Boot`_

.. _Sinking U-Boots with Depthcharge: https://research.nccgroup.com/2020/07/22/depthcharge
.. _...Effective Exploitation of Boot-time Security Debt: https://www.youtube.com/watch?v=fTKMi3Is5x8
.. _...U-Boot Configuration Auditing Introduced in v0.2.0: https://research.nccgroup.com/2020/12/16/depthcharge-v0-2-0
.. _Guiding Engineering Teams Toward a More Secure Usage of U-Boot: https://vimeo.com/showcase/7884533/video/488134063


Official U-Boot Documentation
-----------------------------

The `U-Boot`_ project contains a ton of great `documentation`_. When doing security auditing work and working with Depthcharge, you may find the following resources particularly helpful.

* `U-Boot talks`_
* `Command-line and Hush shell`_
* `Global Data structure`_ (see `global_data.h`_)
* `Exported functions for Standalone Applications`_ (see `exports.h`_ and `_exports.h <https://source.denx.de/u-boot/u-boot/-/blob/v2024.07-rc3/include/_exports.h>`_)
* `U-Boot scripts and the "source" command`_
* `FIT Image Format`_ and `FIT signature verification`_
* `Sandbox build target`_ - Great for fuzzing for command handlers

.. _U-Boot: https://source.denx.de/u-boot/u-boot
.. _documentation: https://docs.u-boot.org/en/latest
.. _U-Boot talks: https://docs.u-boot.org/en/latest/learn/talks.html
.. _Command-line and Hush shell: https://docs.u-boot.org/en/latest/usage/cmdline.html
.. _Global Data structure: https://docs.u-boot.org/en/latest/develop/global_data.html 
.. _global_data.h: https://source.denx.de/u-boot/u-boot/-/blob/v2024.07-rc3/include/asm-generic/global_data.h?ref_type=tags#L39
.. _Exported Functions for Standalone Applications: https://source.denx.de/u-boot/u-boot/-/blob/master/doc/README.standalone?ref_type=heads
.. _exports.h: https://source.denx.de/u-boot/u-boot/-/blob/v2024.07-rc3/include/exports.h
.. _U-Boot Scripts and the "source" command: https://docs.u-boot.org/en/latest/usage/cmd/source.html
.. _FIT image format: https://docs.u-boot.org/en/latest/usage/fit/source_file_format.html
.. _FIT signature verification: https://docs.u-boot.org/en/latest/usage/fit/signature.html
.. _Sandbox build target: https://docs.u-boot.org/en/latest/arch/sandbox/sandbox.html

