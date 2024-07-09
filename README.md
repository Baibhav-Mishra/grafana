# Grafana

## Setting up Infinity Plugin
1) Install Infinity Plugin [here](https://grafana.com/grafana/plugins/yesoreyeram-infinity-datasource/)
2) Head over to ```http://<grafana-url>/connections/datasources/new```
3) Select basic Authentication and fill in the Auth details
4) Click on Save and Test
![image](https://github.com/Baibhav-Mishra/grafana/assets/33419322/c2f78d10-cd1e-4f87-8e68-4b8550dd07cd)


## Import JSON files into Grafana
1) Head over to ```http://<grafana-url>/dashboard/import``` eg (http://localhost:3000/dashboard/import)\
![image](https://github.com/Baibhav-Mishra/grafana/assets/33419322/e15f41ba-5008-4cac-9e8c-824d0ca9e337)
2) Import main.json, worker.json, docker-build-worker.json, global-search.json, model-search.json
3) Select the configured Infinity Data Source



