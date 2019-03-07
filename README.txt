1.AppData
UserAppRecords.txt: There are the App usage records of 30 users. The columns represent user ID, timestamp, base station ID, App ID, respectively.
AppId.txt: The name and the corresponding App ID of 100 Apps.
AppCategory.txt: Eavh line represents a App category and the Apps that it contains.

2.PoiData
PoiData.txt: There shows the base sation ID and the POI quantity distribution of 100 base stations.

3.BlockData
BlockData.txt: There are the data of 188 blocks of Shanghai. The columns represent block ID, the population of blocks, the GDP of blocks, the label for 3 SELs, the label for 4 SELs.
BlockBoundry.mat: The base ID of the 188 base stations and their corresponding boundary information.
GpsToBase.txt: The base station samples and their corresponding longitudes and latitudes.

4.AggregatedData
AggregatedData.txt: The features extracted from App usage records and POIs data. It is used to train regression model and classification models.