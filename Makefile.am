AUTOMAKE_OPTIONS = foreign

INCLUDES   = -I./

CFLAGS = -Wall -pedantic $(INCLUDES)

LIBS+= -lpthread -lmicrohttpd

bin_PROGRAMS = nodogsplash ndsctl

nodogsplash_SOURCES   =  ./src/gateway.c
nodogsplash_SOURCES   += ./src/auth.c

nodogsplash_SOURCES   += ./src/client_list.c
nodogsplash_SOURCES   += ./src/commandline.c
nodogsplash_SOURCES   += ./src/conf.c
nodogsplash_SOURCES   += ./src/debug.c
nodogsplash_SOURCES   += ./src/fw_iptables.c
nodogsplash_SOURCES   += ./src/http_microhttpd.c
nodogsplash_SOURCES   += ./src/http_microhttpd_utils.c
nodogsplash_SOURCES   += ./src/ndsctl_thread.c
nodogsplash_SOURCES   += ./src/safe.c
nodogsplash_SOURCES   += ./src/tc.c
nodogsplash_SOURCES   += ./src/util.c
nodogsplash_SOURCES   += ./src/template.c

ndsctl_SOURCES   = ./src/ndsctl.c
