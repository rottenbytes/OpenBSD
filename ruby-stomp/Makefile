# $OpenBSD: Makefile,v 1.8 2008/06/14 23:46:37 landry Exp $

COMMENT=	the stomp ruby bindings	

DISTNAME=	stomp-1.1.6
PKGNAME=	ruby-${DISTNAME}p0
CATEGORIES=	devel

# Ruby license
PERMIT_PACKAGE_CDROM=	Yes
PERMIT_PACKAGE_FTP=	Yes
PERMIT_DISTFILES_CDROM=	Yes
PERMIT_DISTFILES_FTP=	Yes

#MASTER_SITES=	${MASTER_SITE_RUBYFORGE:=stomp/}
MASTER_SITES= http://production.cf.rubygems.org/gems/

MODULES=	lang/ruby

CONFIGURE_STYLE=ruby gem

PKG_ARCH=	*

.include <bsd.port.mk>
