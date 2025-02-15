---
title: Version
description: Version
ms.date: 04/20/2017
---

# Version

[!include[MBAE deprecation warning](../includes/mbae-deprecation-warning.md)]

The Version element specifies the version of the application software that created the service metadata package.

## Usage


``` syntax
<Version>
  text
</Version>
```

## Attributes


There are no attributes.

## Child elements


There are no child elements.

## Parent elements


<table>
<colgroup>
<col width="50%" />
<col width="50%" />
</colgroup>
<thead>
<tr class="header">
<th>Element</th>
<th>Description</th>
</tr>
</thead>
<tbody>
<tr class="odd">
<td><p><a href="metadatabuilderinformation.md" data-raw-source="[MetadataBuilderInformation](metadatabuilderinformation.md)">MetadataBuilderInformation</a></p></td>
<td><p>The <a href="metadatabuilderinformation.md" data-raw-source="[MetadataBuilderInformation](metadatabuilderinformation.md)">MetadataBuilderInformation</a> element specifies the application that created the service metadata package.</p></td>
</tr>
</tbody>
</table>

 

## XSD


``` syntax
<xs:element name="Version" type="tns:VersionType" />

<xs:simpleType name="VersionType">
  <xs:restriction base="xs:string">
    <xs:minLength value="1" />
    <xs:maxLength value="256" />
  </xs:restriction>
</xs:simpleType>
```

## Remarks


The Version element is not used by the Windows 7 operating system. It is reserved for use by the OEM and developers.

 

 





