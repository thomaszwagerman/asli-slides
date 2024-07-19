# BOOST-EDS: ASLI work reveal.js presentation
A reveal.js presentation describing work undertaken under BOOST-EDS, demonstrating archival of a live data product using [NERC EDS](https://eds.ukri.org/environmental-data-service) cloud services.

We deployed a data processing pipeline on [JASMIN](https://jasmin.ac.uk/) and a [Shiny application on Datalabs](https://ditbas-asliapp.datalabs.ceh.ac.uk/), and designed a method to automatically archive data into the [UK PDC](https://www.bas.ac.uk/data/uk-pdc/).

Related repositories:
* [asli](https://github.com/davidwilby/amundsen-sea-low-index) (Hosking & Wilby 2024): Python package containing ASL calculations described in Hosking et al. (2016).
* [asli-pipeline](https://github.com/antarctica/asli-pipeline): Data processing pipeline.
* [asliapp](https://github.com/antarctica/asliapp/tree/main): Shiny application.

## Acknowledgements
This work used JASMIN, the UK’s collaborative data analysis environment (https://www.jasmin.ac.uk).

This work used [Datalabs](https://datalab.datalabs.ceh.ac.uk/), with particular thanks to [Michael Tso](https://github.com/cmtso) and [Audric Vigier](https://github.com/audricvigier) for their support with hosting Shiny applications on Datalabs.

## References
Brown, M. J., & Chevuturi, A. object_store_tutorial [Computer software]. https://github.com/NERC-CEH/object_store_tutorial

Hosking, J. S., A. Orr, T. J. Bracegirdle, and J. Turner (2016), Future circulation changes off West Antarctica: Sensitivity of the Amundsen Sea Low to projected anthropogenic forcing, Geophys. Res. Lett., 43, 367–376, doi:10.1002/2015GL067143.

Hosking, J. S., & Wilby, D. asli [Computer software]. https://github.com/scotthosking/amundsen-sea-low-index

Lawrence, B. N. , Bennett, V. L., Churchill, J., Juckes, M., Kershaw, P., Pascoe, S., Pepler, S., Pritchard, M. and Stephens, A. (2013) Storing and manipulating environmental big data with JASMIN. In: IEEE Big Data, October 6-9, 2013, San Francisco.
