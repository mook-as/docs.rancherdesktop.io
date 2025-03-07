---
sidebar_label: Containers
title: Containers
---

<head>
  <link rel="canonical" href="https://docs.rancherdesktop.io/ui/containers"/>
</head>

import TabsConstants from '@site/core/TabsConstants';

<!--- Insert S3 Image Here Once Uploaded -->
<Tabs groupId="os" defaultValue={TabsConstants.defaultOs}>
<TabItem value="Windows">

![Containers_Example](rd-versioned-asset://ui-main/Windows_Containers.png)

</TabItem>
<TabItem value="macOS">

![Containers_Example](rd-versioned-asset://ui-main/macOS_Containers.png)

</TabItem>
<TabItem value="Linux">

![Containers_Example](rd-versioned-asset://ui-main/Linux_Containers.png)

</TabItem>
</Tabs>

:::caution warning

This is an **experimental** feature.

:::

The **Containers** tab offers quick access to manage containers and view key information such as:

 - `State`:
  The container state(s) will be listed in this field, and by default running containers are presented first.
- `Name`:
  The container name(s) will be listed in this field and can be sorted.
- `Image`:
  All image names will be listed in this field and can be sorted.
- `Port(s)`:
  Ports are listed in this field and can be clicked for quick access to a localhost port.
- `Started`:
  Container start-up times will be listed in this field and can be sorted.

The listed information can be sorted in ascending or descending order. Containers can also be filtered with input text in the `Filter` field located at the top right. Bulk selection is available for managing multiple instances at once.

### Container Management

The buttons located at the top of the page will be highlighted when a container is selected and depend on the container's state.

Bulk selection and actions can also be performed on instances with the same state.

The following actions are available:

- `Stop`:
  You can terminate container instances using the `Stop` button.
- `Start`:
  You can initiate container instances using the `Start` button.
- `Delete`:
  You can delete container instances from your system entirely by using the `Delete` button.
- `⋮`:
  This button is located on the right side of the tab view. You can start, stop, or delete container instances depending on their  state using the `⋮` button.
