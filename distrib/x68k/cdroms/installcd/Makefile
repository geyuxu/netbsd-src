#	$NetBSD: Makefile,v 1.4 2018/09/28 15:05:23 martin Exp $
CDBASE=		x68kcd			# gives ${CDBASE}.iso
CDRELEASE=	true			# include $RELEASEDIR/$MACHINE
CDRELEASE_NODEBUG=	true
CDINSTKERNEL=	../../floppies/instkernel
CDKERNELS=	netbsd-INSTALL.gz	netbsd
CDBUILDEXTRA=	${BOOT}
BOOTXX_CD9660=	${DESTDIR}/usr/mdec/xxboot_cd9660
CDMAKEFSOPTIONS= generic-bootimage=${BOOTXX_CD9660}

.include "${.CURDIR}/../../../common/Makefile.bootcd"
