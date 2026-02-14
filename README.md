📘 Azure Governance & Access Control Architecture

This project demonstrates the design and implementation of Role-Based Access Control (RBAC) in Microsoft Azure following enterprise security best practices.

🔍 Scenario

A simulated enterprise environment with:

Production Resource Group

Development Resource Group

Network Resource Group

Role-based access segmentation by scope

Least privilege access enforcement

🛠️ Implemented Concepts

Azure RBAC

Scope hierarchy (Subscription → Resource Group → Resource)

Role inheritance

Security group-based role assignment

Principle of least privilege

🧠 Key Decisions

Roles assigned at the Resource Group level to avoid over-permissioning

Security groups used instead of direct user assignments for scalability

Subscription-level Reader role applied to auditing account

📊 Architecture Overview

(Here you include your diagram)

🎯 Skills Demonstrated

Access control architecture

Azure governance design

Enterprise RBAC strategy

Security boundary planning
