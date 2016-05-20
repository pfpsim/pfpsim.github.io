The PFPSim methodology is driven by emerging software-defined networking trends,
such as the need to program forwarding devices with new protocols, the emergence of
new programming paradigms such as [P4](http://p4.org) and [POF](http://www.poforwarding.org),
and of programmable forwarding plane hardware such as NPUs and reconfigurable pipelines.
PFPSim aims to enable early co-design of forwarding plane platforms and applications, through an intuitive
toolchain that makes it easy to create, modify and debug simulation models.



<img src ="https://cloud.githubusercontent.com/assets/943241/15301816/b68a5886-1b7d-11e6-8062-84567ca96456.PNG" class = "responsiveimg" style="text-align:center;">


The dataplane application and target architecture model are independent of each other, but can be optimized
based on their interaction. An example application might consist of parsing followed by the execution of a
control-flow graph of match-action tables, and could be written in C++ or a DSL such as P4. The target architecture
model is composed of a structural and behavioural specification. These components are combined using our model-generation
platform to create a fast, host-compiled simulation model, which allows pre-silicon debugging, and
co-optimization of applications and hardware architectures.
