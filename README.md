# tidal_gcmt
Tidal parameters for earthquakes in the Global Centroid Moment Tensor catalog

If you use these data, please cite the following references:

Dziewonski, A. M., T.-A. Chou and J. H. Woodhouse, Determination of earthquake source parameters from waveform data for studies of global and regional seismicity, J. Geophys. Res., 86, 2825-2852, 1981. doi:10.1029/JB086iB04p02825

Ekström, G., M. Nettles, and A. M. Dziewonski, The global CMT project 2004-2010: Centroid-moment tensors for 13,017 earthquakes, Phys. Earth Planet. Inter., 200-201, 1-9, 2012. doi:10.1016/j.pepi.2012.04.002

GCMT Data were downloaded from https://www.globalcmt.org/CMTfiles.html, as of March 9, 2024. 

Nodal plane 1 is defined as having lower dip than nodal plane 2.

File format: plain text, space-delimited columns

| column #   |      Field      |  Unit/format |
|----------|:-------------:|------:|
|1|longitude|degrees|
|2|latitude|degrees|
|3|depth|km|
|4|magnitude|Mw|
|5|time|ISO8601|
|6|id|string|
|7|strike (NP1)|degrees|
|8|dip (NP1)|degrees|
|9|rake (NP1)|degrees|
|10|strike (NP2)|degrees|
|11|dip (NP2)|degrees|
|12|rake (NP2)|degrees|
|13|phase of V (NP1)|degrees|
|14|phase of t (NP1)|degrees|
|15|phase of s (NP1)|degrees|
|16|phase of CFF0.1 (NP1)|degrees|
|17|phase of CFF0.4 (NP1)|degrees|
|18|phase of CFF0.7 (NP1)|degrees|
|19|amplitude of V (NP1)|MPa|
|20|amplitude of t (NP1)|MPa|
|21|amplitude of s (NP1)|MPa|
|22|amplitude of CFF0.1 (NP1)|MPa|
|23|amplitude of CFF0.4 (NP1)|MPa|
|24|amplitude of CFF0.7 (NP1)|MPa|
|25|phase of V (NP2)|MPa|
|26|phase of t (NP2)|MPa|
|27|phase of s (NP2)|MPa}
|28|phase of CFF0.1 (NP1)|degrees|
|29|phase of CFF0.4 (NP1)|degrees|
|30|phase of CFF0.7 (NP1)|degrees|
|31|amplitude of V (NP2)|MPa|
|32|amplitude of t (NP2)|MPa|
|33|amplitude of s (NP2)|MPa|
|34|amplitude of CFF0.1 (NP2)|MPa|
|35|amplitude of CFF0.4 (NP2)|MPa|
|36|amplitude of CFF0.7 (NP2)|MPa|
|37|tau_p of V (NP1)|Mpa|
|38|tau_p of t (NP1)|Mpa|
|39|tau_p of s (NP1)|Mpa|
|40|tau_p of CFF0.1 (NP1)|Mpa|
|41|tau_p of CFF0.4 (NP1)|Mpa|
|42|tau_p of CFF0.7 (NP1)|Mpa|
|43|tau_p of V (NP2)|Mpa|
|44|tau_p of t (NP2)|Mpa|
|45|tau_p of s (NP2)|Mpa|
|46|tau_p of CFF0.1 (NP2)|Mpa|
|47|tau_p of CFF0.4 (NP2)|Mpa|
|48|tau_p of CFF0.7 (NP2)|Mpa|

