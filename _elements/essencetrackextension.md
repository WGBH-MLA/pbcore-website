---
name: essenceTrackExtension
subelements:
  - name: extensionWrap
    note: required ONLY if extensionEmbedded is not used
  - name: extensionEmbedded
    note: required ONLY if extensionWrap is not used
---
~~~~
<essenceTrackExtension>
<!-- No data here directly; it's within sub-elements instead -->
     <extensionWrap>
          <extensionElement>RightsHolderName</extensionElement>
          <extensionValue>WNET.org</extensionValue>
          <extensionAuthorityUsed>http://www.loc.gov/standards/rights/METSRights.xsd</extensionAuthorityUsed>
     </extensionWrap>
</essenceTrackExtension>
~~~~