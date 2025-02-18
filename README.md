# [Browse Project Railgun](https://github.enablery.org/shri/railgun/)

# Railgun - "Making Hardware Softer" (instead of making software harder)
## DSL to compile BigData AI/ML Application to FPGA/ASIC Gates

### Railgun: High Performance FPGA supports ETL-free Big Data for Machine Learning: 

Railgun is a domain specific language compiler which was developed as a
Source-to-Verilog generator.

Railgun takes specification of computations such as dynamic SerDe and
matrix multiplication written in a DSL hosted in Scala, and complies them
into machine-generated Verilog.

This resulting Verilog could be synthesized into FPGA without any further
human touch. The resulting FPGA implementation of SerDe and matrix processor
kernels for ML were significantly faster than corresponding software in
CPU or GPU. Typically, we were able to process data at 40Gbps in FPGA
compared to 8-10Gbs in Intel CPU.

Lightweight modular staging. was used to host the Railgun DSL in the Scala
enviroment. This allowed programs that resembled Scala to be directly
compiled into low-latency high-performance FPGA Verilog

This project was a collaboration with Michael deLorimier.

# [Browse Project Railgun](https://github.enablery.org/shri/railgun/)


