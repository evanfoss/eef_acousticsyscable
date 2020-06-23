EPL Acoustic System Cable
===================================

It might seem silly to have a whole repo just for the assembly of a cable but the cable is share among various versions of the device and it's assembly has been through several evolution's.

In the beginning the cable was just a BNC cable cut in half with a connector at the spliced ends. This was cheap and easy to assemble but users wanted the cable to be more flexible and the cable stiffness combined with torque from the users positioning correlated with a higher failure rate of the connector. Seeing that it was not practical to change all the acoustic system connectors it was decided to change the wire used to distribute bending forces better. It sounds so simple but it did not work out so easily. 

Assembly Process
===================================

In abstract this is simple.
1. Cut and strip the wires in the cable.
2. Cut the BNC cable in half and strip the freshly cut ends.
3. Solder one end of the cable to the pcb, solder the BNC cable ends to the pcb.
4. Cover the pcb with heatshrink and seal it.
5. Terminate the 4 conductor cable to the molex connector.
6. Test it with a multimeter.
7. Finish the assembly.

The problem is the cable. To get more flexibility at a commodity price we ended up with a wire that isn't friendly to use. Please pay careful attention to the notes in the BOM (Bill Of Matterials) about wire strippers as stripping the individual wires at this gauge is tricky. To remove the jacket on the BNC and multiconductor cable we recommend using a scalpel with a #11 blade. The idea is to bend the cable and lightly score the insulation right at the bend. Bending the cable in the reverse direction and repeating the scoring process on the other side. Finally pull the insulation off. 

Now that you know the technique to use for stripping the insulation it's important to describe how we terminate the molex connector. See the Molex company only makes crimp connectors small enough to crimp 30AWG but the multiconductor cable is 32 AWG. To resolve this we strip the wire insulation 4 times longer than the crimp requires. We then fold the bare wire over 3 times and then twisting the folded over wire a few times. This is best done with tweezers. Finally the terminals can be crimped and the crimped terminals can be inserted into the connector housing. Optionally I like to solder them too but I do not recommend this for the faint of heart as you have to get the crimp over the wire heated with out melting the insulation in the strain relief part of the crimp. You also can't get solder on the mating and bending surfaces.

Finally with the connector assembled test the whole thing using a continuity meter. Assuming it matches the diagram and has no shorts it gets finished. The finishing process is simple. RTV is applied to the pcb with heat shrink over it using the nozzle on the finest point possible. The heatshrink is then shrunk. RTV is also applied to the back of the molex housing. The hard part is getting just enough inside to seal the cable but not so much that it inhibits the connectors operation. I try to just get 1/16" into the housing. I also apply the RTV with a male connector mated to it. After this to prevent the RTV from getting on stuff I drap the cables over a rod to support them while the RTV cures.

Known Problems
===================================

While the current version is of the cable is better than what we used to do there is still a failure rate on the connectors that we find higher than we might like. As we have many of these connectors in use around the lab inside devices we believe there is something to do with how users are handling it. We are continuing to search for a better solution.

We are also looking at better ways to improve the assembly process. We are most aggressively looking at ways to mold the strain relief on the back of the molex connector. This has included various experiments with simple machined molds made in delrin and others 3D printed in acrylic via an SLA process. We are also looking for altnernative connectors entierly.

