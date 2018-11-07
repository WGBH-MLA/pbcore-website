---
name: pbcoreCoverage
definition: <strong>pbcoreCoverage</strong> is a container for subelements coverage and coverageType.
usage: optional, repeatable
subelements:
  - name: coverage
    note: required
  - name: coverageType
    note: optional
---
~~~~
<pbcoreCoverage>
<!-- No data here directly; it's within sub-elements instead -->
        <coverage>1607-1631</coverage>
        <coverageType annotation="historical">Temporal</coverageType>
</pbcoreCoverage>
<pbcoreCoverage>
        <coverage>2007</coverage>
        <coverageType annotation="current">Temporal</coverageType>
</pbcoreCoverage>
<pbcoreCoverage>
        <coverage source="GeoNames" ref="http://www.geonames.org/maps/google_37.208_-76.774.html">Jamestown, VA</coverage>
        <coverageType>Spatial</coverageType>
</pbcoreCoverage>
<pbcoreCoverage>
        <coverage source="latitude, longitude">37.2000,-76.7667</coverage>
        <coverageType source="PBCore coverageType" ref="http://pbcore.org/vocabularies/coverageType#spatial">Spatial</coverageType>
</pbcoreCoverage>
<pbcoreCoverage>
        <coverage source="Wikipedia" ref="http://en.wikipedia.org/wiki/Werowocomoco">Werowocomoco</coverage>
        <coverageType source="PBCore coverageType" ref="http://pbcore.org/vocabularies/coverageType#spatial">Spatial</coverageType>
</pbcoreCoverage>
~~~~