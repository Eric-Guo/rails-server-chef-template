Rails Server Chef Template
==========================

1. prepare the server (Using ubuntu 14.04)

	```bash
	bundle exec knife solo prepare ubuntu@10.71.6.27
	```

2. cook the server

	```bash
	bundle exec knife solo cook ubuntu@10.71.6.27 nodes/solo.json
	```
