#
# Purgatory ia64
#
ia64_PURGATORY_SRCS += purgatory/arch/ia64/entry.S
ia64_PURGATORY_SRCS += purgatory/arch/ia64/purgatory-ia64.c
ia64_PURGATORY_SRCS += purgatory/arch/ia64/console-ia64.c
ia64_PURGATORY_SRCS += purgatory/arch/ia64/vga.c

ia64_PURGATORY_EXTRA_CFLAGS = -ffixed-r28

dist += purgatory/arch/ia64/Makefile $(ia64_PURGATORY_SRCS)	\
	purgatory/arch/ia64/io.h purgatory/arch/ia64/purgatory-ia64.h

