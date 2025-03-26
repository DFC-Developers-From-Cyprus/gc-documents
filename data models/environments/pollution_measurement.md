## Object: pollution_measurement

Stores pollution data gathered from sensors or other sources. These measurements provide the pollution level for a specific area at a certain time.

| Naming            | Description                                                        | Type                | Unique | Required |
|-------------------|--------------------------------------------------------------------|---------------------|--------|----------|
| object_type       | The type of the object, which is 'pollution_measurement' in this case. | String 'pollution_measurement' | no | yes      |
| **Attributes (data)** |                                                                |                     |        |          |
| polluted_area_uuid  | UUID of the polluted area where the measurement was taken        | UUID                | no     | yes      |
| pollution_level   | Pollution level as measured by the sensor (e.g., concentration)    | number (float)      | no     | yes      |
| pollution_type    | Type of pollutant measured (e.g., particulate matter, chemicals)   | string              | no     | yes      |
| measurement_date  | Date and time when the measurement was taken                       | datetime            | no     | yes      |
| sensor_type       | Type of sensor (e.g., government, private)                         | string              | no     | yes      |
| value             | Numerical value of the pollution level measurement                 | number (float)      | no     | yes      |
more...
