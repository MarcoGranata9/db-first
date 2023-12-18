### Used Car Database Model

| Column | Data-Type | Attributes |
| ----------- | ----------- | ----------- |
| id | BIGINT |  PRIMARY_KEY |
| brand | VARCHAR |  NOTNULL |
| model | VARCHAR |  NOTNULL |
| description | VARCHAR |  NULL |
| color | VARCHAR |  NULL |
| interiors_color | VARCHAR |  NULL |
| has_radio | TINYINT |  NULL / DEFAULT("1") |
| image | VARCHAR |  NULL |
| seats | TINYINT |  NULL |
| fuel_type | VARCHAR |  NOTNULL |
| emission_class_EURO | VARCHAR |  NULL |
| weight_in_kg | SMALLINT |  NULL |
| height_in_mm | SMALLINT |  NULL |
| length_in_mm | SMALLINT |  NULL |
| width_in_mm | SMALLINT |  NULL |
| transmission | VARCHAR |  NOTNULL / DEFAULT("Manual") |
| power_in_kW | SMALLINT |  NOTNULL |
| drivetrain-architecture | VARCHAR |  NULL |
| assisting-systems	 | VARCHAR |  NULL |
| price | DECIMAL(11,2) |  NOTNULL |
| mileage_in_km | MEDIUMINT |  NOTNULL |
| year_of_production | YEAR |  NOTNULL |

