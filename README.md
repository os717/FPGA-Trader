# basic_hft_trader
Hi, thanks for stopping by. This is a project I am currently working on to build a low-latency trading platform using an FPGA.

## Inspiration
For my end of year group project at university, we were tasked with learning and utlising a PYNQ Xilinx FPGA in order to build a high frame rate image processer. This invovled the use of key hardware optimisations such as loop pipelining and loop unrolling. I had read around the trading infrastructre banks use and thought it would be cool to optimise some models using custom hardware.  Over time, I got the idea to optimise more and more sophisticated models which eventually led me to the idea of making a full-on high frequency trader using Vivado HLS.

## What I have achieved so far:
So far, I have completed and tested the hardware infrastructure and connected the project via ethernet to the interent.

## Current Development
At the moment, I am currently looking to automate the pre-processing of market data so that it may finally be used over live market feed  - so it may take some time before I build a whole system capable of excecuting live trades! :)  But, I have passed through test data and the board has a latency of roughly 7 ms. I hope to use Github to catalogue my work so far and track future updates. Stay tuned!
