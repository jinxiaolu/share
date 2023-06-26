# share

```
canal.instance.filter.regex=ecs\\.business.*,ecs\\.permission.*,ecs\\.contract,ecs\\.seal_usage,ecs\\.contract_tag
```

```
canal.mq.dynamicTopic=business-agg-topic:ecs\\.business.*,business-agg-topic:ecs\\.permission.*,business-agg-topic:ecs\\.contract,business-agg-topic:ecs\\.seal_usage,business-agg-topic:ecs\\.contract_tag

canal.mq.partitionHash=ecs\\.business.*:entityId,ecs\\.permission.*:entityId,ecs\\.contract:id,ecs\\.seal_usaged:id,ecs\\.contract_tag:contractId
```
