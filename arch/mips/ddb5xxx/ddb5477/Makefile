#
# Makefile for NEC DDB-Vrc5477 board
#

obj-y	 		+= ddb5477-platform.o irq.o irq_5477.o setup.o \
			   lcd44780.o

obj-$(CONFIG_RUNTIME_DEBUG) 	+= debug.o
obj-$(CONFIG_KGDB)		+= kgdb_io.o
