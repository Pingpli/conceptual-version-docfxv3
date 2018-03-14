::: moniker range="contososerver-1.0"

# LOC File Map Test in Versioning page - ENUS - contososerver-1.0

Topology returns a graph of network resources in a virtual network. The graph depicts the interconnection between the resources to represent the end to end network connectivity.

![topology overview][1]

In the portal, Topology returns the resource objects on a per virtual network basis. The relationships are depicted by lines between the resources Resources outside of the Network Watcher region, even if in the resource group will not be displayed. The resources returned in the portal view are a subset of the networking components that are graphed. To see the full list of networking resources you can use PowerShell or REST

> [!NOTE]
> An instance of Network Watcher is required in each region that you want to run Topology on.

As resources are returned the connection between them are modeled under two relationships.

- **Containment** - Example: Virtual Network contains a Subnet which contains a NIC
- **Associated** - Example: A NIC is associated with a VM

### Next steps

Learn how to use PowerShell to retrieve the Topology view by visiting Network Watcher topology with PowerShell

<!--Image references-->

[1]: ./media/network-watcher-topology-overview/topology.png

::: moniker-end
