
# 05. Connecting Search Heads to Indexer Cluster

## 1. Objective

Establish communication between the Search Head Cluster and the Indexer Cluster.

## 2. Configuration Activities

1. Log in to the Search Head Cluster members.
2. Configure the Cluster Manager URI.
3. Configure the shared cluster security key.
4. Register Search Heads with the Indexer Cluster.
5. Verify the available indexer peers.
6. Confirm distributed search connectivity.

## 3. Example CLI Command

splunk edit cluster-config -mode searchhead -manager_uri https://<CLUSTER_MANAGER_IP>:8089 -secret <CLUSTER_SECRET>

## 4. Validation

- Check Search Head connectivity.
- Verify available search peers.
- Execute a sample SPL search.
- Confirm that indexed data is searchable.

## 5. Result

Successfully connected the Search Head Cluster to the Indexer Cluster.
