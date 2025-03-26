## Object: cleanup_action

Represents actions taken during environmental cleanup events. Users can report completed actions with descriptions and photos.

| Naming            | Description                                                        | Type                | Unique | Required |
|-------------------|--------------------------------------------------------------------|---------------------|--------|----------|
| object_type       | The type of the object, which is 'cleanup_action' in this case.    | String 'cleanup_action' | no   | yes      |
| **Attributes (data)** |                                                                |                     |        |          |
| project_uuid        | UUID of the associated project                                   | UUID                | no     | yes      |
| user_UUID           | UUID of the user who performed the cleanup action                | UUID                | no     | yes      |
| action_date       | Date and time the action was performed                             | datetime            | no     | no       |
| description       | Description of the cleanup action                                  | string              | no     | yes      |
| photos            | Media files associated with the cleanup action                     | string (URL)        | no     | yes       |
