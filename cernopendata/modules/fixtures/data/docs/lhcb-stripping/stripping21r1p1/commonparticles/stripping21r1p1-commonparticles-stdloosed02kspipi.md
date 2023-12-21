[[stripping21r1p1 lines]](./stripping21r1p1-index)

# StdLooseD02KsPiPi

**CombineParticles/StdLooseD02KsPiPi**

|                  |                                                                                                                                                                        |
|------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Inputs           | ['Phys/[StdLoosePions](./stripping21r1p1-commonparticles-stdloosepions)/Particles', 'Phys/[StdLooseKsLL](./stripping21r1p1-commonparticles-stdlooseksll)/Particles'] |
| DaughtersCuts    | {'pi+': '(PT\>400\*MeV)', 'KS0': '(PT\>1\*GeV)'}                                                                                                                       |
| CombinationCut   | (ADAMASS('D0')\<80\*MeV) & (APT\>1800\*MeV)                                                                                                                            |
| MotherCut        | (VFASPF(VCHI2/VDOF)\<10) & (MIPCHI2DV(PRIMARY)\>1)                                                                                                                     |
| DecayDescriptor  | [D0 -\> KS0 pi+ pi-]cc                                                                                                                                               |
| DecayDescriptors | []                                                                                                                                                                   |
| Output           | None                                                                                                                                                                   |