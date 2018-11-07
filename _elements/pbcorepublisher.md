---
name: pbcorePublisher
definition: <strong>pbcorePublisher</strong> is a container for sub-elements publisher and publisherRole.
usage: optional, repeatable
subelements:
  - name: publisher
    note: required
  - name: publisherRole
    note: optional
---
~~~~
<pbcorePublisher>
<!-- No data here directly; it's within sub-elements instead -->
        <publisher>WGBH Educational Foundation</publisher>
        <publisherRole>Copyright Holder</publisherRole>
</pbcorePublisher>

<pbcorePublisher>
        <publisher>Public Broadcasting Service</publisher>
        <publisherRole>Distributor</publisherRole>
</pbcorePublisher>
~~~~