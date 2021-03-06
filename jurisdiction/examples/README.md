# Jurisdiction Examples

This file presents an example of how to format a flat file, should an agency prefer to serve flat files instead of implementing a REST API.

**`jurisdictions.json`** file: [`jurisdictions.json`](jurisdictions.json)

```js
{
    "version": "1.2.0",
    "updated": "1570035222868",
    "end_date": "1570035222868",
    "jurisdictions": 
    [
      {
        "jurisdiction_id": "240edf69-9f2b-457c-accf-e8156e78811f",
        "agency_key": "Amsterdam  ",
        "agency_name": "County of Amsterdam",
        "mobility_modes": ["taxi"],
        "geography_id": "e95cb0f7-41eb-4bdd-8b1d-92b0593a7df1"
      },
      {
        "jurisdiction_id": "3c71f367-7c7d-49c7-94d0-21b9e7259c1b",
        "agency_key": "Amsterdam",
        "agency_name": "City of Amsterdam",
        "mobility_modes": ["micromobility"],
        "geography_id": "a3ddc3f6-b476-4784-bae7-f0141bb534f6"
      },
      {
        "jurisdiction_id": "9fc51c56-9ac3-497a-b575-07097aa147cb",
        "agency_key": "coral-gables",
        "agency_name": "City of Coral Gables",
        "mobility_modes": [],
        "geography_id": "ad4b47d3-bb49-4122-ad19-5d517490baa6"
      }
    ]
}
```
