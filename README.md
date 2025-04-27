# Space-Weather-Event-Analysis

## Dataset Format Example

```plaintext
  FORMAT OF THE SUBSETTED FILE
    
    ITEMS                      FORMAT   
     
 1 Year                          I4        
 2 Day                           I4        
 3 Hour                          I3        
 4 Minute                        I3        
 5 ID for IMF spacecraft         I3        
 6 ID for SW Plasma spacecraft   I3        
 7 Timeshift                     I7        
 8 BX, nT (GSE, GSM)             F8.2     ⌉
 9 BY, nT (GSM)                  F8.2     |
10 BZ, nT (GSM)                  F8.2     | 
11 Speed, km/s                   F8.1     |
12 Vx Velocity,km/s              F8.1     | ---- Solar Wind
13 Proton Density, n/cc          F7.2     |
14 Proton Temperature, K         F9.0     | 
15 Flow pressure, nPa            F6.2     |
16 Electric field, mV/m          F7.2     ⌋
17 Plasma beta                   F7.2      
18 S/C, Xgse,Re                  F8.2      
19 S/C, Ygse,Re                  F8.2      
20 S/c, Zgse,Re                  F8.2      
21 BSN location, Xgse,Re         F8.2      
22 BSN location, Ygse,Re         F8.2      
23 BSN location, Zgse,Re         F8.2      
24 AE-index, nT                  I6       ⌉
25 SYM/H, nT                     I6       |
26 ASY/H, nT                     I6       | ---- Earth Params
27 PCN-index                     F7.2     ⌋

```