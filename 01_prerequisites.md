---
layout: page
title: Openstack
order: 1
---
# Using OpenStack

## Creating an instance on Openstack

A video tutorial to connect to OpenStack and launching an instance is [here](https://youtu.be/JIoFJBWTtlg)

To successfully create an instance you will need to select the following options:

### Log on details
* Domain:
* User name:
* Password:


### Openstack instance
Please name your instance something that you will remember - including your name is a good idea. Then follow the instructions using the following options:

* Boot source: _Instance Snapshot_
* Name: BIO3092-2020
* Flavour: _u1.xxlarge_

Once the instance has started remember to take note of the IP address (use Edit-Copy).

## Log onto your instance

A video tutorial to connect to your virtual machine using Terminal (mac) or MobaXterm (windows) is [here](https://youtu.be/qPPBjTSppvE)

The log in details are:
* User name: ubuntu
* Password: bio3092

Once you have successfully logged on, its time to begin the workshop!

# Using your own machine

It is strongly recommended that you use the Virtual Machine approach to complete this workshop described above. However, it will also be possible to use your own machine.

To successfully use your own machine you will need to:
* Install all required software
* Download the workshop data

## Required software

We will run the whole workshop in [R](https://www.r-project.org/). I recommend using an Integrated Development Environment (IDE) such as [RStudio](https://rstudio.com/), which has a lot of useful features such as package installation, script editor and panes for visualisation of the environment and images.

To complete the workshop you will need to install several packages:
* [Rsubread](https://bioconductor.org/packages/release/bioc/html/Rsubread.html) for alignment and counting
* [edgeR](https://bioconductor.org/packages/release/bioc/html/edgeR.html) for differential gene expression analysis
* [GOfuncR](https://www.bioconductor.org/packages/release/bioc/html/GOfuncR.html) for Gene Ontology enrichment

Follow the instructions on the above pages to install the packages.

## Downloading workshop data

A substantial amount of raw data is also required (~5-10GB) for this workshop. The easiest way to download this
