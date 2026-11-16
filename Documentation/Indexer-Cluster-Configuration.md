
# 03. Splunk Indexer Cluster Configuration

## 1. Objective

The objective of this activity is to configure multiple Splunk Indexer instances as an Indexer Cluster and establish communication with the Cluster Manager.

## 2. Components Involved

- Cluster Manager
- Indexer 1
- Indexer 2
- Indexer 3

## 3. Configuration File

Configuration File: server.conf

Configuration Location:

$SPLUNK_HOME/etc/system/local/server.conf

## 4. Configuration Activities

1. Log in to the first Indexer instance.
2. Configure the Indexer as a cluster peer.
3. Configure the Cluster Manager URI.
4. Configure the shared cluster security key.
5. Repeat the configuration on the remaining Indexer instances.
6. Restart Splunk services if required.
7. Verify that all Indexers connect to the Cluster Manager.

## 5. Important Concepts

- Indexer Cluster
- Cluster Manager
- Indexer Peers
- Replication Factor (RF)
- Search Factor (SF)
- Bucket Replication
- Bucket Fix-up

## 6. Cluster Configuration Purpose

The Indexer Cluster provides:

- Data replication across Indexers.
- Data availability during Indexer failures.
- Improved search availability.
- Centralized cluster management.
- Better reliability of indexed data.

## 7. Validation

- Verify all expected Indexer peers.
- Check Indexer connectivity with Cluster Manager.
- Verify cluster health.
- Check replication and search factor status.
- Confirm that data is searchable.

## 8. Result

Successfully configured multiple Indexer instances as an Indexer Cluster and established communication with the Cluster Manager.
