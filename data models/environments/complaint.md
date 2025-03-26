## Object: complaint

Represents a complaint related to pollution or environmental issues. Users can report concerns, issues, or incidents of pollution, including details and supporting media.

| Naming            | Description                                                        | Type                | Unique | Required |
|-------------------|--------------------------------------------------------------------|---------------------|--------|----------|
| object_type       | The type of the object, which is 'complaint' in this case.          | String 'complaint'   | no     | yes      |
| **Attributes (data)** |                                                             |                     |        |          |
| project_uuid        | UUID of the associated project                                        | UUID             | no     | yes      |
| user_uuid           | UUID of the user filing the complaint                                 | UUID             | no     | yes      |
| location          | Geographical location where the complaint was reported              | string              | no     | no      |
| complaint_date    | Date and time the complaint was filed                               | datetime            | no     | no      |
| description       | Detailed description of the complaint                               | string              | no     | yes      |
| status            | Current status of the complaint (e.g., open, resolved, etc.)        | string              | no     | yes      |
| priority          | Priority level of the complaint (e.g., high, medium, low)           | string              | no     | yes       |
| photos            | Media files associated with the complaint                           | string (URL)        | no     | yes       |
