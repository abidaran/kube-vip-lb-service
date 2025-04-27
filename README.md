kube-vip acts like a mini LoadBalancer controller, so you can create a Service of type LoadBalancer, and kube-vip will assign a real IP to it.
specifying loadBalancerClass make kubernetes only picks up services that have its class.
