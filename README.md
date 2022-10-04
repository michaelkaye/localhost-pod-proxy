# localhost-pod-proxy
Mixed-use content warnings? Want to move a http:// hosted service to localhost of a pod to avoid them?

Run this container within a pod and pass a CMD of the host to proxy to and it'll appear on there.

env vars:

 * NGINX\_PORT: 80
 * NGINX\_TARGET: http://10.0.0.1:8090
