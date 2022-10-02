# train-brake-curves
A repository of train brake preformance curves in CSV format from NSW, Australia.

This repositiry was created to make it easier for railway analysts to build models in NSW without having to digitise data from the the [RSU Appendix C – Brake
Performance Curves](https://www.transport.nsw.gov.au/system/files?file=media/asa_standards/2022/ts-04068-1.0.pdf) from Transport for NSW.

## Data Dictionary
| Column Name 	| Description 	|  
|---	|---	|
| speed_kph 	| Speed in kilometers per hour 	|
| grade_1_in_x 	| Grade in terms of 1 in x. e.g. 33 would indicate a grade of 1 in 33 or 1 m of elevation gain for 33 m of horizontal travel. Negative indicates a falling grade. 	| 
| stopping_distance_m 	| Stopping distance in meters 	|
