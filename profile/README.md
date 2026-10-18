# Scalytics open source

We build open source infrastructure for streaming data and AI agents on Kafka. Every project here is Apache 2.0 unless noted, written mostly in Go, and runs on infrastructure you control. The full overview is at [scalytics.io/open-source](https://www.scalytics.io/open-source).

## Projects

| Project | What it is | Code |
|---|---|---|
| [KafScale](https://kafscale.io/) | Kafka-compatible streaming that keeps the log in S3. Stateless brokers, standard Kafka clients | [KafScale/platform](https://github.com/KafScale/platform) |
| [KafClaw](https://kafclaw.scalytics.io/) | Agent runtime in Go. Connects AI agents through Kafka topics with groups, an orchestrator, shared memory and skill routing | [KafClaw/KafClaw](https://github.com/KafClaw/KafClaw) |
| KafGraph | Shared knowledge graph for agents. Runs as a KafScale processor and reads KafClaw group topics. Open beta | [scalytics/KafGraph](https://github.com/scalytics/KafGraph) |
| [kafSIEM](https://www.scalytics.io/kafsiem) | Entity graph over Kafka agent traffic and OSINT feeds, with provenance back to the source record | [scalytics/kafSIEM](https://github.com/scalytics/kafSIEM) |
| [infinimesh](https://infinimesh.org/) | Self-hosted IoT device platform: device registry, device shadow, MQTT bridge, rules and APIs | [infinimesh/core](https://github.com/infinimesh/core) |
| Scalytics Copilot | Private AI inference with open models: vLLM, an OpenAI-compatible API, chat UI and admin panel | [scalytics/ScalyticsCopilot](https://github.com/scalytics/ScalyticsCopilot) |
| kshark-core | Kafka connectivity diagnostics from DNS to produce and consume, with JSON reports. An example of how agents can use our tools to debug Kafka clusters | [scalytics/kshark-core](https://github.com/scalytics/kshark-core) |
| kaf-mirror | Kafka-to-Kafka replication on franz-go with a web dashboard, REST API and CLI | [scalytics/kaf-mirror](https://github.com/scalytics/kaf-mirror) |

Our founders are the original creators of [Apache Wayang](https://wayang.apache.org/), a top-level project at the Apache Software Foundation.

Some repos in this org are forks we use to send pull requests upstream. Please star, open issues and contribute in the canonical repos listed above.

## Commercial support

[Lascaris](https://www.scalytics.io/lascaris) is our governed, supported platform for AI agents on live Kafka data, built on this open core. For commercial support for any of these projects, [contact us](https://www.scalytics.io/contact).

## Read more

- [AI agents on Kafka](https://www.scalytics.io/ai-agents-on-kafka)
- [novatechflow.com](https://www.novatechflow.com/), the blog of our CTO Alexander Alten, on Kafka, streaming, IoT and agents
