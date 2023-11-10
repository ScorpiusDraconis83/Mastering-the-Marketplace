---
# Page settings
layout: default
keywords: Azure AppSource Marketplace SaaS
comments: false

hide:
  - toc

title: Choose your offer type
---

If you are deciding which offer type you will be creating, this page is for you. Primary considerations for choosing an offer type include billing options and deployment architectures. This page has resources to help walk through these topics as well as any others related to getting started.

<!-- no toc -->
- [Choose your offer type: Video walkthrough](#choose-your-offer-type-video-walkthrough)
- [Choose your offer type: Flowchart](#choose-your-offer-type-flowchart)
- [Supporting content](#supporting-content)
    - [About SaaS offers](#about-saas-offers)
    - [About Virtual Machine offers](#about-virtual-machine-offers)
    - [About Azure Managed Application offers](#about-azure-managed-application-offers)
    - [About Container offers for Kubernetes apps](#about-container-offers-for-kubernetes-apps)
    - [Microsoft Learn documentation](#microsoft-learn-documentation)


## Choose your offer type: Video walkthrough

<a href="https://go.microsoft.com/fwlink/?linkid=2236766" target="_blank">Video</a>

The Azure Marketplace enables several types of deployment architectures. Are you unsure of which type of offer you need to bring your solution to the Microsoft commercial marketplace? This video walks you through the decision of what type of offer is a good fit for your solution.

## Choose your offer type: Flowchart

Building on top of the above video, follow the questions in the below image to find the right offer type for you.

![Find your offer type](./assets/offer-type-flow.png)

## Supporting content

### About SaaS offers

SaaS offers allow for software that is delivered as SaaS to be transacted on the Azure Marketplace.

- A SaaS offer runs in the publisher’s tenant
- Supports metered billing
- Requires some integration with marketplace SaaS APIs

🚦Learn more about SaaS offers [here](../learning-paths/saas-offers.md).

⏯️ Experience the SaaS Accelerator course [here](../saas-accelerator/index.md).

### About Virtual Machine offers

Virtual Machine offers allow publishers to install their software on a virtual machine.

- Runs in the customer’s tenant and subscription
- Pricing is based on usage of the product
- Does not support metered billing

🚦Learn more about Virtual Machine offers [here](../learning-paths/virtual-machine-offers.md).

### About Azure Managed Application offers

AMAs offer a powerful ARM-based deployment model allowing publishers to make any Azure service part of their solution.

- Runs in the customer’s tenant
- Enables the publisher to manage the resources in the customer’s tenant
- Deploys via an ARM template
- Supports metered billing

🚦Learn more about Managed Application offers [here](../learning-paths/ama-offers.md).

### About Container offers for Kubernetes apps

Container offers for K8s apps enable bundling your software into container images and deploying onto the customer's Azure Kubernetes Service instance.

- Runs in the customer’s tenant and subscription
- Pricing is based on usage of the product
- Supports metered billing

### Microsoft Learn documentation

- <a target="_blank" href="https://docs.microsoft.com/azure/marketplace/publisher-guide-by-offer-type">Publishing guide by offer type</a>
- <a target="_blank" href="https://docs.microsoft.com/en-us/azure/marketplace/marketplace-commercial-transaction-capabilities-and-considerations#transact-overview">The transact overview</a> helps you understand some of the differences between transactable offer types.
