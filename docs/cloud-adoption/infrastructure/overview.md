---
title: "Fusion: Core Infrastructure overview"
description: Overview of Core infrastructure content for Azure Fusion
author: rotycenh
ms.date: 01/14/2019
---

# Fusion: Architectural decision guides

The [Actionable Governance Journeys](../governance/design-guides/overview.md) provided by the Fusion model's governance section provide highly opinionated guidance for establishing governance as part of your Fusion effort. The opinionated nature of this guidance means the assumptions made in the example journeys may not fully reflect the needs of your organization.

The decision guides section of Fusion supplements the governance section's example journeys by providing alternative patterns and models commonly used when crafting design guidance. Use this section to better align the decisions made in example design guidance with your own requirements.

## Design guidance categories

Each of the following categories represents a key foundational technology underlying all cloud deployments, and are represented as an item within the example design guidance checklist. For each of the choices in the example design guides that do not match your requirements, examine the breakdown of the architecture options in the relevant section listed below to choose a pattern or model that better fits your needs.

[Subscriptions](subscriptions/overview.md):
Plan your cloud deployment's subscription design and account structure to match your organization's ownership, billing, and management capabilities.

[Identity](identity/overview.md): Integrate cloud-based identity services with your existing identity resources to support access control within your IT environment.

[Policy Enforcement](policy-enforcement/overview.md):
Define and enforce organizational policy rules for resources and workloads that you deploy to the cloud.

[Resource Grouping](resource-grouping/overview.md):
Ensure that deployment and organization of your organization's cloud-based resources align to enforce resource management and policy requirements.

[Resource Tagging](resource-tagging/overview.md):
Organize your cloud-based resources to support management, access control, and operational efficiency. Resource tagging requires a consistent and well-organized naming and metadata scheme.

[Software Defined Networks](software-defined-networks/overview.md):
Deploy secure workloads to the cloud using rapid deployment and modification of virtualized networking capabilities. Software defined networks (SDNs) support agile workflows, are capable of isolating resources, and can integrate cloud-based systems with your existing IT infrastructure.

[Encryption](encryption/overview.md):
Secure your sensitive data using encryption, which is an important aspect of security within a cloud deployment.

[Logs and Reporting](logs-and-reporting/overview.md):
Monitor log data generated by cloud-based resources. Analyzing data provides health-related insights into the operations, maintenance, and policy enforcement status of workloads.

## Next steps

Learn how [subscriptions and accounts](subscriptions/overview.md) serve as the base of a cloud deployment.

> [!div class="nextstepaction"]
> [Subscriptions](subscriptions/overview.md)