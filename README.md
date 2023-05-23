# PyPPrate

Passive, PPD-based capacity estimation tool implemented in Python based on PPrate introduced by Taoufik En-Najjary and Guillaume Urvoy-Keller [1] as used for our paper "On the Accuracy of Active Capacity Estimation in the Internet" [2].

Python implementation by Patryk Brzoza, Janluka Janelidze, Simon Bauer, and Benedikt Jaeger. 

## Usage

Current implementation expects a pcap file only consisting of one flow.
Decide to skip the second phase of the PPrate alogorithm based on ADR estimation by using *--adrskip*.

Example: *python3 PPrate.py $PCAP.pcap  --adrskip*

## Measurement results

Capacity estimates conducted on hybrid Internet path setups providing ground truth data as described in [2]: [Download](https://oc.net.in.tum.de/index.php/s/NM5Rb7pcpcxaYRG)

## References

[1] Taoufik En-Najjary and Guillaume Urvoy-Keller. "Pprate: A passive capacity estimation tool." 2006, 4th IEEE/IFIP Workshop on End-to-End Monitoring Techniques and Services.

[2] Simon Bauer, Janluka Janelidze, Benedikt Jaeger, Patrick Sattler, Patryk Brzoza, and Georg Carle. "On the Accuracy of Active Capacity Estimation in the Internet" 2023, IEEE/IFIP Network Operations and Management Symposium (NOMS 2023).

