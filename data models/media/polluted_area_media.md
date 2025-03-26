## Object: polluted_area_media

Stores media (photos, videos) linked to a polluted area to provide visual evidence of pollution.

| Naming            | Description                                                        | Type                | Unique | Required |
|-------------------|--------------------------------------------------------------------|---------------------|--------|----------|
| object_type       | The type of the object, which is 'polluted_area_media' in this case. | String 'polluted_area_media' | no | yes      |
| **Attributes (data)** |                                                                |                     |        |          |
| polluted_area_uuid  | UUID of the polluted area associated with the media              |    UUID             | no     | yes      |
| media_type        | Type of media (e.g., photo, video, document)                       | string              | no     | yes      |
| url               | URL link to the media file                                         | string (URL)        | no     | yes      |
