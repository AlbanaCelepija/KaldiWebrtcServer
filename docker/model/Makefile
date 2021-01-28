all: build

build:
	docker build -t smartcommunitylab/kaldi-online-tcp:spanishmodel .

remove:
	docker rmi smartcommunitylab/kaldi-online-tcp:spanishmodele

rebuild: remove build

upload:
	docker push danijel3/kaldi-online-tcp:spanishmodele
