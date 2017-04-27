system-view    
sysname R1    
interface g0/0/0     
ip address 10.0.0.1 24     
quit    
interface g0/0/1     
ip address 10.0.1.1 24     
quit     
interface LoopBack 0    
ip address 10.0.3.1 24    
quit    
rip 1    
network 10.0.0.0     
quit     
