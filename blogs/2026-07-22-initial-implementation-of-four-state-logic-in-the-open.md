---
title: "Initial implementation of four-state logic in the open source Verilator RTL simulator"
url: "https://chipsalliance.org/news/initial-implementation-verilator/"
date: "2026-07-22"
feed_url: "https://chipsalliance.org/news/index.xml"
---
Verilator is an extremely popular open source simulator, used in a number of ASIC and FPGA workflows where its default two-state operation model (i.e. only representing the logic values of 1 and 0 ) is enough. While two-state simulation is much faster and memory-efficient, and sufficient for many applications such as functional testing and debugging, when dealing with initialization bugs or high-impedance states, four-state simulation (which supports logic values of 1 , 0 , x and z ) becomes necessary.
