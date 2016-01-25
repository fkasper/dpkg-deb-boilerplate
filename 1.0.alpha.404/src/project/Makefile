#!/usr/bin/make -f

EXECUTABLE=project
CP=cp -f
RM=rm -f
BUILD_DIR=/

install:
	$(CP) etc/traefik.toml $(BUILD_DIR)etc
	$(CP) etc/systemd/system/traefik.service $(BUILD_DIR)etc/systemd/system/traefik.service
	$(CP) usr/bin/traefik $(BUILD_DIR)usr/bin

.PHONY: install
