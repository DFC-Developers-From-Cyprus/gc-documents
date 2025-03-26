## Object: polluted_area

Represents a polluted area in Cyprus. Each polluted area is associated with a pollution type, severity, and geolocation.

| Naming            | Description                                                        | Type                | Unique | Required |
|-------------------|--------------------------------------------------------------------|---------------------|--------|----------|
| object_type       | The type of the object, which is 'polluted_area' in this case.     | String 'polluted_area' |  no  |   yes    |
| **Attributes (data)** |                                                             |                     |        |          |
| project_id | ID of the project where the polluted area is associated with                        | integer              |  yes    |   yes    |
| type_of_pollution | Type of pollution (air, water, soil, waste)                        | string              |   no   |    yes   |
| pollution_level   | Level of pollution (low, medium, high)                             | string              |   no   |   yes    |
| description       | Detailed description of the pollution                              | string              |  no    |    yes    |
| location          | Geographical location of the polluted area                         | string              |   yes   |    yes   |
| created_at        | Date and time the polluted area was added to the system            | datetime            |   yes   |    yes   |
| updated_at        | Date and time the polluted area data was last updated             | datetime            |   yes   |    yes   |
