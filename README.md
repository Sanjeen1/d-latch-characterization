# d-latch-characterization
This repository contains the characterization of a CMOS D-Latch using SPICE simulations both pre and post layout. The project demonstrates latch behavior through circuit simulation and waveform analysis. Netlists, simulation setups, spice file, LTSPICE schematic are included using TSMC 180nm.

## Positive level D latch layout

![dd](https://github.com/user-attachments/assets/6cf3694f-c301-4adb-8440-d6422be417eb)

## Waveform

![Screenshot 2025-08-21 112147](https://github.com/user-attachments/assets/0b401336-346a-4821-b2fc-7b5af71dc08c) 

## Clock to Q delay 

<img width="637" height="61" alt="image" src="https://github.com/user-attachments/assets/a5981e0b-9cdc-42c6-a5c0-4537b144cd7f" />

# D latch Schematic -

## Negative Level D latch -

**Schematic**

<img width="843" height="377" alt="image" src="https://github.com/user-attachments/assets/e6c07bfe-e9d6-4296-9583-7a70a540e51a" />

**Waveform**

![waveform Negative level d latch](https://github.com/user-attachments/assets/361d9376-1a8a-4733-a3ac-4f95b0d4cf63)

## Positive Level D latch -

<img width="879" height="385" alt="image" src="https://github.com/user-attachments/assets/bbeb19b2-a780-438a-9745-5d60fea2901a" />

![Positive D-latch waveform](https://github.com/user-attachments/assets/43ed8c1e-99f2-41c1-b12d-844347233382)

# D flip flop (Positive edge/rising edge trigger) - 

<img width="1168" height="391" alt="image" src="https://github.com/user-attachments/assets/e3e236ae-1d1e-4301-87ee-617d2ad23e3a" />

**check for before rising edge -**

**When output q have a glitch due to setup/hold time window -**

**Glitch when data change before 9 ns of rising edge -**
![9ns created a glitch](https://github.com/user-attachments/assets/2a8e470c-619e-4067-811f-b3c9b4478426)
Here we can see check for all rising edge. For example when we see this rising edge as marked above the d is changing nearly 9 ns and we can notice that ouput get glitch or chopped off d data. 
![glitch r](https://github.com/user-attachments/assets/2e095fc3-19e8-4ba4-82f3-8c92967f5178)

**Glitch free when data change before 10 ns of rising edge -**
![10ns setup time](https://github.com/user-attachments/assets/fc183cef-5cea-47c9-af3c-4679d37b90b5)
when the data is changing 10 ns before the rising edge trhen there is no glitch.
![glitch free](https://github.com/user-attachments/assets/ea4d66b2-1600-4e4e-8a03-b275ff9b9c67)


**Similarly check for after rising edge -**

**Glitch if data change at 18ns after rising edge -**

![glitch](https://github.com/user-attachments/assets/38a11b86-191c-4f72-af7d-271e283561aa)
Glitch when data is changing after 18ns.
![holtime glitch](https://github.com/user-attachments/assets/b781aa31-3bc2-4b58-94a8-d910c0d55118)

**Glitch free when data change at 20ns after rising edge -**

![hold time 20 ns ](https://github.com/user-attachments/assets/8f06f096-d274-4097-9881-c49699d396cb)
Glich free when data is changing after 20ns.
![glitch free](https://github.com/user-attachments/assets/ceb71747-8bec-4f57-8b18-c08931c16cf4)

# Perfect capturing at the output- 
When data is not violating any timing constrant then perfect capture of data at ouput will occur
![Screenshot 2025-08-22 084741](https://github.com/user-attachments/assets/d3471472-e3e4-4b3a-94a1-1463755adbbf)











