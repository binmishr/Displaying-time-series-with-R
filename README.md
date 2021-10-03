# Displaying-time-series-with-R

The details of the codeset and plots are included in the attached Microsoft Word Document (.docx) file in this repository. 
You need to view the file in "Read Mode" to see the contents properly after downloading the same.

A Brief Introduction
=====================

A time series is a sequence of observations registered at consecutive
time instants. The visualization of time series is intended to reveal
changes of one or more quantitative variables through time, and to
display the relationships between the variables and their evolution
through time. The standard time series graph displays the time along
the horizontal axis. On the other hand, time can be conceived as a
grouping or conditioning variable. This solution allows several
variables to be displayed together with a scatterplot, using different
panels for subsets of the data (time as a conditioning variable) or
using different attributes for groups of the data (time as a grouping
variable). Finally, time can be used as a complementary variable that
adds information to a graph where several variables are confronted.

Next sections provide a variety of examples to illustrate a set of
useful techniques working with three datasets available at the data
folder of the repository.

This document has been prepared with content extracted and adapted
from the second edition of the book “Displaying time series, spatial
and space-time data with R” published with Chapman&Hall/CRC.

The most relevant packages are: lattice, latticeExtra, and
ggplot2 for static graphics; zoo and xts for reading and
arranging data as time series; RColorBrewer for defining color
palettes; and packages dygraphs, highcharter, and plotly, based
on the htmlwidgets framework, to generate animations or interactive
graphics.
