# VPC常见问题 {#concept_lbv_4f4_tdb .concept}

## 1. 专有网络与经典网络的区别是什么？ {#section_d4z_hg4_tdb .section}

-   经典网络类型的云产品，统一部署在阿里云的公共基础网络内。由阿里云统一规划和管理，更适合对网络易用性要求比较高的用户。
-   专有网络是指用户在阿里云的基础网络内建立一个可以自定义的专有隔离网络。与经典网络相比，专有网络比较适合有网络管理能力和需求的用户。

## 2. ECS实例是否可以绑定多个网卡？ {#section_fht_lg4_tdb .section}

经典网络类型的ECS包括两张网卡，分别是公网网卡和私网网卡。VPC类型的ECS目前只支持一张私网网卡。

## 3. 每个专有网络可以有多个路由器？ {#section_vl4_ng4_tdb .section}

每个专有网络有且只有一个路由器，每个路由器维护一个路由表。

## 4. 每个路由表可以建立多少条路由条目？ {#section_arm_pg4_tdb .section}

默认情况下，每个路由表最多可以新建48条路由条目。如需要更多数量的路由条目，可以提交工单申请。

## 5. 每个专有网络能够容纳多少个交换机？ {#section_gmy_qg4_tdb .section}

每个专有网络最多可以新建24个交换机。

## 6. 每个专有网络能够容纳多少个云产品实例？ {#section_c4h_sg4_tdb .section}

每个专有网络最多能够容纳15,000个云产品实例。

## 7. 每个交换机能够容纳多少个云产品实例？ {#section_i3s_5g4_tdb .section}

交换机本身对云产品实例数量没有限制。它能够容纳多少实例，取决于所在专有网络当前的云产品实例数量，即15,000减去当前已保有的云产品数量。

