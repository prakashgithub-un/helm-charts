#Download the alart manager
[https://prometheus.io/download/](https://github.com/prometheus/alertmanager/releases/download/v0.27.0/alertmanager-0.27.0.linux-amd64.tar.gz)https://github.com/prometheus/alertmanager/releases/download/v0.27.0/alertmanager-0.27.0.linux-amd64.tar.gz

#Extract 
tar -xvzf alertmanager-0.27.0.linux-amd64.tar.gz

#move to folder
cd alertmanager-0.27.0.linux-amd64/

#edit yaml file

#execute
./alertmanager --config.file=alertmanager.yml

#configure to alert manager
cd Prometheus file

vi prometheus.yml

#edit alart manager enable and IP ensure
kubectl restart prometheus.yml
