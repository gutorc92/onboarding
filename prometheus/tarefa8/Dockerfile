FROM flaviostutz/grafana:5.2.4

RUN mkdir /var/lib/grafana/dashboards
COPY uri_dashboard.json /var/lib/grafana/dashboards
COPY all.yml /etc/grafana/provisioning/dashboards
COPY datasource.yml /etc/grafana/provisioning/datasources