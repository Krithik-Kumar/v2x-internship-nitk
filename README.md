# V2X-Internship-NITK

A study of Vehicle-to-Everything (V2X) communication and cooperative perception, carried out during a two-month research internship (May–July 2026) at the Department of Electronics and Communication Engineering, **National Institute of Technology Karnataka (NITK), Surathkal**, under the guidance of **Dr. Prabu K, Associate Professor**.

## What's here

- `report/` - the full internship report (PDF)
- `review-paper/` - *From Spoofing to Denial-of-Service: A Curriculum-Integrated Taxonomy of V2X Cybersecurity Threats and Countermeasures* - a review paper written during the internship, surveying the V2X threat landscape and its countermeasures
- `simulator.html` - an interactive, browser-based simulator comparing the medium-access behaviour of DSRC (IEEE 802.11p CSMA/CA) and C-V2X Mode 4 (sensing-based SPS) under varying vehicle density

## Topics covered

- V2X communication modes (V2V, V2I, V2P, V2N) and the two radio families: DSRC / IEEE 802.11p and Cellular V2X
- Communication impairments - latency, packet loss, clock drift, and bandwidth limits - and how they propagate into the perception pipeline
- Cooperative perception: early, intermediate, and late fusion, and the machine-learning methods used for temporal prediction and feature alignment
- Simulation frameworks (Veins, SUMO, CARLA, ns-3, OpenCOOD) and public datasets (OPV2V, DAIR-V2X, V2X-Seq)
- The V2X cybersecurity threat landscape and its countermeasures

## Running the simulator

No installation needed - just open `simulator.html` in any modern browser.

Or try it live: 

## Scope and disclaimer

This is an educational study: no novel algorithm is proposed and no result here should be read as a research contribution. The simulator is a learning aid built to understand channel-access mechanisms, not a validated network simulator.

## Acknowledgements

Sincere thanks to Dr. Prabu K for his guidance and patience throughout the internship, and to the Department of Electronics and Communication Engineering, NITK Surathkal, for the opportunity.
