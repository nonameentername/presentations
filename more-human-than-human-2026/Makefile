all:
	landslide -t theme talk.md

install:
	pip install -r requirements.txt

watch:
	while inotifywait -re close_write .; do make; done
