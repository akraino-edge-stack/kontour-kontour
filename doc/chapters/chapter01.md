
###  Kontour KT_KPIs

| S.No | KT_KPI Name                                    | Category | Description                                                                           | Measurement Unit                   |
|------|---------------------------------------------|----------|---------------------------------------------------------------------------------------|------------------------------------|
| 1    | KT_KPI_NET_JITTER                              | Network  | Measure of jitter between two workloads                                               | milliseconds                       |
| 2    | KT_KPI_NET_TCP_BW                              | Network  | Network TCP Bandwidth between two workloads                                           | Gbps                               |
| 3    | KT_KPI_NET_PING_LAT                            | Network  | Ping Lateny between two workloads                                                     | milliseconds                       |
| 4    | KT_KPI_NET_UDP_LAT                             | Network  | UDP Lateny between two workloads                                                      | milliseconds                       |
| 5    | KT_KPI_NET_UDP_THPUT                           | Network  | UDP throughput between two workloads                                                  | Gbps                               |
| 6    | KT_KPI_NET_UDP_PKT_LOSS                        | Network  | Packet loss between two workloads                                                     | Packets lost per million packets   |
| 7    | KT_KPI_COMP_CPU_SCORE                          | Compute  | CPU Performance as per index score                                                    | CPU Index Score                    |
| 8    | KT_KPI_COMP_IPS                                | Compute  | Measure CPU performance as instructions per seconds                                   | Instructions per second            |
| 9    | KT_KPI_COMP_MEM_LAT                            | Compute  | Maximum Memory latency of a workload                                                  | nanoseconds                        |
| 10   | KT_KPI_COMP_MEM_BW                             | Compute  | Memory bandwidth of a workload                                                        | Mibyte/sec                         |
| 11   | KT_KPI_STG_SEQ_RW_LATENCY                   | Storage  | Read Write latency in the workload for sequential readwrite operation in 70:30 ratio. | microseconds                       |
| 12   | KT_KPI_STG_SEQ_READ_ONLY_IOPS               | Storage  | Storage IOPS of a workload for sequential read-only operation                         | Input/Output Operations Per Second |
| 13   | KT_KPI_STG_SEQ_WRITE_ONLY_IOPS              | Storage  | Storage IOPS of a workload for sequential write-only operation                        | Input/Output Operations Per Second |
| 14   | KT_KPI_STG_RAND_RW_LATENCY                  | Storage  | Read Write latency in the workload for random readwrite operation in 70:30 ratio.     | microseconds                       |
| 15   | KT_KPI_STG_RAND_READ_ONLY_IOPS              | Storage  | Storage IOPS of a workload for random read-only operation                             | Input/Output Operations Per Second |
| 16   | KT_KPI_STG_RAND_WRITE_ONLY_IOPS             | Storage  | Storage IOPS of a workload for random write-only operation                            | Input/Output Operations Per Second |
| 17   | KT_KPI_K8S_API_JOB_CREATE_READ_DELETE          | API      | Kubernetes API performance for job creation, read and delete                          | Success Rate %                     |
| 18   | KT_KPI_K8S_API_POD_CREATE_DELETE               | API      | Kubernetes API performance for pod creation and delete                                | Success Rate %                     |
| 19   | KT_KPI_K8S_API_NS_CREATE_DELETE                | API      | Kubernetes API performance for namespace creation and delete                          | Success Rate %                     |
| 20   | KT_KPI_K8S_API_REPCONT_CREATE_SCALE_DELETE     | API      | Kubernetes API performance for replication controller creation, scale and delete      | Success Rate %                     |
| 21   | KT_KPI_K8S_API_REPSET_CREATE_SCALE_DELETE      | API      | Kubernetes API performance for replica set creation, scale and delete                 | Success Rate %                     |
| 22   | KT_KPI_K8S_API_STATEFULSET_CREATE_SCALE_DELETE | API      | Kubernetes API performance for statefulset creation, scale and delete                 | Success Rate %                     |
| 23   | KT_KPI_K8S_API_DEP_CREATE_READ_DELETE          | API      | Kubernetes API performance for deployment creation, read and delete                   | Success Rate %                     |
| 24   | KT_KPI_K8S_API_NODEPORT_CREATE_CHECK_DELETE    | API      | Kubernetes API performance for nodeport creation, check and delete                    | Success Rate %                     |
| 25   | KT_KPI_K8S_SEC_CIS_COMPLIANCE                  | API      | Kubernetes security score measured via CIS benchmark                                  | Security Score                     |
| 26   | KT_KPI_K8S_CONF_E2E_SIG_AUTH                   | API      | Kubernetes conformance for sig-auth                                                   | Compliance %age                    |
| 27   | KT_KPI_K8S_CONF_E2E_SIG_STORAGE                | API      | Kubernetes conformance for sig-storage                                                | Compliance %age                    |
| 28   | KT_KPI_K8S_CONF_E2E_SIG_INSTRUMENTATION        | API      | Kubernetes conformance for sig-instrumentation                                        | Compliance %age                    |
| 29   | KT_KPI_K8S_CONF_E2E_SIG_APPS                   | API      | Kubernetes conformance for sig-apps                                                   | Compliance %age                    |
| 30   | KT_KPI_K8S_CONF_E2E_SIG_CONFORMANCE            | API      | Kubernetes conformance for Conformance                                                | Compliance %age                    |
| 31   | KT_KPI_K8S_CONF_E2E_SIG_NODE_CONFORMANCE       | API      | Kubernetes conformance for NodeConformance                                            | Compliance %age                    |
| 32   | KT_KPI_K8S_CONF_E2E_SIG_API_MACHINERY          | API      | Kubernetes conformance for sig-api-machinery                                          | Compliance %age                    |
| 33   | KT_KPI_K8S_CONF_E2E_SIG_NETWORK                | API      | Kubernetes conformance for sig-networrk                                               | Compliance %age                    |
| 34   | KT_KPI_K8S_CONF_E2E_SIG_CLI                    | API      | Kubernetes conformance for sig-cli                                                    | Compliance %age                    |
| 35   | KT_KPI_K8S_CONF_E2E_SIG_SCHEDULING             | API      | Kubernetes conformance for sig-scheduling                                             | Compliance %age                    |
| 36   | KT_KPI_SVC_NGINX_MAX_LATENCY                   | Service  | Maximum latency in NGINX in serving requests                                          | milliseconds                       |
| 37   | KT_KPI_SVC_REDIS_MAX_THPUT_1MS                 | Service  | Redis Server Max Throughput for Latency Under 1ms                                     | requests/sec                       |
| 38   | KT_KPI_SVC_MONGO_THPUT                         | Service  | Mongo throughput for database operations per second                                   | operations/sec                     |
| 39   | KT_KPI_K8S_NODE_HEALTH                         | Service  | Check health of K8S nodes to be in ready state                                        | Nodes in Ready state               |
| 40   | KT_KPI_K8S_SYS_NS_HEALTH                       | Health   | Check health of all pods in kube-system namespace                                     | All pods in running state          |
| 41   | KT_KPI_OS_API_NOVA_CRUD                        | API      | OpenStack Nova API CRUD performance                                                   | Success Rate %                     |
| 42   | KT_KPI_OS_API_NEUTRON_CRUD                     | API      | OpenStack Neutron API CRUD performance                                                | Success Rate %                     |
| 43   | KT_KPI_OS_API_GLANCE_CRUD                      | API      | OpenStack Glance API CRUD performance                                                 | Success Rate %                     |
| 44   | KT_KPI_OS_API_CINDER_CRUD                      | API      | OpenStack Cinder API CRUD performance                                                 | Success Rate %                     |
| 45   | KT_KPI_OPENSTACK_REFSTACK                      | API      | OpenStack API compliance based on RefStack guidelines                                 | Compliance %age                    |
| 46   | KT_KPI_OS_API_TEMPEST_NOVA                     | API      | OpenStack Nova API functional verification                                            | Compliance %age                    |
| 47   | KT_KPI_OS_API_TEMPEST_NEUTRON                  | API      | OpenStack Neutron API functional verification                                         | Compliance %age                    |
| 48   | KT_KPI_OS_API_TEMPEST_GLANCE                   | API      | OpenStack Glance API functional verification                                          | Compliance %age                    |
| 49   | KT_KPI_OS_API_TEMPEST_CINDER                   | API      | OpenStack Cinder API functional verification                                          | Compliance %age                    |
