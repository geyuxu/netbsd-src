# $NetBSD: Makefile,v 1.7 2018/10/14 13:36:32 jmcneill Exp $
# $FreeBSD: src/usr.sbin/acpi/acpidump/Makefile,v 1.7 2003/08/28 03:33:07 njl Exp $

.if (${MACHINE_ARCH} == "i386" || ${MACHINE_ARCH} == "x86_64" || ${MACHINE_ARCH} == "aarch64")
CPPFLAGS+=-I${.CURDIR}/../../../sys -D_KERNTYPES
CPPFLAGS+=-I${.CURDIR}/..
PROG=	acpidump
SRCS=	acpi.c acpi_user.c acpidump.c
.endif

MAN=	acpidump.8
.include <bsd.prog.mk>
