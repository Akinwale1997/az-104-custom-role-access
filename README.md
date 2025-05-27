# AZ-104 Project: Custom Role Creation & Assignment

In this project, I created a custom Azure role named "VM Start-Stop Operator" to give limited control over virtual machines. The role allows viewing, starting, and stopping virtual machines — without permission to delete or modify them.

---

## Real-World Scenario

In many real-world environments, junior DevOps or support engineers need to interact with virtual machines without having full admin rights. This project simulates how to give scoped, secure access using custom roles in Azure.

---

## What I Did

- Created a custom role using Microsoft.Compute/virtualMachines permissions:
  - read
  - start
  - powerOff
- Scoped the role at subscription level
- Assigned it to myself (Olarinde Akinwale)

---

## Key Takeaways

- Custom roles give fine-grained control over Azure resources.
- Useful for enforcing the principle of least privilege.
- Scoped assignments help prevent overexposure or accidental deletion.

---

## Screenshots Included

![Permissions Selected](https://github.com/Akinwale1997/az-104-custom-role-access/blob/main/01-custom-role-permission-selected.png?raw=true)
*Selected VM permissions during custom role creation*

![Role Created](https://github.com/Akinwale1997/az-104-custom-role-access/blob/main/02-custom-role-created-confirmation.png?raw=true)
*Confirmation of successful custom role creation*

![Role Assignment](https://github.com/Akinwale1997/az-104-custom-role-access/blob/main/03-custom-role-assignment.png?raw=true)
*Assigning the role to my user account*
---

##
