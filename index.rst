.. title:: Nutanix .Next On Tour

.. toctree::
  :maxdepth: 2
  :caption: Hands On Labs
  :name: _hols
  :hidden:

  nutanix101/nutanix101
  calm_linux/calm_linux
  flow/flow
  era/era

.. toctree::
  :maxdepth: 2
  :caption: Optional Hands On Labs
  :name: _optional_hols
  :hidden:

  apis/apis

.. toctree::
  :maxdepth: 2
  :caption: Appendix
  :name: _appendix
  :hidden:

  appendix/glossary
  appendix/basics
  tools_vms/windows_tools_vm
  tools_vms/linux_tools_vm
  taskman/taskman

.. _getting_started:

---------------
Getting Started
---------------

Welcome to the .NEXT Hands On Labs! These labs are intended to give you working hands-on experience with the Nutanix platform and an introduction to a few of Nutanix's other offerings so you can experience the power of software-defined for yourself.

There will not be enough time to complete all labs. You can choose which labs to perform, but starting with Nutanix 101 is HIGHLY reccomended if you do not have prior Nutanix experience.

What's New
++++++++++

- Workshop updated for the following software versions:
    - AOS & PC 5.10.x


Initial Setup
+++++++++++++

- Connect to the Whats_NEXT wifi using the password **nutanix/4u**
- Take note of the *Passwords* being used.

Environment Details
+++++++++++++++++++

These labs are intended to be run in the Nutanix Hosted POC environment, but have been repurposed to run on local hardware. The environment will be provisioned with all necessary images, networks, and VMs required to complete the exercises.

Networking
..........

Information needed throughout labs:

Side A
......
- **Cluster Name** - NEXTLAB
- **Subnet** - 10.1.0.0
- **Prism Element/Cluster IP** - 10.1.31.22
- **Prism Central IP** - 10.1.31.35
- **AD Domain Controller** - 10.1.31.50


Side C
......
- **Cluster Name** - NEXTLAB3
- **Subnet** - 10.1.0.0
- **Prism Element/Cluster IP** - 10.1.31.92
- **Prism Central IP** - 10.1.31.96
- **AD Domain Controller** - 10.1.31.50

The clusters are configured with the following networks to be used for VMs:

.. list-table::
  :widths: 25 25 10 40
  :header-rows: 1

  * - Network Name
    - Address
    - VLAN
    - DHCP Scope
  * - Side A Primary
    - 10.1.0.1/19
    - 0
    - 10.1.1.2-10.1.15.253
  * - Side C Primary
    - 10.1.0.1/19
    - 0
    - 10.1.24.1-10.1.30.253

Credentials
...........

- **Prism Element Username** - nutanix
- **Prism Element Password** - Next2019!
- **Prism Central Username** - admin
- **Prism Central Password** - Next2019!
 




ALL LAB ATTENDEES ARE USING THE SAME CLUSTER!
+++++++++++++++++++++++++++++++++++++++++++++
BE A GOOD NEIGHBOR AND DON'T RUIN THE ENVIRONMENT FOR EVERYONE ELSE!
++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++++
If anyone breaks the environment, they will be tarred, feathered, and sent to the United States.
......................................................................................
