# Parcel delivery analyses

This code analyse data about deliveries of the most common Czech parcel tracking providers. 

📝 Analyse

1. Market share across providers
2. Basic aggregation functions per provider about deliveries and parcel
3. Identification of the last state from the tracking per provider
4. Finding anomalies
5. Identification of duplicates of the tracking states per provider
6. Identification of the most common provider
7. Identification of the % success of on time delivered parcels
8. Identification of cancelled deliveries
9. Finding the missing states or bad states orders in the delivery flow

📝 Data source

| Name        | Source           |
| ------------- |:-------------:| -----:|
| `internal eshop database` | Data about orders and customers |
| `providers` | Data from REST API or from FTP about deliveries from every provider |

