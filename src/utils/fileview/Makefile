MAKEFLAGS=-s --no-print-directory
am__is_gnu_make = { \
  if test -z '$(MAKELEVEL)'; then \
    false; \
  elif test -n '$(MAKE_HOST)'; then \
    true; \
  elif test -n '$(MAKE_VERSION)' && test -n '$(CURDIR)'; then \
    true; \
  else \
    false; \
  fi; \
}
am__make_running_with_option = \
  case $${target_option-} in \
      ?) ;; \
      *) echo "am__make_running_with_option: internal error: invalid" \
              "target option '$${target_option-}' specified" >&2; \
         exit 1;; \
  esac; \
  has_opt=no; \
  sane_makeflags=$$MAKEFLAGS; \
  if $(am__is_gnu_make); then \
    sane_makeflags=$$MFLAGS; \
  else \
    case $$MAKEFLAGS in \
      *\\[\ \	]*) \
        bs=\\; \
        sane_makeflags=`printf '%s\n' "$$MAKEFLAGS" \
          | sed "s/$$bs$$bs[$$bs $$bs	]*//g"`;; \
    esac; \
  fi; \
  skip_next=no; \
  strip_trailopt () \
  { \
    flg=`printf '%s\n' "$$flg" | sed "s/$$1.*$$//"`; \
  }; \
  for flg in $$sane_makeflags; do \
    test $$skip_next = yes && { skip_next=no; continue; }; \
    case $$flg in \
      *=*|--*) continue;; \
        -*I) strip_trailopt 'I'; skip_next=yes;; \
      -*I?*) strip_trailopt 'I';; \
        -*O) strip_trailopt 'O'; skip_next=yes;; \
      -*O?*) strip_trailopt 'O';; \
        -*l) strip_trailopt 'l'; skip_next=yes;; \
      -*l?*) strip_trailopt 'l';; \
      -[dEDm]) skip_next=yes;; \
      -[JT]) skip_next=yes;; \
    esac; \
    case $$flg in \
      *$$target_option*) has_opt=yes; break;; \
    esac; \
  done; \
  test $$has_opt = yes
am__make_dryrun = (target_option=n; $(am__make_running_with_option))
am__make_keepgoing = (target_option=k; $(am__make_running_with_option))
pkgdatadir = $(datadir)/amule
pkgincludedir = $(includedir)/amule
pkglibdir = $(libdir)/amule
pkglibexecdir = $(libexecdir)/amule
am__cd = CDPATH="$${ZSH_VERSION+.}$(PATH_SEPARATOR)" && cd
install_sh_DATA = $(install_sh) -c -m 644
install_sh_PROGRAM = $(install_sh) -c
install_sh_SCRIPT = $(install_sh) -c
INSTALL_HEADER = $(INSTALL_DATA)
transform = $(program_transform_name)
NORMAL_INSTALL = :
PRE_INSTALL = :
POST_INSTALL = :
NORMAL_UNINSTALL = :
PRE_UNINSTALL = :
POST_UNINSTALL = :
build_triplet = aarch64-unknown-linux-gnu
host_triplet = aarch64-unknown-linux-gnu
noinst_PROGRAMS = mulefileview$(EXEEXT)
subdir = src/utils/fileview
ACLOCAL_M4 = $(top_srcdir)/aclocal.m4
am__aclocal_m4_deps = $(top_srcdir)/m4/GeoIP.m4 \
	$(top_srcdir)/m4/bfd.m4 $(top_srcdir)/m4/boost.m4 \
	$(top_srcdir)/m4/build-tools.m4 $(top_srcdir)/m4/codeset.m4 \
	$(top_srcdir)/m4/cryptopp.m4 $(top_srcdir)/m4/fallocate.m4 \
	$(top_srcdir)/m4/gdlib.m4 $(top_srcdir)/m4/gettext.m4 \
	$(top_srcdir)/m4/glibc21.m4 $(top_srcdir)/m4/iconv.m4 \
	$(top_srcdir)/m4/intdiv0.m4 $(top_srcdir)/m4/inttypes-pri.m4 \
	$(top_srcdir)/m4/inttypes.m4 $(top_srcdir)/m4/inttypes_h.m4 \
	$(top_srcdir)/m4/isc-posix.m4 $(top_srcdir)/m4/kde.m4 \
	$(top_srcdir)/m4/lcmessage.m4 $(top_srcdir)/m4/lib-ld.m4 \
	$(top_srcdir)/m4/lib-link.m4 $(top_srcdir)/m4/lib-prefix.m4 \
	$(top_srcdir)/m4/libpng.m4 $(top_srcdir)/m4/libupnp.m4 \
	$(top_srcdir)/m4/mmap.m4 $(top_srcdir)/m4/muleboost.m4 \
	$(top_srcdir)/m4/nls.m4 $(top_srcdir)/m4/pkg.m4 \
	$(top_srcdir)/m4/plasmamule.m4 $(top_srcdir)/m4/progtest.m4 \
	$(top_srcdir)/m4/qt.m4 $(top_srcdir)/m4/readline.m4 \
	$(top_srcdir)/m4/stdint_h.m4 $(top_srcdir)/m4/uintmax_t.m4 \
	$(top_srcdir)/m4/ulonglong.m4 $(top_srcdir)/m4/wxwin.m4 \
	$(top_srcdir)/m4/zlib.m4 $(top_srcdir)/acinclude.m4 \
	$(top_srcdir)/configure.ac
am__configure_deps = $(am__aclocal_m4_deps) $(CONFIGURE_DEPENDENCIES) \
	$(ACLOCAL_M4)
DIST_COMMON = $(srcdir)/Makefile.am $(am__DIST_COMMON)
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
PROGRAMS = $(noinst_PROGRAMS)
am_mulefileview_OBJECTS = mulefileview-CFile.$(OBJEXT) \
	mulefileview-SafeFile.$(OBJEXT) \
	mulefileview-OtherFunctions.$(OBJEXT) \
	mulefileview-Tag.$(OBJEXT) mulefileview-UInt128.$(OBJEXT) \
	mulefileview-eD2kFiles.$(OBJEXT) \
	mulefileview-FileView.$(OBJEXT) \
	mulefileview-KadFiles.$(OBJEXT) mulefileview-Print.$(OBJEXT)
mulefileview_OBJECTS = $(am_mulefileview_OBJECTS)
am__DEPENDENCIES_1 =
mulefileview_LINK = $(CXXLD) $(mulefileview_CXXFLAGS) $(CXXFLAGS) \
	$(mulefileview_LDFLAGS) $(LDFLAGS) -o $@
am__v_P_1 = :
am__v_GEN_1 = 
am__v_at_1 = 
DEFAULT_INCLUDES = -I. -I$(top_builddir)
depcomp = $(SHELL) $(top_srcdir)/depcomp
am__depfiles_maybe = depfiles
am__mv = mv -f
am__v_lt_1 = 
CXXCOMPILE = $(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) \
	$(AM_CPPFLAGS) $(CPPFLAGS) $(AM_CXXFLAGS) $(CXXFLAGS)
am__v_CXX_1 = 
CXXLD = $(CXX)
CXXLINK = $(CXXLD) $(AM_CXXFLAGS) $(CXXFLAGS) $(AM_LDFLAGS) $(LDFLAGS) \
	-o $@
am__v_CXXLD_1 = 
COMPILE = $(CC) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) \
	$(CPPFLAGS) $(AM_CFLAGS) $(CFLAGS)
am__v_CC_1 = 
CCLD = $(CC)
LINK = $(CCLD) $(AM_CFLAGS) $(CFLAGS) $(AM_LDFLAGS) $(LDFLAGS) -o $@
am__v_CCLD_1 = 
SOURCES = $(mulefileview_SOURCES)
DIST_SOURCES = $(mulefileview_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
am__uniquify_input = $(AWK) '\
  BEGIN { nonempty = 0; } \
  { items[$$0] = 1; nonempty = 1; } \
  END { if (nonempty) { for (i in items) print i; }; } \
'
am__define_uniq_tagged_files = \
  list='$(am__tagged_files)'; \
  unique=`for i in $$list; do \
    if test -f "$$i"; then echo $$i; else echo $(srcdir)/$$i; fi; \
  done | $(am__uniquify_input)`
ETAGS = etags
CTAGS = ctags
am__DIST_COMMON = $(srcdir)/Makefile.in $(top_srcdir)/depcomp \
	$(top_srcdir)/mkinstalldirs
DISTFILES = $(DIST_COMMON) $(DIST_SOURCES) $(TEXINFOS) $(EXTRA_DIST)
ACLOCAL = ${SHELL} /home/pablo/aMule-2.3.3/missing aclocal-1.15
ALCC_MANPAGES = 
ALC_MANPAGES = 
ALLOCA = 
AMTAR = $${TAR-tar}
AMULECMD_MANPAGES = 
AMULEWEB_DEFS = 
AMULE_DAEMON_MANPAGES = 
AMULE_GUI_MANPAGES = 
AR = ar
AUTOCONF = ${SHELL} /home/pablo/aMule-2.3.3/missing autoconf
AUTOHEADER = ${SHELL} /home/pablo/aMule-2.3.3/missing autoheader
AUTOMAKE = ${SHELL} /home/pablo/aMule-2.3.3/missing automake-1.15
AWK = gawk
BFD_CPPFLAGS = -DHAVE_BFD
BFD_LIBS = -lbfd
BOOST_CPPFLAGS = 
BOOST_LDPATH = 
BOOST_ROOT = 
BOOST_SYSTEM_LDFLAGS = 
BOOST_SYSTEM_LDPATH = 
BOOST_SYSTEM_LIBS = 
BUILD_CC = gcc
BUILD_CFLAGS = 
BUILD_CPPFLAGS = 
BUILD_EXEEXT = 
BUILD_INCLUDED_LIBINTL = no
BUILD_LDFLAGS = 
CAS_DEFS = 
CAS_MANPAGES = 
CATOBJEXT = .gmo
CC = gcc
CCDEPMODE = depmode=gcc3
CFLAGS = 
CPP = gcc -E
CPPFLAGS = 
CRYPTOPP_CPPFLAGS = 
CRYPTOPP_LDFLAGS = 
CRYPTOPP_LIBS = -lcryptopp
CXX = g++
CXXCPP = g++ -E
CXXDEPMODE = depmode=gcc3
CXXFLAGS = 
CYGPATH_W = echo
DATADIRNAME = share
DEBUGFLAG = 
DEFS = 
DEPDIR = .deps
DISTCHECK_CONFIGURE_FLAGS = 
ECHO_C = 
ECHO_N = -n
ECHO_T = 
ED2K_MANPAGES = ed2k.1 ed2k.de.1 ed2k.es.1 ed2k.fr.1 ed2k.hu.1 ed2k.it.1 ed2k.ro.1 ed2k.ru.1 ed2k.tr.1 ed2k.zh_TW.1
EGREP = /usr/bin/grep -E
EXEEXT = 
GDLIB_CFLAGS = 
GDLIB_CONFIG_PATH = 
GDLIB_LDFLAGS = 
GDLIB_LIBS = 
GENCAT = gencat
GEOIP_CPPFLAGS = 
GEOIP_LDFLAGS = 
GEOIP_LIBS = 
GLIBC21 = yes
GMSGFMT = /usr/bin/msgfmt
GREP = /usr/bin/grep
INCINTL = 
INSTALL = /usr/bin/install -c
INSTALL_DATA = ${INSTALL} -m 644
INSTALL_PROGRAM = ${INSTALL}
INSTALL_SCRIPT = ${INSTALL}
INSTALL_STRIP_PROGRAM = $(install_sh) -c -s
INSTOBJEXT = .mo
INTLBISON = bison
INTLLIBS = 
INTLOBJS = 
INTL_LIBTOOL_SUFFIX_PREFIX = 
KDE4_CONFIG = 
KDE_APPLNK_PATH = 
KDE_HEADER_DIR = 
KDE_ICON_PATH = 
KDE_MIME_PATH = 
KDE_MODULE_PATH = 
KDE_SERVICE_PATH = 
LD = ld
LDFLAGS = 
LIBICONV = 
LIBINTL = 
LIBOBJS = 
LIBPNG_CFLAGS = 
LIBPNG_CONFIG_PATH = 
LIBPNG_LDFLAGS = 
LIBPNG_LIBS = 
LIBS = 
LIBUPNP_CFLAGS = -pthread
LIBUPNP_CPPFLAGS = -I/usr/include/upnp -DENABLE_UPNP=1
LIBUPNP_LDFLAGS = 
LIBUPNP_LIBS = -pthread -lpthread -lupnp -lixml
LTLIBICONV = 
LTLIBINTL = 
LTLIBOBJS = 
MAINT = #
MAKEINFO = ${SHELL} /home/pablo/aMule-2.3.3/missing makeinfo
MKDIR_P = /usr/bin/mkdir -p
MKINSTALLDIRS = ./mkinstalldirs
MONOLITHIC_MANPAGES = amule.1 amule.de.1 amule.es.1 amule.fr.1 amule.hu.1 amule.it.1 amule.ro.1 amule.ru.1 amule.tr.1 amule.zh_TW.1
MSGFMT = /usr/bin/msgfmt
MSGMERGE = /usr/bin/msgmerge
MULECFLAGS = -w  -g -ggdb -fno-inline -fmessage-length=0
MULECPPFLAGS =  -D__DEBUG__ -DUSE_WX_EXTENSIONS
MULECXXFLAGS = -w  -g -ggdb -fno-inline -fmessage-length=0
MULELDFLAGS =  -lpthread
MULERCFLAGS = -I/usr/lib64/wx/include/gtk3-unicode-3.2 -I/usr/include/wx-3.2 -D_FILE_OFFSET_BITS=64 -DWXUSINGDLL -D__WXGTK__ 
OBJEXT = o
PACKAGE = amule
PACKAGE_BUGREPORT = admin@amule.org
PACKAGE_NAME = aMule
PACKAGE_STRING = aMule 2.3.3
PACKAGE_TARNAME = amule
PACKAGE_URL = 
PACKAGE_VERSION = 2.3.3
PATH_SEPARATOR = :
PKG_CONFIG = /usr/bin/pkg-config
POSUB = po
POW_LIB = 
QT_CORE_CXXFLAGS = 
QT_CORE_LIBS = 
QT_DBUS_LDFLAGS = 
QT_GUI_CXXFLAGS = 
QT_GUI_LIBS = 
QT_MOC = 
RANLIB = ranlib
RC = 
RCFLAGS = 
READLINE_LIBS = 
RESOLV_LIB = 
SED = /usr/bin/sed
SET_MAKE = 
SHELL = /bin/sh
STRIP = strip
SVNDATE = 
USE_INCLUDED_LIBINTL = no
USE_NLS = yes
VERSION = 2.3.3
WEBSERVER_MANPAGES = 
WXBASE_CPPFLAGS = -I/usr/lib64/wx/include/gtk3-unicode-3.2 -I/usr/include/wx-3.2 -D_FILE_OFFSET_BITS=64 -DWXUSINGDLL -D__WXGTK__ -DwxUSE_GUI=0
WXBASE_LIBS = -pthread   -lwx_baseu_net-3.2 -lwx_baseu-3.2 
WXCAS_MANPAGES = 
WX_CFLAGS = -I/usr/lib64/wx/include/gtk3-unicode-3.2 -I/usr/include/wx-3.2 -D_FILE_OFFSET_BITS=64 -DWXUSINGDLL -D__WXGTK__ -pthread
WX_CFLAGS_ONLY = -pthread
WX_CONFIG_PATH = /usr/bin/wx-config
WX_CPPFLAGS = -I/usr/lib64/wx/include/gtk3-unicode-3.2 -I/usr/include/wx-3.2 -D_FILE_OFFSET_BITS=64 -DWXUSINGDLL -D__WXGTK__
WX_CXXFLAGS = -I/usr/lib64/wx/include/gtk3-unicode-3.2 -I/usr/include/wx-3.2 -D_FILE_OFFSET_BITS=64 -DWXUSINGDLL -D__WXGTK__ -pthread
WX_CXXFLAGS_ONLY = 
WX_DEBUG = 0
WX_LIBS = -pthread   -lwx_gtk3u_core-3.2 -lwx_baseu_net-3.2 -lwx_baseu-3.2 
WX_LIBS_STATIC = 
WX_PORT = gtk3
WX_RESCOMP = 
WX_SHARED = 1
WX_UNICODE = 1
WX_VERSION = 3.2.4
WX_VERSION_MAJOR = 3
WX_VERSION_MICRO = 4
WX_VERSION_MINOR = 2
XGETTEXT = /usr/bin/xgettext
ZLIB_CPPFLAGS = 
ZLIB_LDFLAGS = 
ZLIB_LIBS = -lz
abs_builddir = /home/pablo/aMule-2.3.3/src/utils/fileview
abs_srcdir = /home/pablo/aMule-2.3.3/src/utils/fileview
abs_top_builddir = /home/pablo/aMule-2.3.3
abs_top_srcdir = /home/pablo/aMule-2.3.3
ac_ct_BUILD_CC = 
ac_ct_CC = gcc
ac_ct_CXX = g++
am__include = include
am__leading_dot = .
am__quote = 
am__tar = $${TAR-tar} chof - "$$tardir"
am__untar = $${TAR-tar} xf -
bindir = ${exec_prefix}/bin
build = aarch64-unknown-linux-gnu
build_alias = 
build_cpu = aarch64
build_os = linux-gnu
build_vendor = unknown
builddir = .
datadir = ${datarootdir}
datarootdir = ${prefix}/share
docdir = ${datarootdir}/doc/${PACKAGE_TARNAME}
dvidir = ${docdir}
exec_prefix = ${prefix}
host = aarch64-unknown-linux-gnu
host_alias = 
host_cpu = aarch64
host_os = linux-gnu
host_vendor = unknown
htmldir = ${docdir}
includedir = ${prefix}/include
infodir = ${datarootdir}/info
install_sh = ${SHELL} /home/pablo/aMule-2.3.3/install-sh
libdir = ${exec_prefix}/lib
libexecdir = ${exec_prefix}/libexec
localedir = ${datarootdir}/locale
localstatedir = ${prefix}/var
mandir = ${datarootdir}/man
mkdir_p = $(MKDIR_P)
oldincludedir = /usr/include
pdfdir = ${docdir}
prefix = /usr/local
program_transform_name = s,x,x,
psdir = ${docdir}
runstatedir = ${localstatedir}/run
sbindir = ${exec_prefix}/sbin
sharedstatedir = ${prefix}/com
srcdir = .
sysconfdir = ${prefix}/etc
target_alias = 
top_build_prefix = ../../../
top_builddir = ../../..
top_srcdir = ../../..
mulefileview_SOURCES = \
	../../CFile.cpp \
	../../SafeFile.cpp \
	../../OtherFunctions.cpp \
	../../Tag.cpp \
	../../kademlia/utils/UInt128.cpp \
	../../kademlia/kademlia/SearchManager.h \
	eD2kFiles.h \
	eD2kFiles.cpp \
	FileView.cpp \
	KadFiles.h \
	KadFiles.cpp \
	Print.h \
	Print.cpp
mulefileview_DEPENDENCIES = ../../libs/common/libmulecommon.a
mulefileview_CPPFLAGS = $(MULECPPFLAGS) -I$(top_srcdir)/src/libs -I$(top_srcdir)/src/include $(WXBASE_CPPFLAGS) $(CRYPTOPP_CPPFLAGS)
mulefileview_CXXFLAGS = $(MULECXXFLAGS) $(WX_CFLAGS_ONLY) $(WX_CXXFLAGS_ONLY)
mulefileview_LDFLAGS = $(MULELDFLAGS) -L../../libs/common $(CRYPTOPP_LDFLAGS)
mulefileview_LDADD = -lmulecommon $(WXBASE_LIBS) $(CRYPTOPP_LIBS)
all: all-am
.SUFFIXES:
.SUFFIXES: .cpp .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign src/utils/fileview/Makefile'>/dev/null; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign src/utils/fileview/Makefile
Makefile: $(srcdir)/Makefile.in $(top_builddir)/config.status
	@case '$?' in \
	  *config.status*) \
	    cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh;; \
	  *) \
	    echo ' cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe)'>/dev/null; \
	    cd $(top_builddir) && $(SHELL) ./config.status $(subdir)/$@ $(am__depfiles_maybe) denoiser;; \
	esac;
$(top_builddir)/config.status: $(top_srcdir)/configure $(CONFIG_STATUS_DEPENDENCIES)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(top_srcdir)/configure: # $(am__configure_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(ACLOCAL_M4): # $(am__aclocal_m4_deps)
	cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh
$(am__aclocal_m4_deps):
clean-noinstPROGRAMS:
	-test -z "$(noinst_PROGRAMS)" || rm -f $(noinst_PROGRAMS)
mulefileview$(EXEEXT): $(mulefileview_OBJECTS) $(mulefileview_DEPENDENCIES) $(EXTRA_mulefileview_DEPENDENCIES) 
	echo "Linking $(@F)"
	@rm -f mulefileview$(EXEEXT)
	$(mulefileview_LINK) $(mulefileview_OBJECTS) $(mulefileview_LDADD) $(LIBS)
mostlyclean-compile:
	-rm -f *.$(OBJEXT)
distclean-compile:
	-rm -f *.tab.c
include ./$(DEPDIR)/mulefileview-CFile.Po
include ./$(DEPDIR)/mulefileview-FileView.Po
include ./$(DEPDIR)/mulefileview-KadFiles.Po
include ./$(DEPDIR)/mulefileview-OtherFunctions.Po
include ./$(DEPDIR)/mulefileview-Print.Po
include ./$(DEPDIR)/mulefileview-SafeFile.Po
include ./$(DEPDIR)/mulefileview-Tag.Po
include ./$(DEPDIR)/mulefileview-UInt128.Po
include ./$(DEPDIR)/mulefileview-eD2kFiles.Po
.cpp.o:
	echo "Compiling $(<F)"
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
.cpp.obj:
	echo "Compiling $(<F)"
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
mulefileview-CFile.o: ../../CFile.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-CFile.o -MD -MP -MF $(DEPDIR)/mulefileview-CFile.Tpo -c -o mulefileview-CFile.o `test -f '../../CFile.cpp' || echo '$(srcdir)/'`../../CFile.cpp
	$(am__mv) $(DEPDIR)/mulefileview-CFile.Tpo $(DEPDIR)/mulefileview-CFile.Po
mulefileview-CFile.obj: ../../CFile.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-CFile.obj -MD -MP -MF $(DEPDIR)/mulefileview-CFile.Tpo -c -o mulefileview-CFile.obj `if test -f '../../CFile.cpp'; then $(CYGPATH_W) '../../CFile.cpp'; else $(CYGPATH_W) '$(srcdir)/../../CFile.cpp'; fi`
	$(am__mv) $(DEPDIR)/mulefileview-CFile.Tpo $(DEPDIR)/mulefileview-CFile.Po
mulefileview-SafeFile.o: ../../SafeFile.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-SafeFile.o -MD -MP -MF $(DEPDIR)/mulefileview-SafeFile.Tpo -c -o mulefileview-SafeFile.o `test -f '../../SafeFile.cpp' || echo '$(srcdir)/'`../../SafeFile.cpp
	$(am__mv) $(DEPDIR)/mulefileview-SafeFile.Tpo $(DEPDIR)/mulefileview-SafeFile.Po
mulefileview-SafeFile.obj: ../../SafeFile.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-SafeFile.obj -MD -MP -MF $(DEPDIR)/mulefileview-SafeFile.Tpo -c -o mulefileview-SafeFile.obj `if test -f '../../SafeFile.cpp'; then $(CYGPATH_W) '../../SafeFile.cpp'; else $(CYGPATH_W) '$(srcdir)/../../SafeFile.cpp'; fi`
	$(am__mv) $(DEPDIR)/mulefileview-SafeFile.Tpo $(DEPDIR)/mulefileview-SafeFile.Po
mulefileview-OtherFunctions.o: ../../OtherFunctions.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-OtherFunctions.o -MD -MP -MF $(DEPDIR)/mulefileview-OtherFunctions.Tpo -c -o mulefileview-OtherFunctions.o `test -f '../../OtherFunctions.cpp' || echo '$(srcdir)/'`../../OtherFunctions.cpp
	$(am__mv) $(DEPDIR)/mulefileview-OtherFunctions.Tpo $(DEPDIR)/mulefileview-OtherFunctions.Po
mulefileview-OtherFunctions.obj: ../../OtherFunctions.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-OtherFunctions.obj -MD -MP -MF $(DEPDIR)/mulefileview-OtherFunctions.Tpo -c -o mulefileview-OtherFunctions.obj `if test -f '../../OtherFunctions.cpp'; then $(CYGPATH_W) '../../OtherFunctions.cpp'; else $(CYGPATH_W) '$(srcdir)/../../OtherFunctions.cpp'; fi`
	$(am__mv) $(DEPDIR)/mulefileview-OtherFunctions.Tpo $(DEPDIR)/mulefileview-OtherFunctions.Po
mulefileview-Tag.o: ../../Tag.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-Tag.o -MD -MP -MF $(DEPDIR)/mulefileview-Tag.Tpo -c -o mulefileview-Tag.o `test -f '../../Tag.cpp' || echo '$(srcdir)/'`../../Tag.cpp
	$(am__mv) $(DEPDIR)/mulefileview-Tag.Tpo $(DEPDIR)/mulefileview-Tag.Po
mulefileview-Tag.obj: ../../Tag.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-Tag.obj -MD -MP -MF $(DEPDIR)/mulefileview-Tag.Tpo -c -o mulefileview-Tag.obj `if test -f '../../Tag.cpp'; then $(CYGPATH_W) '../../Tag.cpp'; else $(CYGPATH_W) '$(srcdir)/../../Tag.cpp'; fi`
	$(am__mv) $(DEPDIR)/mulefileview-Tag.Tpo $(DEPDIR)/mulefileview-Tag.Po
mulefileview-UInt128.o: ../../kademlia/utils/UInt128.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-UInt128.o -MD -MP -MF $(DEPDIR)/mulefileview-UInt128.Tpo -c -o mulefileview-UInt128.o `test -f '../../kademlia/utils/UInt128.cpp' || echo '$(srcdir)/'`../../kademlia/utils/UInt128.cpp
	$(am__mv) $(DEPDIR)/mulefileview-UInt128.Tpo $(DEPDIR)/mulefileview-UInt128.Po
mulefileview-UInt128.obj: ../../kademlia/utils/UInt128.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-UInt128.obj -MD -MP -MF $(DEPDIR)/mulefileview-UInt128.Tpo -c -o mulefileview-UInt128.obj `if test -f '../../kademlia/utils/UInt128.cpp'; then $(CYGPATH_W) '../../kademlia/utils/UInt128.cpp'; else $(CYGPATH_W) '$(srcdir)/../../kademlia/utils/UInt128.cpp'; fi`
	$(am__mv) $(DEPDIR)/mulefileview-UInt128.Tpo $(DEPDIR)/mulefileview-UInt128.Po
mulefileview-eD2kFiles.o: eD2kFiles.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-eD2kFiles.o -MD -MP -MF $(DEPDIR)/mulefileview-eD2kFiles.Tpo -c -o mulefileview-eD2kFiles.o `test -f 'eD2kFiles.cpp' || echo '$(srcdir)/'`eD2kFiles.cpp
	$(am__mv) $(DEPDIR)/mulefileview-eD2kFiles.Tpo $(DEPDIR)/mulefileview-eD2kFiles.Po
mulefileview-eD2kFiles.obj: eD2kFiles.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-eD2kFiles.obj -MD -MP -MF $(DEPDIR)/mulefileview-eD2kFiles.Tpo -c -o mulefileview-eD2kFiles.obj `if test -f 'eD2kFiles.cpp'; then $(CYGPATH_W) 'eD2kFiles.cpp'; else $(CYGPATH_W) '$(srcdir)/eD2kFiles.cpp'; fi`
	$(am__mv) $(DEPDIR)/mulefileview-eD2kFiles.Tpo $(DEPDIR)/mulefileview-eD2kFiles.Po
mulefileview-FileView.o: FileView.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-FileView.o -MD -MP -MF $(DEPDIR)/mulefileview-FileView.Tpo -c -o mulefileview-FileView.o `test -f 'FileView.cpp' || echo '$(srcdir)/'`FileView.cpp
	$(am__mv) $(DEPDIR)/mulefileview-FileView.Tpo $(DEPDIR)/mulefileview-FileView.Po
mulefileview-FileView.obj: FileView.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-FileView.obj -MD -MP -MF $(DEPDIR)/mulefileview-FileView.Tpo -c -o mulefileview-FileView.obj `if test -f 'FileView.cpp'; then $(CYGPATH_W) 'FileView.cpp'; else $(CYGPATH_W) '$(srcdir)/FileView.cpp'; fi`
	$(am__mv) $(DEPDIR)/mulefileview-FileView.Tpo $(DEPDIR)/mulefileview-FileView.Po
mulefileview-KadFiles.o: KadFiles.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-KadFiles.o -MD -MP -MF $(DEPDIR)/mulefileview-KadFiles.Tpo -c -o mulefileview-KadFiles.o `test -f 'KadFiles.cpp' || echo '$(srcdir)/'`KadFiles.cpp
	$(am__mv) $(DEPDIR)/mulefileview-KadFiles.Tpo $(DEPDIR)/mulefileview-KadFiles.Po
mulefileview-KadFiles.obj: KadFiles.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-KadFiles.obj -MD -MP -MF $(DEPDIR)/mulefileview-KadFiles.Tpo -c -o mulefileview-KadFiles.obj `if test -f 'KadFiles.cpp'; then $(CYGPATH_W) 'KadFiles.cpp'; else $(CYGPATH_W) '$(srcdir)/KadFiles.cpp'; fi`
	$(am__mv) $(DEPDIR)/mulefileview-KadFiles.Tpo $(DEPDIR)/mulefileview-KadFiles.Po
mulefileview-Print.o: Print.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-Print.o -MD -MP -MF $(DEPDIR)/mulefileview-Print.Tpo -c -o mulefileview-Print.o `test -f 'Print.cpp' || echo '$(srcdir)/'`Print.cpp
	$(am__mv) $(DEPDIR)/mulefileview-Print.Tpo $(DEPDIR)/mulefileview-Print.Po
mulefileview-Print.obj: Print.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(mulefileview_CPPFLAGS) $(CPPFLAGS) $(mulefileview_CXXFLAGS) $(CXXFLAGS) -MT mulefileview-Print.obj -MD -MP -MF $(DEPDIR)/mulefileview-Print.Tpo -c -o mulefileview-Print.obj `if test -f 'Print.cpp'; then $(CYGPATH_W) 'Print.cpp'; else $(CYGPATH_W) '$(srcdir)/Print.cpp'; fi`
	$(am__mv) $(DEPDIR)/mulefileview-Print.Tpo $(DEPDIR)/mulefileview-Print.Po
ID: $(am__tagged_files)
	$(am__define_uniq_tagged_files); mkid -fID $$unique
tags: tags-am
TAGS: tags
tags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	set x; \
	here=`pwd`; \
	$(am__define_uniq_tagged_files); \
	shift; \
	if test -z "$(ETAGS_ARGS)$$*$$unique"; then :; else \
	  test -n "$$unique" || unique=$$empty_fix; \
	  if test $$# -gt 0; then \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      "$$@" $$unique; \
	  else \
	    $(ETAGS) $(ETAGSFLAGS) $(AM_ETAGSFLAGS) $(ETAGS_ARGS) \
	      $$unique; \
	  fi; \
	fi
ctags: ctags-am
CTAGS: ctags
ctags-am: $(TAGS_DEPENDENCIES) $(am__tagged_files)
	$(am__define_uniq_tagged_files); \
	test -z "$(CTAGS_ARGS)$$unique" \
	  || $(CTAGS) $(CTAGSFLAGS) $(AM_CTAGSFLAGS) $(CTAGS_ARGS) \
	     $$unique
GTAGS:
	here=`$(am__cd) $(top_builddir) && pwd` \
	  && $(am__cd) $(top_srcdir) \
	  && gtags -i $(GTAGS_ARGS) "$$here"
cscopelist: cscopelist-am
cscopelist-am: $(am__tagged_files)
	list='$(am__tagged_files)'; \
	case "$(srcdir)" in \
	  [\\/]* | ?:[\\/]*) sdir="$(srcdir)" ;; \
	  *) sdir=$(subdir)/$(srcdir) ;; \
	esac; \
	for i in $$list; do \
	  if test -f "$$i"; then \
	    echo "$(subdir)/$$i">/dev/null; \
	  else \
	    echo "$$sdir/$$i">/dev/null; \
	  fi; \
	done >> $(top_builddir)/cscope.files
distclean-tags:
	-rm -f TAGS ID GTAGS GRTAGS GSYMS GPATH tags
distdir: $(DISTFILES)
	@srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	topsrcdirstrip=`echo "$(top_srcdir)" | sed 's/[].[^$$\\*]/\\\\&/g'`; \
	list='$(DISTFILES)'; \
	  dist_files=`for file in $$list; do echo $$file; done | \
	  sed -e "s|^$$srcdirstrip/||;t" \
	      -e "s|^$$topsrcdirstrip/|$(top_builddir)/|;t"`; \
	case $$dist_files in \
	  */*) $(MKDIR_P) `echo "$$dist_files" | \
			   sed '/\//!d;s|^|$(distdir)/|;s,/[^/]*$$,,' | \
			   sort -u` ;; \
	esac; \
	for file in $$dist_files; do \
	  if test -f $$file || test -d $$file; then d=.; else d=$(srcdir); fi; \
	  if test -d $$d/$$file; then \
	    dir=`echo "/$$file" | sed -e 's,/[^/]*$$,,'`; \
	    if test -d "$(distdir)/$$file"; then \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    if test -d $(srcdir)/$$file && test $$d != $(srcdir); then \
	      cp -fpR $(srcdir)/$$file "$(distdir)$$dir" || exit 1; \
	      find "$(distdir)/$$file" -type d ! -perm -700 -exec chmod u+rwx {} \;; \
	    fi; \
	    cp -fpR $$d/$$file "$(distdir)$$dir" || exit 1; \
	  else \
	    test -f "$(distdir)/$$file" \
	    || cp -p $$d/$$file "$(distdir)/$$file" \
	    || exit 1; \
	  fi; \
	done
check-am: all-am
check: check-am
all-am: Makefile $(PROGRAMS)
installdirs:
install: install-am
install-exec: install-exec-am
install-data: install-data-am
uninstall: uninstall-am
install-am: all-am
	@$(MAKE) $(AM_MAKEFLAGS) install-exec-am install-data-am
installcheck: installcheck-am
install-strip:
	if test -z '$(STRIP)'; then \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	      install; \
	else \
	  $(MAKE) $(AM_MAKEFLAGS) INSTALL_PROGRAM="$(INSTALL_STRIP_PROGRAM)" \
	    install_sh_PROGRAM="$(INSTALL_STRIP_PROGRAM)" INSTALL_STRIP_FLAG=-s \
	    "INSTALL_PROGRAM_ENV=STRIPPROG='$(STRIP)'" install; \
	fi
mostlyclean-generic:
clean-generic:
distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)
maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
clean: clean-am
clean-am: clean-generic clean-noinstPROGRAMS mostlyclean-am
distclean: distclean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
distclean-am: clean-am distclean-compile distclean-generic \
	distclean-tags
dvi: dvi-am
dvi-am:
html: html-am
html-am:
info: info-am
info-am:
install-data-am:
install-dvi: install-dvi-am
install-dvi-am:
install-exec-am:
install-html: install-html-am
install-html-am:
install-info: install-info-am
install-info-am:
install-man:
install-pdf: install-pdf-am
install-pdf-am:
install-ps: install-ps-am
install-ps-am:
installcheck-am:
maintainer-clean: maintainer-clean-am
	-rm -rf ./$(DEPDIR)
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic
mostlyclean: mostlyclean-am
mostlyclean-am: mostlyclean-compile mostlyclean-generic
pdf: pdf-am
pdf-am:
ps: ps-am
ps-am:
uninstall-am:
.MAKE: install-am install-strip
.PHONY: CTAGS GTAGS TAGS all all-am check check-am clean clean-generic \
	clean-noinstPROGRAMS cscopelist-am ctags ctags-am distclean \
	distclean-compile distclean-generic distclean-tags distdir dvi \
	dvi-am html html-am info info-am install install-am \
	install-data install-data-am install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-info install-info-am install-man install-pdf \
	install-pdf-am install-ps install-ps-am install-strip \
	installcheck installcheck-am installdirs maintainer-clean \
	maintainer-clean-generic mostlyclean mostlyclean-compile \
	mostlyclean-generic pdf pdf-am ps ps-am tags tags-am uninstall \
	uninstall-am
.PRECIOUS: Makefile
.NOEXPORT:
