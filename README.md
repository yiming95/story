# story
A frontend web app for the data visualisation for a cloud based data analyse project. 

### Introduction

The breif introduction of the project.

```
This web app is the data visualisation for the cloud based data analyse project. The project uses NETCHAR cloud to analyse twitter 
dataset. The team uses Twitter streaming API to harvest the twitter with geo loaction, then save the data in the couchDB and then applies
sentimantal analyse to find tweets that are related to the sepecfic emotion such as lust, wrath. Next, map reduce is applied to
the dataset. The frontend web app shows the results and visualise it by using map and charts.

The frontend part uses bootstrap to make nav bar, footer and caursol. Also, uses HTML5 video tag which means applies a mp4 in the
background. However, as Safari is not allowed mp4 auto played in the background, it is recommaned to use it in Chrome or Opera.

The map part uses 'leaflet' library which is a open source map library. It can have different layers. Each layer can either be 
a base map, a marker layer(twitter marker) or a polygon. To apply a polygon on the map, a geo JSON file is needed. Also, to load
a geo Json file, AJAX is needed. A problem occured whihc is CROS, and it is solved by the server side by couchDB side.

The chart part uses 'chart js' libarary, it has bar chart and pie chart,etc. 

It uses RESTful API, to 'GET' data from the couchDB.

```

## To run it

* Please use Chrome or Opera to run the web app.
      
      
## Screenshots

<img width="1680" alt="Screen Shot 2019-04-22 at 3 13 26 pm" src="https://user-images.githubusercontent.com/40975373/56484171-90d15c80-6511-11e9-8e02-4086c03f0f05.png">

<img width="1680" alt="Screen Shot 2019-04-22 at 3 13 48 pm" src="https://user-images.githubusercontent.com/40975373/56484175-92028980-6511-11e9-9d87-bd392c7a5553.png">

<img width="1680" alt="Screen Shot 2019-04-22 at 3 13 57 pm" src="https://user-images.githubusercontent.com/40975373/56484176-9333b680-6511-11e9-8ae8-f6000179a55c.png">

<img width="1680" alt="Screen Shot 2019-04-22 at 3 14 04 pm" src="https://user-images.githubusercontent.com/40975373/56484178-9464e380-6511-11e9-84d6-8467ec926be2.png">

## Authors

* **Yiming Zhang** 

## License

This project is licensed under the MIT License.

