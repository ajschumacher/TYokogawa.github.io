---
layout: post
title: Connection between primary and secondary diagnosis
---

101,766 patients diagnosis data was visualized by using d3.javascript.

Some primary diagnosis have more number of patients have particular secondary diagnosis (e.g. hyperosmorarity), on the other hand some have very wide spread sencondary diagnosis (e.g. cerebral thrombosis). Each strings represent number of patients, so thicker bundle means more patients had that particular combination of primary and secondary diagnosis. Move your pointer over single primary diagnosis on the circle, it will highlight connection to the secondary diagnosis. More purple color means more number of patients.

###Interactive d3.js plot of primary and seccondary diagnosis connection

[<img src="{{ '/assets/img/Diagnosis_connection2.png' | prepend: site.baseurl }}">](http://52.4.135.74)

[link to interactive plot](http://52.4.135.74)

###Interactive d3.js plot of primary diagnosis counts
<iframe src="{{'/assets/html_plots/diag_count.html' | prepend: site.baseurl }}" width="800" height="600" frameborder="0"></iframe>


[d3 reference](http://bl.ocks.org/mbostock/4062006)
