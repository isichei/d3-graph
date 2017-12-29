# d3-graph
Messing around with force directed graph in d3 (v4).

Working example: https://isichei.github.io/d3-graph/index.html

Currently this example can do the following:
- Highlight first order links to node on hover (can also hide all non-highlighted nodes)
- Stop/start force layout (i.e. freezing and unfreezing nodes)
- Snap individual nodes into a fixed postion by dragging them (double click to release them)
- Zoom in and out of the svg (wheel zoom only - click zoom disabled)

Based off the code from these examples:
- http://www.coppelia.io/2014/07/an-a-to-z-of-extra-features-for-the-d3-force-layout/
- https://bl.ocks.org/puzzler10/4438752bb93f45dc5ad5214efaa12e4a
- https://bl.ocks.org/mbostock/4062045

To do:
- Add ability to highlight shortest path between two nodes
- Create hierarchical clusters based on node properties using link.distance
- Integrate with autotickbox to filter nodes
- Maybe click on zoom
