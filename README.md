# dolphinscheduler-dashboards

Saved-object exports for DolphinScheduler / Whaleops monitoring dashboards.

## Files

| File | Purpose |
| --- | --- |
| `whaleops_monitoring.ndjson` | Kibana saved objects (NDJSON). |
| `whaleops_monitoring.json` | Same dashboard as JSON. |
| `dolphinscheduler-alert.ndjson` | Alert-related Kibana objects. |

Import the NDJSON in Kibana: **Stack Management → Saved Objects → Import**.

Related poller config: [elasticsearch-http-json](https://github.com/nwlterry/elasticsearch-http-json).
