# basic_hft_trader
Hi, thanks for stopping by. This is a project I am currently working on to build a low-latency trading platform using an FPGA.

# Inspiration
For my end of year group project at university, we were tasked with learning and utlising a PYNQ Xilinx FPGA in order to build a high frame rate image processer. This invovled the use of key hardware optimisations such as loop pipelining and loop unrolling. After my exams, I thought it would be cool to try and use some of the knowledge I got from my group project and use it in order to optimise some basic maths models. Over time, I got the idea to optimise more and more sophisticated models and eventually I had the idea to make a full-on high frequency trader using Vivado HLS.

# Current Development
At the moment, I am currently looking to automate the pre-processing of market data so that it may finally be used over live market feed  - so it may take some time before I build a whole system capable of excecuting live trades! :)  But, I have passed through test data and the board has a latency of approximately 400 microseconds.
