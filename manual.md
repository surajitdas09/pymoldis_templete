---
layout: default
---

# Content:
[1. STG](#stg)  
    >[1.1 Query1](#query1)               
    >[1.2 Query2](#query2)         
    >[1.3 Query3](#query3)               
    >[1.4 Query4](#query4)
    >[1.1 Query5](#query5)
    >[1.2 Query6](#query6)
    >[1.3 Query7](#query7)
    >[1.4 Query8](#query8)
    >[1.1 Query9: Get SMILES](#query9)
    >[1.2 Query10: Get svg](#query10)

[1. XPS](#xps)  
[2. NMR](#nmr)

## <a name="stg">1. S1-T1 Gap</a>

This section explains how to find a singlet-triplet gap (STG) of an molecule from an molecular coordinates. 

### <a name="query1">1.1 Query1: Define bigqm7w dataset</a>
```
df = pymoldis.get_data('bigqm7w_S1T1)
df.describe()
```
### <a name="query">1.2 Query2</a>
### <a name="query">1.3 Query3</a>
### <a name="query">1.4 Query4</a>
### <a name="query">1.5 Query5</a>
### <a name="query">1.6 Query6</a>
### <a name="query">1.7 Query7</a>
### <a name="query">1.8 Query8</a>
### <a name="query">1.9 Query9: Get SMILES</a>
### <a name="query">1.10 Query10: Get svg</a>
```
SVG(image)
```

## <a name="xps">2. X-ray photoelectron spectroscopy </a>
Predictions from ML model.

## <a name="nmr">3. Nuclear Magnetic Resonance Spectroscopy </a>
Predictions from ML model.

For direct-ML model:
```
pym.direct_ml('target', 'descriptor', 'method', 'basis')
```

For delta-ML model:
```
pym.delta_ml('target', 'descriptor', 'method', 'xyz_file')
```

Available
ML: direct, delta
target: H, C, N, O, F
descriptor: 'bob3'
method: CCSD(T), CCSD, MP2

