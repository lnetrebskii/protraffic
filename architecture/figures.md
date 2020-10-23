# Figures used to make decisions
This figures are based on the real numbers I got from my experience working in the area in 2013-2017.

## SLA
Only 10% of crossroads have the same number per camera.
| Name | Value |
| --- | --- |
| Max vehicles per camera per day | 20000 |
| Max number of track positions per camera per day | 2000000 |
| Max payload per vehicle (w/o images) | 1 Kb |
| Max vehicle image size | 20 Kb |
| Max number of violations detected per camera per day | 500 |
| Max evidense base size per detected violation | 3 Mb |
| Max data to upload per day | 1.9 Gb |
| Max data retention time | 3 Months |

## Assumptions
| Name | Value |
| --- | --- |
| Number of consequent hours that turn into 80% of detections | 10 |
| Min average upload speed within the most active hours | 1 Mbps |

## Calculations
| Name | Value |
| --- | --- |
| Required max throughput | 0.35 Mbps |
