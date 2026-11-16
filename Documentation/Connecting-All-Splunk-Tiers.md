
# 09. Connecting All Splunk Tiers

## 1. Objective

Establish communication and integration between all the configured Splunk infrastructure components.

## 2. Integrated Components

- License Manager
- Monitoring Console
- Cluster Manager
- Indexer Cluster
- Search Head Cluster
- Deployer
- Deployment Server
- Universal Forwarders
- Heavy Forwarders

## 3. Integration Activities

1. Connect applicable Splunk instances to the License Manager.
2. Connect indexer peers to the Cluster Manager.
3. Connect Search Head Cluster members to the Indexer Cluster.
4. Configure Deployer communication with Search Head Cluster members.
5. Configure Deployment Server communication with Forwarders.
6. Configure Indexer Discovery on the required Forwarders.
7. Integrate the Monitoring Console with distributed Splunk instances.
8. Verify communication between all required tiers.

## 4. Validation

- Verify License Manager connectivity.
- Check Indexer Cluster status.
- Verify Search Head Cluster status.
- Check Forwarder connectivity.
- Verify Indexer Discovery.
- Check Monitoring Console visibility.

## 5. Result

Successfully integrated the configured Splunk infrastructure components and established communication across the distributed Cluster environment.
