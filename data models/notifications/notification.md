## Object: notification

Represents notifications sent to users to alert them of new activities, pollution updates, or other events.

| Naming            | Description                                                        | Type                | Unique | Required |
|-------------------|--------------------------------------------------------------------|---------------------|--------|----------|
| object_type       | The type of the object, which is 'notification' in this case.      | String 'notification' | no    | yes      |
| **Attributes (data)** |                                                             |                     |        |          |
| user_uuid           | UUID of the user receiving the notification                          | UUID             | no     | yes      |
| message           | Content of the notification                                        | string              | no     | yes      |
| type              | Type of notification (e.g., new polluted area, update, event)      | string              | no     | yes      |
| created_at        | Date and time the notification was created                         | datetime            | no     | no      |
