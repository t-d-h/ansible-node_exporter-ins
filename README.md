# ansible-node_exporter-ins
This is a ansible playbook to install a node_exporter on debian, amd64 architecture. I'm going to add "auto adding node to prometheus" in future 😄

# Run:

ansible-playbook main.yaml -i inventory --extra-vars "exporter_ver"='1.5.0'
