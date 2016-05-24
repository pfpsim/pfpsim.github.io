<img src ="https://raw.githubusercontent.com/pfpsim/pfpsim.github.io/master/images/banner-image.png" class = "responsiveimg centerimg">
<br>
Software-Defined Networking (SDN) enables centralized network control by physical separating the control plane from the forwarding plane. The next logical step in SDN is the ability to fully program the forwarding behavior from the controller, i.e. a Programmable Forwarding Plane. The emergence of new forwarding plane programming languages such as [P4](http://p4.org) and [POF](http://www.poforwarding.org), and highly programmable forwarding hardware such as NPUs and reconfigurable pipelines, is evidence of this growing trend. 
<br>
PFPSim enables pre-silicon co-design and co-optimization of programmable forwarding plane architecture and applications as seen in the figure above. The forwarding plane designer specifies a mapping between the application (written in P4, C or C++) and the forwarding architecture (described in a simple architecture description language). A model generator (pfpgen) auto-generates a host-compiled simulation binary from the forwarding plane specification. A powerful debugger (pfpdb) enables the designer to debug their application running on a model of the target architecture. The user can also program observers to generate interesting simulation metrics such as packet latency, memory footprint, power consumption etc. to guide pre-silicon optimization of both the application and the forwarding architecture.

<br>

PFPSim offers 3 key benefits to programmable forwarding plane developers:
<p>
1. Hardware developers can leverage automatic model generation to minimize manual development of complex switch models. 
<br>
2. Hardware architects can leverage fast and scalable host-compiled simulation to explore architecture optimizations and perform pre-silicon what-if analysis.
<br>
3. Application developers can debug and optimize their application on the target model before silicon availability, thereby significantly reducing deployment time.
</p>
Best of all, the PFPSim simulation tools are free and open-source under the GPLv2 license. We invite you to download PFPSim and get started with our example models!
