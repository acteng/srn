
<!-- README.md is generated from README.Rmd. Please edit that file -->
<!-- # srn -->
<!-- badges: start -->
<!-- badges: end -->

There is value in identifying parts of the Strategic Road Network (SRN)
that overlap with potential active travel links with high walking,
wheeling and cycling potential.

On 25th November National Highways published new ‘RedLine’ data with the
boundary of its sites in England. The dataset is available at
[opendata.nationalhighways.co.uk](https://opendata.nationalhighways.co.uk/datasets/highwaysengland::redline/explore?location=53.785976%2C-1.542063%2C17.19)
and looks like this (example from Leeds):

![](https://user-images.githubusercontent.com/1825120/205610534-c9abaf87-3480-405a-af3a-3a27dc8830fa.png)

We can get estimates of active travel potential from the open PCT data
and overlay that with the RedLine data. Applying a 500 m buffer around
the simulated cycle network with high potential — with at least 100
trips per day in the PCT under the Government Target scenario — leads to
the following areas being flagged, in West Yorkshire for example, with
Cycling potential representing the Ebike scenario:

![](https://user-images.githubusercontent.com/1825120/205618329-7bdab2df-fe65-4ee5-8c8e-a0428e194675.png)
See interactive version of the map here:
<https://rpubs.com/RobinLovelace/979291>

This approach can be scaled nationally. We could modify the method or
show different scenarios but, as a proof of concept, it demonstrates the
potential to link up with NH on the data side of things.
