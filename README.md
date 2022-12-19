# PyPPrate

Passive, PPD-based capacity estimation tool implemented in Python based on the PPrate algortithm introduced by Taoufik En-Najjary and Taoufik En-Najjary [1] as used for our paper "On the Accuracy of Active Capacity Estimation in the Internet" [2]. <br />
Implementation by Patryk Brzoza, Janluka Janelidze, Simon Bauer, and Benedikt Jaeger. 

[1] Taoufik En-Najjary and Guillaume Urvoy-Keller. "Pprate: A passive capacity estimation tool." 2006 4th IEEE/IFIP Workshop on End-to-End Monitoring Techniques and Services. IEEE, 2006. <br />
[2] tba.

## Usage

Current implementation expects a pcap file only consisting of one flow. <br />
Decide to skip the second phase of the PPrate alogorithm based on ADR estimation by using *--adrskip*.

Example: `python3 PPrate.py $PCAP.pcap  --adrskip`
