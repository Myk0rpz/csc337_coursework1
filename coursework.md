---
elm:
  dependencies:
    gicentre/elm-vegalite: latest

narrative-schemas:
  - coursework
---

Author: Adam Jennings (955770)

{(aim|}
Observing what age of building there is and how frequent they show up around Europe.
{|aim)}

{(vistype|}
cumulative graphs with editable Featuretype(changing how many were built in both max date made and min date made)
{|vistype)}

<iframe src="graph3.html" ></iframe>

{(vismapping|}

x position
: maxDate/minDate

y position
: cumulativeCount

{|vismapping)}

{(dataprep|}
Data was agregated by timePeriods and altered by FeatureType
{|dataprep)}

{(limitations|}
Fairly simple design, haveing both graphs overlap each other would be better as well as creating an average date line
{|limitations)}
