# load_balancer

Scripts for configuring web servers behind a load balancer.

- `0-custom_http_response_header`: configures nginx with an X-Served-By header set to the server hostname.
- `1-install_load_balancer`: installs HAProxy and load balances web-01 and web-02 with roundrobin.
