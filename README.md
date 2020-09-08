# basic_hft_trader
Hi, thanks for stopping by. This is a project I am currently working on to build a low-latency trading platform using an FPGA.

## Inspiration
For my end of year group project at university, we were tasked with learning and utlising a PYNQ Xilinx FPGA in order to build a high frame rate image processer. This invovled the use of key hardware optimisations such as loop pipelining and loop unrolling. I had read around the trading infrastructre banks use and thought it would be cool to optimise some models in C using custom hardware. Over time, I got the idea to optimise more and more sophisticated models which eventually led me to the idea of trading using an FPGA. Currently, my platform has a measured latency of roughly 1650 nanoseconds.

## What I have achieved so far:
So far, I have completed the hardware infrastructure to faciliate trades so that complex models can be run over it. I have also set up the ethernet ports to allow the board to connect the internet.

## Current Development
At the moment, I am currently looking at ways to add a GUI to visualise stock movemnts and set trading decisions (such as auto-sell/auto-buy after a stock has reached a certain price) using the Jupiter Notebook. 

### Stay tuned for updates!
