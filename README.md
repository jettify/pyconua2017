# Key Concepts For Scalable Stateful Services


Stateless service architectures can be easily scaled horizontally by adding
backend servers to a front-end load balancer. Such approach is not always
optimal, any application that needs to perform soft real-time work could never
be built using stateless CRUD models, because state locality is required in
order to achieve those response times. 

In this talk I'll cover benefits of stateful services, gave an overview of
existing frameworks that exists in js, scala, .net and golang worlds.
Unfortunately in this area python has little to offer. To fix this we will
figure out key concepts for building scalable stateful services: membership
and dissemination protocols, failure detection and message routing.
