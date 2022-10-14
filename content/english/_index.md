---
####################### Banner #########################
banner:
  title : "All-in-one database access manager on MySQL protocol"
  content : "Tuna is a MySQL syntax-based cloud native relational database access manager with RBAC (role based access control) model. It supports all databases that are mysql wire protocol compatible, and abstracts them as db entities of a single entry. Set up RBAC users/roles/policies/resources on tuna and get a convenient centralized database access management service."
  button:
    enable : true
    label : "Get Started"
    link : "contact/"

##################### Feature ##########################
feature:
  enable : true
  title : "Features of tuna"
  feature_item:
      # feature item loop
    - name : "Plug-and-Play"
      icon : "fas fa-plug"
      content : "No need for additional dependancies or SDKs. Set tuna up properly and connect with your familiar mysql drivers."

      # feature item loop
    - name : "Cloud Native"
      icon : "fas fa-cloud"
      content : "Designed with Cloud Native principles, tuna aggregates mysql compatible databases on different cloud providers into a single point."
      
    # feature item loop
    - name : "SQL Compatible"
      icon : "fas fa-database"
      content : "Tuna supports MySQL wire protocol. Postgres support is under construction."

######################### Service #####################
service:
  enable : true
  service_item:
    # service item loop
    - title : "One-stop access manager"
      images:
      - "images/tuna_arch.png"
      content : "Some databases have RBAC built in and some not. You need to individually configure on all engines you deploy, which add ops cost to your team. With tuna as a centralized RBAC access manager, you enjoy consistent access control experience on all of your databases, as long as they are MySQL compatible."
      button:
        enable : false
        label : "Check it out"
        link : "#"

    # service item loop
    - title : "Versatile compatibility with MySQL protocol"
      images:
      - "images/compatibility.png"
      content : "Compatible with MySQL wire protocol, tuna supports all MySQL-compatible databases. MySQL, MariaDB, ClickHouse, Spanner, TiDB, etc. All of them could be abstracted into entry point on tuna, and tuna provides RBAC access control to all of them."
      button:
        enable : false
        label : "Check it out"
        link : "#"
  

##################### Call to action #####################
call_to_action:
  enable : true
  title : "Ready to get started?"
  image : "images/start.png"
  content : "Start now with tuna service."
  button:
    enable : true
    label : "Get Started"
    link : "contact/"
---
