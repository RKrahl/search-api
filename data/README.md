# Example Data from HZB

The `db.json` file provides some example data from HZB to be used in
the PaNOSC federated search demonstrator.  It has been derived from
real HZB data that is publicly available:

* Data from the proposal [14100881-ST-1.1-N](https://data.helmholtz-berlin.de/permalink/14100881-ST-1.1-N)
  that have been collected in November 2015 at the
  [E2 beamline](https://doi.org/10.5442/NI000001) (just 10 out of 191
  datasets from the real proposal).

* A data publication [Neutron study of the topological flux model of
  hydrogen ions in water ice](https://doi.org/10.5442/ND000001).

Some notes:

* I tried my best to squeeze the data into the model used in the
  PaNOSC search API.  Some aspects of this data model are not very
  clear, so there may be errors in the structure.  I am not able to
  test the conformity of the data.

* The names of the dataset parameter from the proposal in the example
  data are legacy.  It is how the parameters were named back then in
  the data catalogue.  The naming conventions for the parameter at HZB
  has been changed since.

* I used UUIDs as placeholders were the PaNOSC data model requests a
  PID, but no formal PID is available in the real data.  These UUIDs
  are not present in the HZB data catalogue.
