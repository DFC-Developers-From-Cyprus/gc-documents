## Object: user

A user represents an individual or an organization using the platform. They can be regular users, volunteers, or environmental organizations contributing to the project.

| Naming            | Description                                                        | Type                | Unique | Required |
|-------------------|--------------------------------------------------------------------|---------------------|--------|----------|
| object_type       | The type of the object, which is 'user' in this case.              | String 'user'       | no     | yes      |
| **Attributes (data)** |                                                             |                     |        |          |
| name              | User's full name                                                   | string              | no     | yes      |
| email             | User's email address                                               | string (email)      | yes    | yes      |
| password          | Encrypted password for user authentication                        | string (encrypted)  | no     | yes      |
| role              | Role of the user (e.g., regular, volunteer, organization)          | string              | no     | yes      |
| location          | Geographical location of the user                                  | string              | no     | no       |
| profile_picture   | URL link to the user's profile picture                             | string (URL)        | no     | no       |
| created_at        | Date and time when the user account was created                    | datetime            | no     | no      |
| updated_at        | Date and time when the user data was last updated                  | datetime            | no     | no      |
