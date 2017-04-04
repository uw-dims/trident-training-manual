.. _systemadministration:

System Administration Activities
================================

This chapter introduces the fundamentals of administering the underlying Debian
Linux operating system and packages using Ansible and playbooks produced and
published by the DIMS project team. For the purposes of training, this chapter
will use the published ``local`` deployment variables and playbook templates
that will install Trident and related tools in Virtualbox Vagrant virtual
machines on a base Ubuntu 14.04 development system. (This is the platform used
by DIMS developers to do development and development testing on laptops or
development servers.)

The basic steps covered in the sections below are:

* Cloning the necessary repositories.

* Creating SSH key pairs.

* Running Ansible playbooks to establish a control host.

* Creating required Virtualbox box files using Packer.

* Building Vagrants from Virtualbox box files.

* Running Ansible playbooks to change configuration or update packages.

At the end of these steps, you will have a running Trident instance in local
virtual machines with which you can practice customizing Trident or
upgrade/update component packages in an isolated deployment that will not
impact your production deployment. Once you are comfortable with these tasks,
you will be able to administer a production system with greater confidence and
reliability.

.. todo::

   Add other sections as necessary. Walk through all the steps at
   enough detail to make them work so that the end result is a
   local Trident system that matches the one shown in the screen
   captures in this manual.

..
