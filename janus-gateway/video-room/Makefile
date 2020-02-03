#
# Makefile for janus streaming
#
PROG=video-room
usage:
	@echo "usage: make [edit|build|run]"

edit e:
	vi main.go

build b:
	go build -o $(PROG)

run r:
	./$(PROG)

#----------------------------------------------------------------------------------
git g:
	@echo "> make (git:g) [update|store]"
git-update gu:
	git add .
	git commit -a -m "update information"
	git push
git-store gs:
	git config credential.helper store
#----------------------------------------------------------------------------------


