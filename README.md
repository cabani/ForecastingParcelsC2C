# Analysis and forecasting of the load of parcel pick-up points related to C2C e-commerce

Second-hand shopping, primarily via online marketplaces, has rapidly increased during the last decade. Nowadays, consumers widely choose the Pick-Up Point (PUP) service to facilitate the
delivery of products. Parcels related to this Customer-to-Customer (C2C) activity are dropped off in PUPs chosen by the sellers, shipped to PUPs selected by the buyers where they wait to be
picked up. The increased impact of C2C parcels on PUPs requires an improved control of their load to reduce the risks of PUP overload, parcel rerouting, and resulting customer dissatisfaction.
This paper presents a forecasting approach for the load of PUPs receiving C2C parcels. The daily number of parcels dropped off with a given PUP as target is described by a Markov-Switching
Auto-Regressive (MSAR) model to account for the non-stationarity of the second-hand shopping activity. A PUP Management Company, using this forecasting approach, is able to propose customers only target PUPs that are likely not to be overloaded at time of delivery. The proposed approach is compared to load prediction techniques involving SARIMA, Holt-Winters, LSTM,
Prophet, and TiDE models. For the considered PUP, the load is predicted from one up to seven days ahead with mean absolute errors ranging from 5.5 parcels (1 day ahead) to 8.8 parcels (7 days
ahead) for a PUP with an average load of 25 parcels. Similar results are shown for other PUPs.

For more details about this work:
>  Thi Thu Tam Nguyen, Adnane Cabani, Iyadh Cabani, Koen De Turck, and Michel Kieffer, "Analysis and forecasting of the load of parcel pick-up points related to C2C e-commerce", Computers & Industrial Engineering, 2024.

# Dataset
The dataset presented in this github ([data.csv](https://github.com/cabani/ForecastingParcelsC2C/blob/main/data_C2C.csv)). Each line of the csv file contains for each parcel:
- Id_parcel: The ID of the parcel
- PUP_longitude: Longitude of the PUP's position
- PUP_latitude: Latitude of the PUP's position
- Date_S1: Drop-off time 
- Date_S2: Collection time
- Date_S3: Delivery time
- Date_S4: Pickup time
