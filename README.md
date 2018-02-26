HAProxy
=======

* HAProxy server = entry point from outdoor + letsencrypt server


Install
-------

1. Configure HAProxy server

	`ansible-playbook [-i hosts] [--become] [--ask-become-pass] --tags haproxy_configure haproxy_containers_manager.yml`
