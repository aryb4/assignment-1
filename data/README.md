# Data files

`inspection.csv` and `service_times.csv` contain synthetic observations prepared for this assignment. The other five files contain real observations exported from R's datasets package, version 4.5.2. Numeric values and missing observations in those datasets have been preserved.

| File | Rows | Variables |
| --- | --- | --- |
| `inspection.csv` | 100 | `day` gives the observation order, `inspected` is the number of items checked, and `defects` is the number found defective. |
| `service_times.csv` | 420 | `order` gives the observation order and `service_minutes` is the service duration in minutes. |
| `faithful.csv` | 272 | `eruptions` is an eruption's duration and `waiting` is the wait until the next eruption, both in minutes. |
| `airquality.csv` | 153 | `Ozone`, `Solar.R`, `Wind`, `Temp`, `Month`, and `Day` retain their R dataset names. Ozone is in parts per billion, wind in miles per hour, temperature in degrees Fahrenheit, and solar radiation in Langleys. `NA` denotes a missing measurement. |
| `insect_sprays.csv` | 72 | `count` is the number of insects in an experimental unit and `spray` identifies the insecticide treatment. |
| `precipitation.csv` | 70 | `city` identifies a location and `annual_inches` is its average annual precipitation in inches over 1941 to 1970. |
| `iris.csv` | 150 | Four sepal and petal measurements in centimeters, followed by `Species`. |

The geyser observations are from Old Faithful in Yellowstone National Park. See the [R documentation for faithful](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/faithful.html).

The air quality measurements cover May through September 1973 in New York. Ozone is the mean reading from 1 p.m. to 3 p.m. at Roosevelt Island. See the [R documentation for airquality](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/airquality.html).

The insect counts come from experiments reported by Beall in 1942. See the [R documentation for InsectSprays](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/InsectSprays.html).

The precipitation observations are averages for 70 locations in the United States and Puerto Rico, taken from the Statistical Abstracts of the United States, 1975. Each row represents a location, not an individual year. See the [R documentation for precip](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/precip.html).

The iris measurements were collected by Edgar Anderson and include 50 flowers from each of three species. See the [R documentation for iris](https://stat.ethz.ch/R-manual/R-devel/library/datasets/html/iris.html).
