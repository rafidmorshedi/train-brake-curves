# train-brake-curves
A repository of train stopping distance (aka brake curves) tables in a machine readable format from NSW, Australia.

This repositiry was created to make it easier for railway analysts in Australia to build models without having to digitise data from various brake tables.the [TS 04068:1.0 RSU Appendix C – Brake Performance Curves](https://www.transport.nsw.gov.au/system/files?file=media/asa_standards/2022/ts-04068-1.0.pdf) from Transport for NSW.

## Notes
These tables should be read in conjunction with the notes in the relevant standard they were digitised from.

## Data Dictionary
| Column Name 	| Description 	|  
|---	|---	|---	|
|brake_curve	| Name of the brake curve	|
| speed_kph 	| Speed in kilometers per hour 	|
| grade_1_in_x 	| Grade in terms of 1 in x. e.g. 33 would indicate a grade of 1 in 33 or 1 m of elevation gain for 33 m of horizontal travel. Negative indicates a falling grade. 0 indicates level track| 
| stopping_distance_m 	| Stopping distance in meters 	|

## Progress notes

This is the list of standards containing brake tables and their digitisation status.

- [ARTC Train Braking Application Design ESD-05-03](https://extranet.artc.com.au/docs/eng/signal/procedures/design/ESD-05-03.pdf): Digitised in file `ESD-05-03_brake_tables.xlsx`
- [TfNSW RSU Appendix C – Brake Performance Curves TS 04068:1.0](https://www.transport.nsw.gov.au/system/files?file=media/asa_standards/2022/ts-04068-1.0.pdf): hasn't been digitised yet
