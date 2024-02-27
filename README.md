HAproxy is an open-source TCP/HTTP Loadbalancer and proxy. It distributes workloads upon web server, app;ication server,
DB server to ensure high-availability.

To solve problems with the dependencies in pom.xml, you should find the right version of jsoup in https://central.sonatype.com/

In the folder, there's a file named Dockerfile. you should set up the entrypoint to the path of your haproxy.cfg.

You can use the haproxy through Docker Desktop by using docker compose.
There would be 3 apps and hanproxy server after the configuration.
