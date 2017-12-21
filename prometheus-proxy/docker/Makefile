default: build push

build:
	docker build -t pambrose/prometheus-test .

push:
	docker push pambrose/prometheus-test

run:
	docker run --rm -p 9090:9090 pambrose/prometheus-test
