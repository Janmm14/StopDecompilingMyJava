# Entry-005
This is a pretty well known one. When the class signature (which is how generics are stored) is set
to garbage data, multiple decompilers will crash on attemping to decompile. This is known to cause
random signature-read errors by the JVM.

## JD-GUI
JD-GUI crashes on attempting to decompile the class.

#### Scoring
Consistency: 10  
Practicality: 5  
Decompiler Inaccuracy: 5  
Total score: 0.67  

#### Patch Date
2019-05-13

## Procyon
Procyon crashes on attempting to decompile the class.

#### Scoring
Consistency: 10  
Practicality: 5  
Decompiler Inaccuracy: 5  
Total score: 0.67  

#### Patch Date
N/A

## CFR
CFR &lt; 0.138 crashes on attempting to decompile the class.

#### Scoring
Consistency: 10  
Practicality: 5  
Decompiler Inaccuracy: 5  
Total score: 0.67  

#### Patch Date
2018-12-14

## javap
javap crashes on attempting to disassemble the class.

#### Scoring
Consistency: 10  
Practicality: 5  
Decompiler Inaccuracy: 5  
Total score: 0.67  

#### Patch Date
N/A