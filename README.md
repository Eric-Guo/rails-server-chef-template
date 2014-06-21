Rails Server Chef Template
==========================

1. Modify and fill the password in nodes/solo.json

2. prepare the server (Using ubuntu 14.04)

	```bash
	bundle exec knife solo prepare ubuntu@54.238.153.86
	```

3. cook the server

	```bash
	bundle exec knife solo cook ubuntu@54.238.153.86 nodes/solo.json
	```
