### EXPT NO 2 : SIMULATION OF AMPLITUDE SHIFT KEYING
### DATE :
### AIM:
 To implement ASK using MATLAB.
 SOFTWARE REQUIRED: MATLAB
 ### PROGRAM

 clc; clear all; close all; fc=input('Enter the freq of Sine Wave carrier:'); fp=input('Enter the
 freq of Periodic Binary pulse (Message):'); amp=input('Enter the amplitude (For Carrier &
 Binary Pulse Message):'); t=0:0.001:1; % For setting the sampling interval
 c=amp.sin(2pifct);% For Generating Carrier Sine wave subplot(3,1,1) %For Plotting The
 Carrier wave plot(t,c) xlabel('Time') ylabel('Amplitude') title('Carrier Wave')
 m=amp/2.square(2pifpt)+(amp/2);%For Generating Square wave message subplot(3,1,2)
 %For Plotting The Square Binary Pulse (Message) plot(t,m) xlabel('Time') ylabel('Amplitude')
 title('Binary Message Pulses') w=c.*m; % The Shift Keyed Wave subplot(3,1,3) %For Plotting
 The Amplitude Shift Keyed Wave plot(t,w) xlabel('Time') ylabel('Amplitude') title('Amplitide Shift Keyed Signal')

 
 INPUTS GIVEN TO GENERATE ASK MODULATED WAVE:
 Enter the freq of Sine Wave carrier:100 Enter the freq of Periodic Binary pulse (Message):10
 Enter the amplitude (For Both Carrier & Binary Pulse Message):4
 ### output
 ![Screenshot 2025-03-27 191610](https://github.com/user-attachments/assets/9dd80e41-10fc-4974-b3a8-88eb245b4e4c)

### RESULT
 Thus the generation of ASK was implemented using MATLAB
