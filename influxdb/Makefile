pull: pull-telegraf pull-influxdb pull-chronograf pull-kapacitor

pull-telegraf:
	docker pull telegraf

pull-influxdb:
	docker pull influxdb

pull-chronograf:
	docker pull chronograf

pull-kapacitor:
	docker pull kapacitor

run: run-telegraf run-influxdb run-chronograf run-kapacitor

run-telegraf:
	docker run --net host -d --name telegraf telegraf

run-influxdb:
	docker run --net host -d --name influxdb influxdb

run-chronograf:
	docker run --net host -d --name chronograf chronograf

run-kapacitor:
	docker run --net host -d --name kapacitor kapacitor

clean:
	docker stop telegraf influxdb chronograf kapacitor
	docker rm telegraf influxdb chronograf kapacitor
