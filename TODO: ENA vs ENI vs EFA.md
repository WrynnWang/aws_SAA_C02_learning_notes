## Elastic Fabric Adapter (EFA)

An Elastic Fabric Adapter (EFA) is a network device that you can attach to your Amazon EC2 instance to `accelerate High Performance Computing (HPC) and machine learning applications`. EFA enables you to achieve the application performance of an on-premises HPC cluster, with the scalability, flexibility, and elasticity provided by the AWS Cloud.

EFA provides lower and more consistent latency and higher throughput than the TCP transport traditionally used in cloud-based HPC systems. It enhances the performance of inter-instance communication that is critical for scaling HPC and machine learning applications. It is optimized to work on the existing AWS network infrastructure and it can scale depending on application requirements.

`OS-bypass` enables HPC and machine learning applications to bypass the operating system kernel and to communicate directly with the EFA device.

ENA and ENI don't have OS-bypass capability.
