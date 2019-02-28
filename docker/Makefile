
help:
	cat Makefile
run:
	docker-compose.exe up
exec:
	docker-compose.exe exec handson-ml bash
build: stop .FORCE
	docker-compose.exe build
rebuild: stop .FORCE
	docker-compose.exe build --force-rm
stop:
	docker.exe stop handson-ml || true; docker.exe rm handson-ml || true;
.FORCE:
