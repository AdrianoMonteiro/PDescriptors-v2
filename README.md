# PDescriptors-v2
New implementation for PDescriptors - Extract features from tables and input signals

This is a new version (v2) of PDescritors, a collection of Pure Data patches for features extraction from audio signals. 

In this version, the algorithms of PDescriptors operates in two modes: 

1. in real-time mode ("rt" flag): PDescriptor's algorithms extract features  directly from input PD audio signals. It operates in the samplerate set in PD audio properties (such as in the previous versions fo PDescritors). 
2. in table mode ("table" flag): PDescriptor's algorithms extract features as fast as possible from a audio sample recorded in a PD array (which means much faster than in PD samplerate).

Work to be done: 

Import all PDescriptors patches from version 1.2 to the  model of this version and create help patches consistent with version 2 propoerties. 

The patch "modelo.pd" is a template for V2 implementations. Use and modify it as necessary to adapt V1.2 algorithms to the main idea of V2 (i.e. merge rt and table modes in one algorithm). 

New feature algorithms or other functional contributions are also welcome. 

