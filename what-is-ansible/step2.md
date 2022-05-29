Ansible uses the concepts of control and managed nodes. It connects from the **control node** (any machine with Ansible installed) to the **managed nodes**, sending commands and instructions to them.

The units of code that Ansible executes on the managed nodes are called **modules**. Each module is invoked by a **task**, and an ordered list of tasks together forms a **playbook**. Users write playbooks with tasks and modules to define the desired state of the system.

The managed machines are represented in a simplistic **inventory** file that groups all the nodes into different categories.

Ansible leverages a very simple language, [YAML](https://docs.ansible.com/ansible/latest/reference_appendices/YAMLSyntax.html), to define playbooks in a human-readable data format that is really easy to understand from day one.