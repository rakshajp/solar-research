## Steps

Enable Google Maps Static API in GCP, create new API key and update in script as API_KEY.

Generate coordinates for CSV from geojson.io JSON

Image tiles are downloaded to Goole Drive/locally at line:
> files.download(filename)

Along with files, a metadata csv that contains lat, long coords of each image tile is generated.

This dataset can be split into labelled and unlabelled.

Labelled images can be used to traina nd test ML model.

Once a good enough model is trianed, run the unlabelled images throug it to generate DB with results with similar accuracy.

## geojson website example 
https://geojson.io/#new&map=14.61/41.82954/-88.03202

![image](https://github.com/rakshajp/solar-research/assets/134439658/ca895ca3-3eed-439c-b471-479e58205856)

