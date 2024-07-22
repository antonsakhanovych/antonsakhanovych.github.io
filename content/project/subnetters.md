+++
title = 'Subnetters'
date = 2024-07-22T19:13:02-04:00
author = "Anton Sakhanovych"
description = "Subnetters is a simple and efficient program designed to divide a given network into subnets based on specified requirements. It supports quick and easy compilation and execution, making network segmentation straightforward."
+++

![Github Link](https://github.com/antonsakhanovych/subnetters)

### Quick Start

Copmpile

```sh
make
```

Run

```sh
./subnetters <ipv4> <cidr mask> <... list of subnet sizes/number of hosts>
# Example
> ./subnetters 192.168.0.0 21 167 126 120 18 9 1
----------------------
IP Address: 192.168.0.0
----------------------
----------------------
IP Address: 192.168.1.0
----------------------
----------------------
IP Address: 192.168.1.128
----------------------
----------------------
IP Address: 192.168.2.0
----------------------
----------------------
IP Address: 192.168.2.32
----------------------
----------------------
IP Address: 192.168.2.48
----------------------
----------------------
IP Address: 192.168.2.52
----------------------
```
