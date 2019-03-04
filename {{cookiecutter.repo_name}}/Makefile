CC ?= gcc
CFLAGS += -Wall
CLFAGS += -g
CFLAGS += -std=c99

.PHONY: all
all: {{ cookiecutter.app_name }}

{{ cookiecutter.app_name }}:
	${CC} ${CFLAGS} {{ cookiecutter.app_name }}.c -o {{ cookiecutter.app_name }}

.PHONY: clean
clean:
	rm -rf {{ cookiecutter.app_name }}
