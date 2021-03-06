---
layout: page
title: Citrix Service Mesh (CPX) Adapter
name: Meshery Adapter for Citrix Service Mesh
mesh_name: Citrix 
version: "1.0"
port: 10008/tcp
project_status: beta
github_link: https://github.com/layer5io/meshery-cpx
image: /docs/assets/img/service-meshes/citrix.svg
---

# {{ page.name }}

|  Service Mesh  |                   Adapter Status                    | Latest Supported Mesh Version |
| :------------: | :-------------------------------------------------: | :---------------------------: |
| <img src="{{ page.image }}" style="width:20px" /> {{ page.mesh_name }} | [{{ page.project_status }}]({{ page.github_link }}) |       {{page.version}}        |


### Lifecycle management
The {{page.name}} can install **{{page.version}}** of the {{page.mesh_name}}. 

### Install {{ page.mesh_name }}

##### **Choose the Meshery Adapter for Citrix**

<a href="#cpx-adapter">
  <img style="width:500px;" src="/docs/assets/img/adapters/citrix/citrix-adapter.png" />
</a>
<a href="#" class="lightbox" id="cpx-adapter">
  <span style="background-image: url('/docs/assets/img/adapters/citrix/citrix-adapter.png')"></span>
</a>

##### **Click on (+) and choose the `{{page.version}}` of the {{page.mesh_name}} service mesh.**

<a href="#cpx-install">
  <img style="width:500px;" src="/docs/assets/img/adapters/citrix/citrix-install.png" />
</a>
<a href="#" class="lightbox" id="cpx-install">
  <span style="background-image: url('/docs/assets/img/adapters/citrix/citrix-install.png')"></span>
</a>

## Features

1. Lifecycle Management of {{page.mesh_name}}
2. Lifecycle Management of Sample Applications

### Sample Applications

The {{ page.name }} includes a handful of sample applications. Some of these applications are from other service meshes and some of these sample applications are general-purpose examples. Use Meshery to deploy any of these sample applications.

- [Bookinfo](/docs/guides/sample-apps#bookinfo)
    - Follow this [tutorial workshop](https://github.com/layer5io/istio-service-mesh-workshop/blob/master/lab-2/README.md) to set up and deploy the BookInfo sample app on Istio using Meshery. 
- [Httpbin](/docs/guides/sample-apps#httpbin)
    - Httpbin is a simple HTTP request and response service.
- [Hipster](/docs/guides/sample-apps#hipster)
    - Hipster Shop Application is a web-based, e-commerce demo application from the Google Cloud Platform.

### Suggested Topics

- Examine [Meshery's architecture]({{ site.baseurl }}/architecture) and how adapters fit in as a component.
- Learn more about [Meshery Adapters]({{ site.baseurl }}/architecture/adapters).
