AIM:

To implement SR flipflop using verilog and validating their functionality using their functional tables

SOFTWARE REQUIRED:

Quartus prime

THEORY

SR Flip-Flop SR flip-flop operates with only positive clock transitions or negative clock transitions. Whereas, SR latch operates with enable signal. The circuit diagram of SR flip-flop is shown in the following figure.
<img width="893" height="499" alt="Screenshot 2025-12-12 204843" src="https://github.com/user-attachments/assets/b2062f8f-237b-4bad-9047-5e46d81b0c72" />

This circuit has two inputs S & R and two outputs Qtt & Qtt’. The operation of SR flipflop is similar to SR Latch. But, this flip-flop affects the outputs only when positive transition of the clock signal is applied instead of active enable. The following table shows the state table of SR flip-flop.
<img width="992" height="528" alt="Screenshot 2025-12-12 204856" src="https://github.com/user-attachments/assets/8c310115-5623-4f02-9774-87bf785be3b3" />

Here, Qtt & Qt+1t+1 are present state & next state respectively. So, SR flip-flop can be used for one of these three functions such as Hold, Reset & Set based on the input conditions, when positive transition of clock signal is applied. The following table shows the characteristic table of SR flip-flop. Present Inputs Present State Next State
<img width="822" height="684" alt="Screenshot 2025-12-12 204909" src="https://github.com/user-attachments/assets/967955e4-248e-43ec-b702-6f16ddbcf8ee" />


By using three variable K-Map, we can get the simplified expression for next state, Qt+1t+1. The three variable K-Map for next state, Qt+1t+1 is shown in the following figure.

<img width="482" height="314" alt="Screenshot 2025-12-12 204918" src="https://github.com/user-attachments/assets/65ccb67b-9669-47d1-9f7a-69d2e0470e70" />

The maximum possible groupings of adjacent ones are already shown in the figure. Therefore, the simplified expression for next state Qt+1t+1 is Q(t+1)=S+R′Q(t)Q(t+1)=S+R′Q(t)

Procedure

Select Two Logic Gates

Cross-Couple the Gates

Assign Set and Reset Inputs

Understand Output Behavior

Power and Test the Circuit

PROGRAM

/* Program for flipflops and verify its truth table in quartus using Verilog programming. Developed by:YUVASREE S

RegisterNumber:25014102 */

RTL LOGIC FOR FLIPFLOPS

TIMING DIGRAMS FOR FLIP FLOPS

RESULTS:
Thus the SR flipflop using verilog and validating their functionality using their functional tables is implemented and verified.
