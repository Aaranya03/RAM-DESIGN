COMPANY : CODTECH IT SOLUTIONS

NAME : AARANYA M

INTERN ID : CT04DH854

DOMAIN : VLSI

DURATION : 4 WEEKS

MENTOR : NEELA SANTHOSH

DESCRIPTION OF TASK-2:As part of the CodTech Internship Program, Task-2 involves designing a simple synchronous RAM (Random Access Memory) module and verifying its functionality through simulation. This task focuses on implementing memory logic in digital circuits and understanding how read and write operations work using a Hardware Description Language like Verilog or VHDL.

In this project, you are expected to create a synchronous RAM that operates based on a clock signal. The RAM should support both read and write operations depending on a control signal (wr_en). Your design must include:

Clock input (clk)

Write enable (wr_en)

Address input

Data input (din)

Data output (dout)


The memory should store data at a given address when wr_en is high (write operation), and provide data from a given address when wr_en is low (read operation).

Once the RAM module is coded, you must build a testbench to validate its behavior. The testbench should simulate multiple scenarios including:

Writing values to different memory addresses

Reading back the values

Checking if the read data matches the written data


For simulation, I have used ModelSim, a widely used HDL simulation tool. Using ModelSim, the design was compiled, simulated, and tested using waveform analysis. The simulation results successfully demonstrated:

Clock-synchronized write operations

Accurate data retrieval from memory

Stable and error-free functionality


ModelSim's waveform viewer helped verify the timing and correctness of read/write operations, ensuring that the RAM behaves as expected in different test cases.

 Deliverables:

1. Verilog Code for the RAM module


2. Verilog Testbench code


3. ModelSim Simulation Output (waveform screenshots or log)


4. (Optional) Short explanation or README of the design and observations


#OUTPUT#

<img width="1895" height="981" alt="Image" src="https://github.com/user-attachments/assets/7d24a1d9-458f-4de4-8c97-47836cb7be3b" />
