## Object: project

A project represents an environmental initiative on the platform, such as a cleanup effort or awareness campaign. It can be created by individuals or organizations.

| Naming            | Description                                                        | Type                | Unique | Required |
|-------------------|--------------------------------------------------------------------|---------------------|--------|----------|
| object_type       | The type of the object, which is 'project' in this case.           | String 'project'    | no     | yes      |
| **Attributes (data)** |                                                             |                     |        |          |
| title             | Title of the project                                               | string              | yes     | yes      |
| description       | Detailed description of the project                                | string              | no     | yes      |
| created_by        | User UUID of the creator (volunteer or organization)                 | UUID             | no     | yes      |
| status            | Current status of the project (active, completed, etc.)            | string              | no     | yes      |
| location          | Geographical location of the project                               | string              | no     | no       |
| start_date        | Date when the project starts                                        | datetime            | no     | no      |
| end_date          | Date when the project ends                                          | datetime            | no     | no       |
| created_at        | Date and time when the project was created                          | datetime            | no     | no      |
| updated_at        | Date and time when the project data was last updated               | datetime            | no     | no      |
