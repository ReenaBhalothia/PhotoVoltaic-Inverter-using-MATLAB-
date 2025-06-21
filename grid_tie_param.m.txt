
clc

f=50; % system frequency 
Vbase=380; %Grid voltage 
fs = 99*f; % switching frequency 

Ts_Power=1/(fs*100); % sampling time 

P= 50e3; % inverter power 


% this equations taken from MATLAB samples .
%Filter coil parameters 
Pbase=Vbase^2/P; 
RL=1.5e-3*Pbase;
L=0.15*Pbase/(2*pi*f);

%Filter capacitor parameters
Qc=0.1*P; 
Pc=Qc/50; 