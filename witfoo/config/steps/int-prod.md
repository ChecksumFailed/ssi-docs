[title]: # (int product)
[tags]: # (witfoo,introduction)
[priority]: # (1)
[display]: # (all)

# Configuration of WitFoo

<!-- Change the file name, title, and main topic to reflect the name of the integration product. Add the initial configuration steps, usually the initial integration setup steps. -->

## About Appliance Nodes

WitFoo Precinct is deployed via appliance nodes. There are small, medium, and
large options for an all-in-one appliance that contains all three WitFoo
Precinct components. Each node can handle up to 50,000 EPS when clustered (at
optimal resource allocation and core processing level.) 

**Note:** Appliance CPU and RAM must comply with the table below.

Currently, Primary Node is supported for integration. The Primary Node contains
Investigative Engine (IE), Streamer, and Data nodes. This is rated up to 10k
EPS.

## Primary Node

The table below provides details of the primary node.

| Parameters      | Details          |
|-----------------|------------------|
| CPU (min)       | 6                |
| RAM (min)       | 12 GB            |
| Ubuntu Download | Ubuntu 18.04 LTS |

Increasing RAM reduces disk input/output and improves query time. The
recommended RAM for storage is as follows:

-   50GB to 200GB disk space: 8GB RAM

-   1TB disk space: 16GB RAM

-   8TB disk space: 64GB RAM

## About Open Ports

The communication between WitFoo virtual appliance and Secret Server happens
through ports. The all-in-one appliance has the following open ports:

-   SSH (22/tcp)

-   HTTPS (443/tcp)

-   Syslog (514/udp/tcp, 6055/tcp, 6555/tcp)

-   NetFlow (2055/udp)

-   Beats (5044/tcp)
