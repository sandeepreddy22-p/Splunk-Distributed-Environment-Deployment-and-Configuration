
# 06. Configuring Indexer Discovery in Forwarders Through Deployment Server

## 1. Objective

Configure Indexer Discovery on Forwarders using the Deployment Server to distribute the required configuration.

## 2. Configuration Activities

1. Log in to the Deployment Server.
2. Create or prepare the Forwarder deployment app.
3. Configure outputs.conf.
4. Configure the Cluster Manager URI.
5. Configure the shared security key.
6. Configure the Indexer Discovery output group.
7. Deploy the app to the required Forwarders.
8. Verify that Forwarders receive the configuration.

## 3. Configuration File

outputs.conf

## 4. Example Configuration

[indexer_discovery:cluster_manager]
manager_uri = https://<CLUSTER_MANAGER_IP>:8089
pass4SymmKey = <SHARED_SECRET>

[tcpout]
defaultGroup = indexer_group

[tcpout:indexer_group]
indexerDiscovery = cluster_manager

## 5. Validation

- Verify the deployment app on Forwarders.
- Check Indexer Discovery configuration.
- Verify discovered indexer peers.
- Confirm successful data forwarding.

## 6. Result

Successfully configured Indexer Discovery through the Deployment Server.
