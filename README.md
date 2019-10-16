Table of Contents
=================

   * [首云公开API文档](https://github.com/capitalonline/openapi/blob/master/%E9%A6%96%E4%BA%91OpenAPI(v1.2).md#%E9%A6%96%E4%BA%91%E5%85%AC%E5%BC%80api%E6%96%87%E6%A1%A3)
      * [认证方式](#认证方式)
         * [1.公共请求参数](#1公共请求参数)
         * [2.签名机制](#2签名机制)
            * [步骤一：构造规范化请求字符串](#步骤一构造规范化请求字符串)
            * [步骤二：构造签名字符串](#步骤二构造签名字符串)
         * [2.获取签名代码](#2获取签名代码)
      * [实例相关](#实例相关)
         * [1.CreateInstance](#1createinstance)
         * [2.DeleteInstance](#2deleteinstance)
         * [3. StopInstance](#3-stopinstance)
         * [4.RebootInstance](#4rebootinstance)
         * [5.ModifyInstanceChargeType](#5modifyinstancechargetype)
         * [7.CreateDisk](#7createdisk)
         * [8.ResizeDisk](#8resizedisk)
         * [9.DeleteDisk](#9deletedisk)
         * [11.DescribeInstances](#11describeinstances)
         * [12.ConnectNetworkInterface](#12connectnetworkinterface)
         * [13.<strong>DisconnectNetworkInterface</strong>](#13disconnectnetworkinterface)
         * [14. ModifyIpAddress](#14-modifyipaddress)
         * [15.DescribeInstanceMonitor](#15describeinstancemonitor)
      * [安全组相关](#安全组相关)
         * [1.CreateSecurityGroup](#1createsecuritygroup)
         * [2.DeleteSecurityGroup](#2deletesecuritygroup)
         * [3.ForceDeleteSecurityGroup](#3forcedeletesecuritygroup)
         * [4.DescribeSecurityGroupAttribute](#4describesecuritygroupattribute)
         * [5.ModifySecurityGroupAttribute](#5modifysecuritygroupattribute)
         * [6.DescribeSecurityGroups](#6describesecuritygroups)
         * [7.AddSecurityGroupRule](#7addsecuritygrouprule)
         * [8.RemoveSecurityGroupRule](#8removesecuritygrouprule)
         * [9.ModifySecurityGroupRule](#9modifysecuritygrouprule)
         * [10.JoinSecurityGroup](#10joinsecuritygroup)
         * [11.LeaveSecurityGroup](#11leavesecuritygroup)
      * [模板相关](#模板相关)
         * [1.CreateTemplate](#1createtemplate)
         * [2.DeleteTemplate](#2deletetemplate)
         * [3.SyncTemplate](#3synctemplate)
      * [虚拟数据中心相关](#虚拟数据中心相关)
         * [1.DescribeVdc](#1describevdc)
         * [2.CreateVdc](#2createvdc)
         * [3.DeleteVdc](#3deletevdc)
         * [4.CreatePublicNetwork](#4createpublicnetwork)
         * [5.CreatePrivateNetwork](#5createprivatenetwork)
         * [6.ModifyPublicNetwork](#6modifypublicnetwork)
         * [7.AddPublicIp](#7addpublicip)
         * [8.DeletePublicIp](#8deletepublicip)
         * [9.DeletePublicNetwork](#9deletepublicnetwork)
         * [10.DeletePrivateNetwork](#10deleteprivatenetwork)
         * [11.RenewPublicNetwork](#11renewpublicnetwork)
      * [其他公共接口](#其他公共接口)
         * [1.DescribeAvailableResource](#1describeavailableresource)
         * [2.<strong>DescribeTask</strong>](#2describetask)
      * [附件一](#附件一)
            * [节点名称](#节点名称)
      * [附件二](#附件二)
            * [主机类型](#主机类型)
      * [附件三](#附件三)
            * [带宽类型](#带宽类型)
      * [附件四](#附件四)
            * [公共模板](#公共模板)
      * [示例](#示例)
         * [1.获取请求url](#1获取请求url)
         * [4.创建云主机实例](#4创建云主机实例)
         * [5.修改公网带宽](#5修改公网带宽)
         * [6.修改云主机实例计费类型](#6修改云主机实例计费类型)
         * [7.获取任务状态](#7获取任务状态)
