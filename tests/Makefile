.PHONY: check

QCOW_IMG := atomic.qcow2

check:
	TEST_SUBJECTS=$(QCOW_IMG) ansible-playbook -t atomic -e ansible_python_interpreter=/usr/bin/python3 -i /usr/share/ansible/inventory/standard-inventory-qcow2 ./tests.yml
