
# Splunk Cluster Manager Configuration

## 1. Objective

The objective of this activity is to configure the Cluster Manager to centrally manage and coordinate the Indexer Cluster in a Splunk Distributed Environment.

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

1. Log in to the Cluster Manager instance.
2. Configure the Cluster Manager role.
3. Configure the cluster security key.
4. Configure the required cluster communication settings.
5. Connect the indexer peers to the Cluster Manager.
6. Verify the indexer peer connectivity.
7. Check the overall cluster health.

## 5. Important Concepts

- Cluster Manager
- Indexer Peers
- Replication Factor (RF)
- Search Factor (SF)
- Bucket Replication
- Bucket Fix-up
- Cluster Health

## 6. Validation

- Verify Cluster Manager status.
- Check connected indexer peers.
- Verify cluster health.
- Check replication and search factor status.

## 7. Result

Successfully configured the Cluster Manager to centrally manage the Indexer Cluster and monitor the status of connected indexer peers.
