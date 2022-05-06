# CSC-227 FINAL 

This is an about me portfolio site where I will begin hosting links to all my projects.

This project uses `Express v4.17.x` and enables health checking and application metrics out of the box. 

## Health checking

Health-checking enables the cloud platform to determine the `readiness` and `liveness` of your application.

 These endpoints will be available for you to use:

- Readiness endpoint: http://localhost:3000/ready
- Liveness endpoint: http://localhost:3000/live

## Application metrics

The [prom-client](https://www.npmjs.com/package/prom-client) module will collect a wide range of resource-centric (CPU, memory) and application-centric (HTTP request responsiveness) metrics from your application, and then expose them as multi-dimensional time-series data through an application endpoint for Prometheus to scrape and aggregate.

 This endpoints will be available for you to use:

- Metrics endpoint: http://localhost:3000/metrics

## License

This stack is licensed under the [EPL 2.0](./LICENSE) license.
