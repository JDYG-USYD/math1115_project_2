# Notes of data

## Metadata

- Month: The number shown in this column when taken into Microsoft Excel and formatted as a Date will give the MMM/YYYY information. When using any other package, use the Year and Month_num fields to get this information. Month is the lowest level of aggregation.

- In_Out: I = Inbound (Inbound to Australia/Australian international airport) and O = Outbound (Outbound from Australia/Australian international airport)

- Australian_City: String

- International_City: String

- Route: The route of a flight is determined by the flight number and is a list of the individual cities linked by services operated under a single flight number. Each city has a three letter code and these codes are strung together to show the route.

- Port_Country: Based on the international uplift or discharge port.

- Port_Region: Based on the international uplift or discharge port.

- Service_Country: Based on the international country where same flight number services commence or cease.

- Service_Region: Based on the international country where same flight number services commence or cease.

- Stops: Number of Stops between the **Australian_City** and **International_City**.

- All_Flights

- Max_Seats

- Year: YYYY

- Month_num: M

## Mentionables

- Covers flights and fitted/sale-able seats operated by scheduled international passenger airlines operating to and from Australia.

- Code share arrangements are not covered: all seats are shown under the operating airline. 

- Charter operations are also not covered.

- Figures were obtained from data supplied by scheduled international passenger airlines.

- Some airlines report based on departure date: if comparing these figures with published airline schedules, use the flights/seats outbound from Australia.

- Airlines are responsible for providing accurate seat data to and from Australia on an Over The Coast basis. This data has to be processed in order to produce the information contained in this file. Note that the airlines are not responsible for verifying the information contained in this file. Please read the Indemnity Statement below.

- Where an airline has not supplied data prior to publication, figures shown are based on schedules or estimated based on previous reporting.

- Where fitted seats are used, the seats reported here may differ slightly from the sale-able seats reported in the International Airline Activity publication.

- Flights and seats operated on routes with more than one city pair are shared by each city pair on the route. For example, seats on a 1-2-3 service are shared between 1-2 and 1-3. 

- All Flights/Maximum available seats:

  - All flights/seats operated on a given route are shown as being available against each city/city pair on that route. In 1-2-3 example above, if 400 seats were operated, that would be shown as 400 seats from 1 to 2 and 400 seats from 1 to 3.

- The data shows flights and seats dis-aggregated to airline and route for each city pair. For example, this file shows the airlines that operate on a given city pair and the different routes involved. Use the "Stops" category set to zero ("Over the coast") in order to get totals for an airline, route, inbound, outbound or total Australia. Any other aggregation could result in double counting.

- The "Over the coast" measure allocates the available seats only to the directly connected over the coast city pair - thereby eliminating double counting. For inbound services, the seats will be allocated as from the **last international city** to the **first Australian city**. For outbound services, the seats will be allocated as from the **last Australian city** to the **first international city**. For example, seats on a London-Singapore-Sydney-Melbourne route will be allocated as from Singapore to Sydney.

- The data may include diversions. For diverted flights where seats are not sold to/from the diversion port, this data will overstate the available capacity to/from the diversion port.