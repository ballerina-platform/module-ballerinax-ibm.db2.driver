## Overview

This package bundles the IBM Data Server Driver for JDBC and SQLJ (JCC, type 4) so that the
[`ballerinax/ibm.db2`](https://central.ballerina.io/ballerinax/ibm.db2) connector can reach IBM Db2 for LUW,
Db2 for z/OS and Db2 for i servers without any extra driver configuration.

## Compatibility

| | Version |
|:---|:---:|
| Ballerina Language | **2201.13.0** |
| IBM JCC driver | **12.1.5.0** (JDBC 4.38.7) |

## Usage

Import the driver package alongside the connector:

```ballerina
import ballerinax/ibm.db2;
import ballerinax/ibm.db2.driver as _;
```

The IBM JCC driver is distributed under the IBM International Program License Agreement (IPLA).
