# Prometheus and Grafana with Docker Compose

This repository provides a simple and quick implementation of Prometheus and Grafana using Docker Compose.

![prometheus-and-grafana](https://res.cloudinary.com/practicaldev/image/fetch/s--0UNSt1Xb--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/u17n397qj8a8l6u3o2cs.png)

## Starting the applications

To start the applications, simply run the following command at the root of the project:

```docker compose up -d```


## Accessing the applications

* **Prometheus:** Access the web interface at `http://localhost:9090`.
* **Grafana:** Access the web interface at `http://localhost:3000` with the credentials:
    * Username: admin
    * Password: grafana

## Docker Compose file

The `docker-compose.yaml` file contains the configuration for the Prometheus and Grafana services.


## Customization and advanced usage
* **Documentation:** For more information and advanced usage, please consult the official documentation:
    * Prometheus: [https://prometheus.io/docs/introduction/overview/](https://prometheus.io/docs/introduction/overview/)
    * Grafana: [https://grafana.com/docs/](https://grafana.com/docs/)
