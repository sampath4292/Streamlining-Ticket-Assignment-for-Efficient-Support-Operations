Streamlining Ticket Assignment for Efficient Support Operations 🚀
📌 Project Overview

This project demonstrates the design and implementation of an automated ticket assignment system using the ServiceNow platform. The goal was to streamline support operations by automatically routing tickets to the appropriate support teams based on category, thereby reducing resolution time, improving team productivity, and enhancing customer satisfaction.

🎯 Objective

Automate support ticket routing in ServiceNow.

Reduce manual effort and ticket misrouting.

Ensure role-based access and secure ticket handling.

Improve operational efficiency and customer satisfaction.

🛠 Skills Utilized

User and Group Management

Role Management

Table Configuration

Access Control Lists (ACLs)

Flow Designer (Automation)

📂 Modules Implemented
1️⃣ User & Group Management

Created users representing support team members.

Created groups:

Certification Group

Platform Group

Assigned users to appropriate groups for organized responsibility handling.

2️⃣ Role Creation & Assignment

Defined custom roles for granular access control.

Assigned roles to:

Individual users

Groups (Certificate, Platform)

Custom tables

3️⃣ Table Creation

Built a custom table: Operation_Relations

Stored ticket details (ID, description, category, priority, assigned group).

Applied role-based access using ACLs.

4️⃣ Assigning Roles

Assigned roles to:

Users

Groups

The Operations Ticket Table

Ensured proper segregation of responsibilities.

5️⃣ Access Control Lists (ACLs)

Implemented ACLs at table-level and field-level.

Restricted sensitive fields to administrative roles only.

Secured create, read, update, delete actions.

6️⃣ Flow Designer – Automated Ticket Assignment

Flow 1 – Certificate Group Assignment

Trigger: New Operations Ticket Created

Condition: Category = "Certificate Issue"

Action: Assign to Certificate Group

Flow 2 – Platform Group Assignment

Trigger: New Operations Ticket Created

Condition: Category = "Platform Issue"

Action: Assign to Platform Group

🎥 Demo

👉 Project Demo Video
 [(Insert your video link here)](https://drive.google.com/file/d/1Y2gqp9_MuB2NByahu-OrSOxjZaIwbZxc/view?usp=drive_link)

✅ Conclusion

This project successfully automated ticket assignment in ServiceNow by integrating users, groups, roles, custom tables, ACLs, and Flow Designer automation.

🔹 Reduced manual intervention in ticket routing.

🔹 Ensured faster response times.

🔹 Enforced data security with ACLs.

🔹 Enhanced operational efficiency.

Overall, the project highlights how low-code platforms like ServiceNow can be effectively leveraged to solve real-world IT service management challenges.

📧 Contact

👤 Your Name
📩 sampathsriram4292@gmail.com
💼 https://www.linkedin.com/in/sampath-kumar-sreeram-44b22716b/
