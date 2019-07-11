IMG ?= quay.io/ocpmigrate/mssql-sample-app:microsoft

container:
	docker build -t $(IMG) .

push: 
	docker push $(IMG) 
