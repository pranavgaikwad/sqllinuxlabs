IMG ?= quay.io/ocpmigrate/mssql-server:latest

container:
	docker build -t $(IMG) .

push:
	docker push $(IMG)
