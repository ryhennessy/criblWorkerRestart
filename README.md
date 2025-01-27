# criblWorkerRestart

Simple Ansible Playbook that will restart workers one by one from the hosts listed in the inventory file.
Once the node is restarted the playbook will test the health endpoint to validate the Cribl services are fully functional.
