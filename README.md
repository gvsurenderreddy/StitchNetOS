StitchNetOS (Stitch distributed network operating system) is an experimental cloud operating
system desinged to run web applications in docker containers. The goal of
stitchnetos is to provide a user experience, for deploying and running web-scale
applications, similar to running applications on an individual server, while
providing applicaitons the ability to horizontally scale without any user
intervention. StitchNetOS is agnostic to the underlying hardware resources, such
as storage and networking, and its deployment and operation doesn't require any
modifications to the underlying infrastructure. The only requirement that
StitchNetOS operates on is that the nodes on which StitchNetOS runs have ip-connectivity
to all other nodes in the cluster. In order to achieve its goals, StitchNetOS
comes with its own distributed file system (glusterfs), and a
high-performance, software-based switch (**don't** read SDN) called stitch-switch.
Given that StitchNetOS is agnostic to the underlying cloud infrastructure, this
makes web apps running on StitchNetOS highly portable across different cloud
infrastructure. 
