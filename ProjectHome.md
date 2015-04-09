![http://www.geovista.psu.edu/stempo/images/codeheader.png](http://www.geovista.psu.edu/stempo/images/codeheader.png)

The goal of the STempo project is to develop and implement computational tools for revealing complex associations in reported events. The prototype being developed represents a tightly integrated temporal and spatio-temporal pattern discovery environment that synergistically combines the power and impartiality of statistical methods to uncover hidden and potentially unsuspected patterns in complex data with the capabilities of the human analyst to see pattern visually and, in turn, apply prior knowledge to guide analysis.

The design of this integrated visualization - computational environment will facilitate the discovery of 'normal' patterns via consistency over space and/or time as well as the identification of anomalies, since the latter will be visible as inconsistencies. The environment will also be able to trace linkages and associations through potentially long chains of places, people, organizations and events, making the process suitable for uncovering the character of financial transfers or information flows, or the spread of disease.

### The STempo prototype is specifically intended to deal with: ###

  * large collections of heterogeneous data, where the patterns may potentially be composed of long chains of associations at varying temporal and spatial scales
  * events that can have both duration and spatial extent
  * inexact and missing data

The visualization capabilities are being implemented by significantly extending the [Visual Inquiry Toolkit](http://www.geovista.psu.edu/VIT/) (VIT) and integrating elements of the [GeoViz Toolkit](http://www.geovista.psu.edu/geoviztoolkit/) (GVT). Both of these are open-source Java libraries developed within the [Penn State GeoVISTA Laboratory](http://www.geovista.psu.edu/). Both toolkits support flexible coordination among multiple visualization components and views to enable relationships among objects and events (or sets of objects and events) to be recognized and contextualized within and across temporal and spatial scales. They also provide tight interaction between the visualization and statistical components so that the statistical model is driven (and modified) via the visualization components, obviating the need for a query language or textual dialogue to run the statistical components.

### Overall Research Goals: ###
  * new procedures that represent the generalization of the small set of truly inductive and scalable computational pattern discovery techniques
  * the integration of advanced visualization with innovative computational capabilities for inductively finding temporal and spatio-temporal patterns in data from diverse sources,
  * design principles for how to integrate and relate diverse visualizations for representing events in the temporal, spatial and object dimensions in a way that is useful and intuitive for the human analyst
  * a running STempo software prototype that demonstrates the viability and robustness of the conceptual advancements above


---

_This study is supported by a grant from the NGA University Research Initiative (NURI) program. The views and conclusions contained in this document are those of the author(s) and should not be interpreted as necessarily representing the official policies or endorsements, either expressed or implied, of the National Geospatial- Intelligence Agency (NGA) or the U.S. Government._