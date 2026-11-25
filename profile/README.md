<p align="center">
  <a href="https://highfivelabs.dev">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="hfl-horizontal-color-on-dark.svg">
      <img alt="High Five Labs" src="hfl-horizontal-color-on-light.svg" width="420">
    </picture>
  </a>
</p>

<p align="center">
  <strong>Infrastructure and application deployments, built for the agentic era.</strong><br>
  Agentic speed. Builder judgment.
</p>

<p align="center">
  <a href="https://highfivelabs.dev">Website</a> ·
  <a href="https://registry.highfivelabs.dev">KRM Registry</a> ·
  <a href="https://highfivelabs.dev/careers/">Careers</a> ·
  <a href="mailto:hello@highfivelabs.dev">hello@highfivelabs.dev</a>
</p>

---

We are building **Bundt**, a deployment platform for applications and
infrastructure on the Kubernetes Resource Model (KRM), and **Spectacle**,
which turns specs into checked behavior. Both are coming soon.

Along the way we publish, in the open, the Kubernetes kinds that clouds and
vendors don't ship yet.

### Cloud extensions

Kinds the official cloud operators don't have yet, built on their own
reconcilers. Each build follows upstream `main`.

| Repository | What it adds |
| --- | --- |
| [config-connector-extensions](https://github.com/highfivelabs/config-connector-extensions) | Google Cloud, on Config Connector |
| [ack-extensions](https://github.com/highfivelabs/ack-extensions) | AWS, on AWS Controllers for Kubernetes |
| [aso-extensions](https://github.com/highfivelabs/aso-extensions) | Azure, on Azure Service Operator |

### Vendor extensions

Kinds for SaaS configuration that Terraform manages and the vendors' own
operators don't, generated from OpenAPI specs by
[krm-rest-runtime](https://github.com/highfivelabs/krm-rest-runtime).

[Cloudflare](https://github.com/highfivelabs/cloudflare-krm-extensions) ·
[Confluent](https://github.com/highfivelabs/confluent-krm-extensions) ·
[Datadog](https://github.com/highfivelabs/datadog-krm-extensions) ·
[GitHub](https://github.com/highfivelabs/github-krm-extensions) ·
[GitLab](https://github.com/highfivelabs/gitlab-krm-extensions) ·
[Grafana](https://github.com/highfivelabs/grafana-krm-extensions) ·
[MongoDB Atlas](https://github.com/highfivelabs/mongodbatlas-krm-extensions) ·
[Okta](https://github.com/highfivelabs/okta-krm-extensions) ·
[PagerDuty](https://github.com/highfivelabs/pagerduty-krm-extensions) ·
[Sentry](https://github.com/highfivelabs/sentry-krm-extensions) ·
[Snowflake](https://github.com/highfivelabs/snowflake-krm-extensions) ·
[Vault](https://github.com/highfivelabs/vault-krm-extensions)

### Find a kind

[**registry.highfivelabs.dev**](https://registry.highfivelabs.dev) documents
every KRM provider: Config Connector, ACK, ASO, our extensions, and the chart
packages in [krm-packages](https://github.com/highfivelabs/krm-packages).
