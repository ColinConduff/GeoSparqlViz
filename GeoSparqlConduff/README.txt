GeoSparqlViz

This web application was originally developed by David Mattli using an earlier version of Django.  Colin Conduff updated the application for use with Django 1.8.5.

The app can be found at http://usgs-ybother.srv.mst.edu/viz

Currently there is an error that occurs when users submit a sparql query.  The error occurs because the data being pulled from ontoloty/data is not in json.  As a result the data is not in a format that the code in app.js under the static directory is able to use.  
