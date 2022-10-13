---
####################### Banner #########################
banner:
  title : "MySQL协议下统一的数据库权限管理系统"
  content : "Tuna是基于MySQL语法分析的云原生RBAC关系式数据库权限管理系统。支持所有的兼容MySQL协议的数据库，并将它们在用户角度下抽象为同一个连接点下的不同的本地库来进行统一权限管理。在tuna上设置好RBAC模型下的用户、角色、策略和资源，即可开始体验中心化管理的便捷数据库权限管理服务。"
  button:
    enable : true
    label : "现在试用"
    link : "https://www.github.com"

##################### Feature ##########################
feature:
  enable : true
  title : "Features of tuna"
  feature_item:
      # feature item loop
    - name : "即插即用"
      icon : "fas fa-plug"
      content : "不需要额外的依赖或SDK，只需要在tuna上设置好，就可以使用你习惯的MySQL驱动进行连接。"

      # feature item loop
    - name : "Cloud Native"
      icon : "fas fa-cloud"
      content : "基于云原生基础设施设计，tuna整合不同云平台上的MySQL兼容数据库，成为一个统一的管理系统。"
      
    # feature item loop
    - name : "SQL Compatible"
      icon : "fas fa-database"
      content : "tuna支持MySQL连接协议。后续将Postgres协议。"


######################### Service #####################
service:
  enable : true
  service_item:
      # service item loop
    - title : "一站式权限管理"
      images:
      - "images/olap.png"
      content: "你可能在用很多不同的关系式数据库引擎。有的支持完善的权限管理，而有的没有。同时你还需要对每一个正在运行的引擎进行单独的权限设置和部署，这更增添了维护的成本。使用tuna作为中心式的权限管理系统，你可以对所有的MySQL协议兼容的数据库进行统一的权限管理。"
        
    # service item loop
    - title : "基于MySQL协议的兼容性"
      images:
      - "images/plug.png"
      content : "tuna兼容MySQL协议，因此支持所有兼容MySQL协议的数据库。包括MySQL，ClickHouse，Spanner，TiDB，SingleStore等。所有这些都可以被抽象成为tuna服务下的本地库，并且为它们提供统一的RBAC权限管理服务。"
      button:
        enable : true
        label : "Check it out"
        link : "#"

##################### Call to action #####################
call_to_action:
  enable : true
  title : "开始tuna体验"
  content : "开始tuna为你带来的便捷统一的数据库权限管理服务。"
  image : "images/rocket.png"
  button:
    enable : true
    label : "现在试用"
    link : "contact/"
---
