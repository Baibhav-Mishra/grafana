# Grafana Dashbord

## Setting up Infinity Plugin
1) Install Infinity Plugin [here](https://grafana.com/grafana/plugins/yesoreyeram-infinity-datasource/)
2) Head over to ```http://<grafana-url>/connections/datasources/new```
3) Select Infinity 
4) Select basic Authentication and fill in the Auth details
5) Click on Save and Test
![image](https://github.com/Baibhav-Mishra/grafana/assets/33419322/c2f78d10-cd1e-4f87-8e68-4b8550dd07cd)


## Import JSON files into Grafana
1) Head over to ```http://<grafana-url>/dashboard/import``` eg (http://localhost:3000/dashboard/import)\
2) Import main.json, worker.json, docker-build-worker.json, global-search.json, model-search.json
3) Select the configured Infinity Data Source
![image](https://github.com/Baibhav-Mishra/grafana/assets/33419322/e15f41ba-5008-4cac-9e8c-824d0ca9e337)


## Using the Plugin
1) The dashboard is divided into 4 panes worker, docker-build-worker, Model Search, Global Search
2) The Line text field is used to specify the number of rows to be fetched
3) The Model Id specifies the Model ID of the Model Search Pane
4) The Global Search Text Field specifies the search field for the Global Search Pane
![image](https://github.com/Baibhav-Mishra/grafana/assets/33419322/8d78e1ac-ef60-44c5-94c6-f72e4dbfc273)


