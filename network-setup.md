# Network Setup

Once you have logged into the [Jetstream API web interface](https://jblb.jetstream-cloud.org/dashboard/auth/login/?next=/dashboard/) click on Network -> Network Topology in the left hand menu:

![Network topology](images/network0.png)

Next, click create network in the top right hand corner, and then enter the details for this network.

The network will be called sra-net, and we will create a subnet.

![Network details](images/network1.png)

Set the network addresses to be 192.168.0.0/24 and the gateway to be the first machine on that network: 192.168.0.1

![Network setup](images/network2.png)

Set the allocation pool to be 192.168.0.10,192.168.0.254. This should be more than enough machines and reserves IPs 192.168.0.1-9 for other things if needed.

For the DNS server, I've just used [OpenDNS](https://www.opendns.com)

![Subnet setup](images/network3.png)




