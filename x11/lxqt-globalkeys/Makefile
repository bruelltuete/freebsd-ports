PORTNAME=	lxqt-globalkeys
PORTVERSION=	1.3.0
CATEGORIES=	x11
MASTER_SITES=	LXQT

MAINTAINER=	jsm@FreeBSD.org
COMMENT=	Global keyboard shortcuts registration
WWW=		https://lxqt-project.org

LICENSE=	LGPL21+
LICENSE_FILE=	${WRKSRC}/LICENSE

USES=		cmake compiler:c++14-lang kde:5 xorg lxqt perl5 pkgconfig qt:5 tar:xz gnome
USE_PERL5=	build
USE_QT=		buildtools:build qmake:build core dbus gui linguisttools \
		svg widgets x11extras xml
USE_KDE=	windowsystem
USE_LXQT=	buildtools lxqt
USE_GNOME=	glib20
USE_XORG=	ice sm x11 xext
USE_LDCONFIG=	yes

.include <bsd.port.mk>
