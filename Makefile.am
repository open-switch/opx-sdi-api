ACLOCAL_AMFLAGS=-I m4

SUBDIRS = inc

# Build sdi stub library example to link against PAS
lib_LTLIBRARIES = libopx_sdi_stub.la

libopx_sdi_stub_la_SOURCES = examples/sdi_startup.c examples/sdi_entity.c examples/sdi_entity_framework.c examples/sdi_entity_info.c \
                               examples/sdi_entity_reset.c examples/sdi_fan.c examples/sdi_thermal.c \
                               examples/sdi_led.c examples/sdi_media.c

libopx_sdi_stub_la_LDFLAGS = -lopx_common -lopx_logging -lpthread -lrt

libopx_sdi_stub_la_CFLAGS =  -I$(top_srcdir)/inc/opx -I$(includedir)/opx
