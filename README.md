# SQLTools Hologres Driver

This is a lightweight fork of the [PostgreSQL driver from SQLTools](https://vscode-sqltools.mteixeira.dev/?umd_source=repository&utm_medium=readme&utm_campaign=pg) to integrate with Alibaba Cloud Hologres.

# Premises and Recommends

This plugin is only for connection testing and local trials, please do not use it in development and production.
- Big data development, recommend to use [DataWorks Data IDE](https://ide-cn-shanghai.data.aliyun.com/) instead.
- Data API development, recommend to use [DataWorks Data API](https://ds-cn-shanghai.data.aliyun.com/) instead.
- Data Analytics development, recommend to use [DataWorks Data Analytics](https://da-cn-shanghai.data.aliyun.com/) instead.
- Managing databases, schemas and tables, recommend to use [HoloWeb](https://holoweb-cn-shanghai.data.aliyun.com/) instead.
- Managing instances, recommend to use [Hologres Console](https://hologram.console.aliyun.com/) instead.

# Quick Start

- Prepare a Hologres instance, goto [Hologres Console](https://hologram.console.aliyun.com/) and apply a instance.
- Open instance public network and enable SSL, then download the SSL certificate.
![Enable Hologres Public Network](https://img.alicdn.com/imgextra/i3/O1CN01UXerRT1MSoslF2qd1_!!6000000001434-0-tps-2878-1508.jpg)
![Enable Hologres SSL](https://img.alicdn.com/imgextra/i1/O1CN01AQ0efO25owjAnLB01_!!6000000007574-0-tps-2878-1506.jpg)
- Click account management and open HoloWeb, then create a user account for connection.
![Goto Account Management](https://img.alicdn.com/imgextra/i2/O1CN01FVEGT51o5kAaMYBPV_!!6000000005174-0-tps-2878-1508.jpg)
![Create a User Account](https://img.alicdn.com/imgextra/i4/O1CN01WbqEJ61J8ieeAPAj0_!!6000000000984-0-tps-2878-1508.jpg)
- Create databases, schemas and tables, then insert data.
![Create Databases, Schemas and Tables](https://img.alicdn.com/imgextra/i3/O1CN01nMNOez1gTXpGjnuv4_!!6000000004143-0-tps-2878-1506.jpg)
![Insert Data](https://img.alicdn.com/imgextra/i1/O1CN01dtGTHg1l9uvlhtyH5_!!6000000004777-0-tps-2878-1508.jpg)
- Install [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools)
- Install [SQLTools Hologres Driver](https://marketplace.visualstudio.com/items?itemName=dataworks.sqltools-driver-hologres) plugin.
- Open SQLTools and choose Hologres as the connection type.
![Hologres SQLTools Demo1](https://img.alicdn.com/imgextra/i2/O1CN01x9Geic1nwaFQC319O_!!6000000005154-0-tps-2878-1406.jpg)
- Input the connection information.
![Hologres SQLTools Demo2](https://img.alicdn.com/imgextra/i1/O1CN01qkv8IH1qhPypLCURj_!!6000000005527-0-tps-2878-1692.jpg)
- Run SQL and check the result.
![Hologres SQLTools Demo3](https://img.alicdn.com/imgextra/i4/O1CN01jwmP0V1aGMjYLSFUN_!!6000000003302-0-tps-2878-1752.jpg)
