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
bin_PROGRAMS = $(am__EXEEXT_1) $(am__EXEEXT_2)
subdir = src/utils/aLinkCreator/src
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
DIST_COMMON = $(srcdir)/Makefile.am $(noinst_HEADERS) \
	$(am__DIST_COMMON)
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
am__installdirs = "$(DESTDIR)$(bindir)"
PROGRAMS = $(bin_PROGRAMS)
am_alc_OBJECTS = alc-alc.$(OBJEXT) alc-alcframe.$(OBJEXT) \
	alc-ed2khash.$(OBJEXT) alc-alcpix.$(OBJEXT) alc-md4.$(OBJEXT)
alc_OBJECTS = $(am_alc_OBJECTS)
am__DEPENDENCIES_1 =
alc_DEPENDENCIES = $(am__DEPENDENCIES_1) $(am__append_3)
alc_LINK = $(CXXLD) $(alc_CXXFLAGS) $(CXXFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
am_alcc_OBJECTS = alcc-alcc.$(OBJEXT) alcc-ed2khash.$(OBJEXT) \
	alcc-md4.$(OBJEXT)
alcc_OBJECTS = $(am_alcc_OBJECTS) $(nodist_alcc_OBJECTS)
alcc_DEPENDENCIES = $(am__DEPENDENCIES_1)
alcc_LINK = $(CXXLD) $(alcc_CXXFLAGS) $(CXXFLAGS) $(AM_LDFLAGS) \
	$(LDFLAGS) -o $@
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
SOURCES = $(alc_SOURCES) $(alcc_SOURCES) $(nodist_alcc_SOURCES)
DIST_SOURCES = $(alc_SOURCES) $(alcc_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
HEADERS = $(noinst_HEADERS)
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
abs_builddir = /home/pablo/aMule-2.3.3/src/utils/aLinkCreator/src
abs_srcdir = /home/pablo/aMule-2.3.3/src/utils/aLinkCreator/src
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
top_build_prefix = ../../../../
top_builddir = ../../../..
top_srcdir = ../../../..
AM_LDFLAGS = $(MULELDFLAGS)
alc_SOURCES = alc.cpp \
		alcframe.cpp \
		ed2khash.cpp \
		alcpix.cpp \
		md4.cpp
noinst_HEADERS = alc.h \
		alcc.h \
		alcframe.h \
		ed2khash.h \
		alcpix.h \
		md4.h \
		bithelp.h
alc_CPPFLAGS = $(MULECPPFLAGS) $(WX_CPPFLAGS)
alc_CXXFLAGS = $(MULECXXFLAGS) $(WX_CFLAGS_ONLY) $(WX_CXXFLAGS_ONLY)
alc_LDADD = $(WX_LIBS) $(am__append_3)
alcc_SOURCES = alcc.cpp \
		ed2khash.cpp \
		md4.cpp
alcc_CPPFLAGS = $(MULECPPFLAGS) $(WXBASE_CPPFLAGS)
alcc_CXXFLAGS = $(MULECXXFLAGS) $(WX_CFLAGS_ONLY) $(WX_CXXFLAGS_ONLY)
alcc_LDADD = $(WXBASE_LIBS)
MAINTAINERCLEANFILES = Makefile.in
all: all-am
.SUFFIXES:
.SUFFIXES: .rc .$(OBJEXT) .cpp .o .obj
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign src/utils/aLinkCreator/src/Makefile'>/dev/null; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign src/utils/aLinkCreator/src/Makefile
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
install-binPROGRAMS: $(bin_PROGRAMS)
	@$(NORMAL_INSTALL)
	@list='$(bin_PROGRAMS)'; test -n "$(bindir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(bindir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(bindir)" || exit 1; \
	fi; \
	for p in $$list; do echo "$$p $$p"; done | \
	sed 's/$(EXEEXT)$$//' | \
	while read p p1; do if test -f $$p \
	  ; then echo "$$p"; echo "$$p"; else :; fi; \
	done | \
	sed -e 'p;s,.*/,,;n;h' \
	    -e 's|.*|.|' \
	    -e 'p;x;s,.*/,,;s/$(EXEEXT)$$//;$(transform);s/$$/$(EXEEXT)/' | \
	sed 'N;N;N;s,\n, ,g' | \
	$(AWK) 'BEGIN { files["."] = ""; dirs["."] = 1 } \
	  { d=$$3; if (dirs[d] != 1) { print "d", d; dirs[d] = 1 } \
	    if ($$2 == $$4) files[d] = files[d] " " $$1; \
	    else { print "f", $$3 "/" $$4, $$1; } } \
	  END { for (d in files) print "f", d, files[d] }' | \
	while read type dir files; do \
	    if test "$$dir" = .; then dir=; else dir=/$$dir; fi; \
	    test -z "$$files" || { \
	      echo " $(INSTALL_PROGRAM_ENV) $(INSTALL_PROGRAM) $$files '$(DESTDIR)$(bindir)$$dir'">/dev/null; \
	echo "Installing $(bindir)$$dir"; \
	      $(INSTALL_PROGRAM_ENV) $(INSTALL_PROGRAM) $$files "$(DESTDIR)$(bindir)$$dir" || exit $$?; \
	    } \
	; done
uninstall-binPROGRAMS:
	@$(NORMAL_UNINSTALL)
	@list='$(bin_PROGRAMS)'; test -n "$(bindir)" || list=; \
	files=`for p in $$list; do echo "$$p"; done | \
	  sed -e 'h;s,^.*/,,;s/$(EXEEXT)$$//;$(transform)' \
	      -e 's/$$/$(EXEEXT)/' \
	`; \
	test -n "$$list" || exit 0; \
	echo " ( cd '$(DESTDIR)$(bindir)' && rm -f" $$files ")">/dev/null; \
	cd "$(DESTDIR)$(bindir)" && rm -f $$files
clean-binPROGRAMS:
	-test -z "$(bin_PROGRAMS)" || rm -f $(bin_PROGRAMS)
alc$(EXEEXT): $(alc_OBJECTS) $(alc_DEPENDENCIES) $(EXTRA_alc_DEPENDENCIES) 
	echo "Linking $(@F)"
	@rm -f alc$(EXEEXT)
	$(alc_LINK) $(alc_OBJECTS) $(alc_LDADD) $(LIBS)
alcc$(EXEEXT): $(alcc_OBJECTS) $(alcc_DEPENDENCIES) $(EXTRA_alcc_DEPENDENCIES) 
	echo "Linking $(@F)"
	@rm -f alcc$(EXEEXT)
	$(alcc_LINK) $(alcc_OBJECTS) $(alcc_LDADD) $(LIBS)
mostlyclean-compile:
	-rm -f *.$(OBJEXT)
distclean-compile:
	-rm -f *.tab.c
include ./$(DEPDIR)/alc-alc.Po
include ./$(DEPDIR)/alc-alcframe.Po
include ./$(DEPDIR)/alc-alcpix.Po
include ./$(DEPDIR)/alc-ed2khash.Po
include ./$(DEPDIR)/alc-md4.Po
include ./$(DEPDIR)/alcc-alcc.Po
include ./$(DEPDIR)/alcc-ed2khash.Po
include ./$(DEPDIR)/alcc-md4.Po
.cpp.o:
	echo "Compiling $(<F)"
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
.cpp.obj:
	echo "Compiling $(<F)"
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
alc-alc.o: alc.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alc_CPPFLAGS) $(CPPFLAGS) $(alc_CXXFLAGS) $(CXXFLAGS) -MT alc-alc.o -MD -MP -MF $(DEPDIR)/alc-alc.Tpo -c -o alc-alc.o `test -f 'alc.cpp' || echo '$(srcdir)/'`alc.cpp
	$(am__mv) $(DEPDIR)/alc-alc.Tpo $(DEPDIR)/alc-alc.Po
alc-alc.obj: alc.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alc_CPPFLAGS) $(CPPFLAGS) $(alc_CXXFLAGS) $(CXXFLAGS) -MT alc-alc.obj -MD -MP -MF $(DEPDIR)/alc-alc.Tpo -c -o alc-alc.obj `if test -f 'alc.cpp'; then $(CYGPATH_W) 'alc.cpp'; else $(CYGPATH_W) '$(srcdir)/alc.cpp'; fi`
	$(am__mv) $(DEPDIR)/alc-alc.Tpo $(DEPDIR)/alc-alc.Po
alc-alcframe.o: alcframe.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alc_CPPFLAGS) $(CPPFLAGS) $(alc_CXXFLAGS) $(CXXFLAGS) -MT alc-alcframe.o -MD -MP -MF $(DEPDIR)/alc-alcframe.Tpo -c -o alc-alcframe.o `test -f 'alcframe.cpp' || echo '$(srcdir)/'`alcframe.cpp
	$(am__mv) $(DEPDIR)/alc-alcframe.Tpo $(DEPDIR)/alc-alcframe.Po
alc-alcframe.obj: alcframe.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alc_CPPFLAGS) $(CPPFLAGS) $(alc_CXXFLAGS) $(CXXFLAGS) -MT alc-alcframe.obj -MD -MP -MF $(DEPDIR)/alc-alcframe.Tpo -c -o alc-alcframe.obj `if test -f 'alcframe.cpp'; then $(CYGPATH_W) 'alcframe.cpp'; else $(CYGPATH_W) '$(srcdir)/alcframe.cpp'; fi`
	$(am__mv) $(DEPDIR)/alc-alcframe.Tpo $(DEPDIR)/alc-alcframe.Po
alc-ed2khash.o: ed2khash.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alc_CPPFLAGS) $(CPPFLAGS) $(alc_CXXFLAGS) $(CXXFLAGS) -MT alc-ed2khash.o -MD -MP -MF $(DEPDIR)/alc-ed2khash.Tpo -c -o alc-ed2khash.o `test -f 'ed2khash.cpp' || echo '$(srcdir)/'`ed2khash.cpp
	$(am__mv) $(DEPDIR)/alc-ed2khash.Tpo $(DEPDIR)/alc-ed2khash.Po
alc-ed2khash.obj: ed2khash.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alc_CPPFLAGS) $(CPPFLAGS) $(alc_CXXFLAGS) $(CXXFLAGS) -MT alc-ed2khash.obj -MD -MP -MF $(DEPDIR)/alc-ed2khash.Tpo -c -o alc-ed2khash.obj `if test -f 'ed2khash.cpp'; then $(CYGPATH_W) 'ed2khash.cpp'; else $(CYGPATH_W) '$(srcdir)/ed2khash.cpp'; fi`
	$(am__mv) $(DEPDIR)/alc-ed2khash.Tpo $(DEPDIR)/alc-ed2khash.Po
alc-alcpix.o: alcpix.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alc_CPPFLAGS) $(CPPFLAGS) $(alc_CXXFLAGS) $(CXXFLAGS) -MT alc-alcpix.o -MD -MP -MF $(DEPDIR)/alc-alcpix.Tpo -c -o alc-alcpix.o `test -f 'alcpix.cpp' || echo '$(srcdir)/'`alcpix.cpp
	$(am__mv) $(DEPDIR)/alc-alcpix.Tpo $(DEPDIR)/alc-alcpix.Po
alc-alcpix.obj: alcpix.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alc_CPPFLAGS) $(CPPFLAGS) $(alc_CXXFLAGS) $(CXXFLAGS) -MT alc-alcpix.obj -MD -MP -MF $(DEPDIR)/alc-alcpix.Tpo -c -o alc-alcpix.obj `if test -f 'alcpix.cpp'; then $(CYGPATH_W) 'alcpix.cpp'; else $(CYGPATH_W) '$(srcdir)/alcpix.cpp'; fi`
	$(am__mv) $(DEPDIR)/alc-alcpix.Tpo $(DEPDIR)/alc-alcpix.Po
alc-md4.o: md4.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alc_CPPFLAGS) $(CPPFLAGS) $(alc_CXXFLAGS) $(CXXFLAGS) -MT alc-md4.o -MD -MP -MF $(DEPDIR)/alc-md4.Tpo -c -o alc-md4.o `test -f 'md4.cpp' || echo '$(srcdir)/'`md4.cpp
	$(am__mv) $(DEPDIR)/alc-md4.Tpo $(DEPDIR)/alc-md4.Po
alc-md4.obj: md4.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alc_CPPFLAGS) $(CPPFLAGS) $(alc_CXXFLAGS) $(CXXFLAGS) -MT alc-md4.obj -MD -MP -MF $(DEPDIR)/alc-md4.Tpo -c -o alc-md4.obj `if test -f 'md4.cpp'; then $(CYGPATH_W) 'md4.cpp'; else $(CYGPATH_W) '$(srcdir)/md4.cpp'; fi`
	$(am__mv) $(DEPDIR)/alc-md4.Tpo $(DEPDIR)/alc-md4.Po
alcc-alcc.o: alcc.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alcc_CPPFLAGS) $(CPPFLAGS) $(alcc_CXXFLAGS) $(CXXFLAGS) -MT alcc-alcc.o -MD -MP -MF $(DEPDIR)/alcc-alcc.Tpo -c -o alcc-alcc.o `test -f 'alcc.cpp' || echo '$(srcdir)/'`alcc.cpp
	$(am__mv) $(DEPDIR)/alcc-alcc.Tpo $(DEPDIR)/alcc-alcc.Po
alcc-alcc.obj: alcc.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alcc_CPPFLAGS) $(CPPFLAGS) $(alcc_CXXFLAGS) $(CXXFLAGS) -MT alcc-alcc.obj -MD -MP -MF $(DEPDIR)/alcc-alcc.Tpo -c -o alcc-alcc.obj `if test -f 'alcc.cpp'; then $(CYGPATH_W) 'alcc.cpp'; else $(CYGPATH_W) '$(srcdir)/alcc.cpp'; fi`
	$(am__mv) $(DEPDIR)/alcc-alcc.Tpo $(DEPDIR)/alcc-alcc.Po
alcc-ed2khash.o: ed2khash.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alcc_CPPFLAGS) $(CPPFLAGS) $(alcc_CXXFLAGS) $(CXXFLAGS) -MT alcc-ed2khash.o -MD -MP -MF $(DEPDIR)/alcc-ed2khash.Tpo -c -o alcc-ed2khash.o `test -f 'ed2khash.cpp' || echo '$(srcdir)/'`ed2khash.cpp
	$(am__mv) $(DEPDIR)/alcc-ed2khash.Tpo $(DEPDIR)/alcc-ed2khash.Po
alcc-ed2khash.obj: ed2khash.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alcc_CPPFLAGS) $(CPPFLAGS) $(alcc_CXXFLAGS) $(CXXFLAGS) -MT alcc-ed2khash.obj -MD -MP -MF $(DEPDIR)/alcc-ed2khash.Tpo -c -o alcc-ed2khash.obj `if test -f 'ed2khash.cpp'; then $(CYGPATH_W) 'ed2khash.cpp'; else $(CYGPATH_W) '$(srcdir)/ed2khash.cpp'; fi`
	$(am__mv) $(DEPDIR)/alcc-ed2khash.Tpo $(DEPDIR)/alcc-ed2khash.Po
alcc-md4.o: md4.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alcc_CPPFLAGS) $(CPPFLAGS) $(alcc_CXXFLAGS) $(CXXFLAGS) -MT alcc-md4.o -MD -MP -MF $(DEPDIR)/alcc-md4.Tpo -c -o alcc-md4.o `test -f 'md4.cpp' || echo '$(srcdir)/'`md4.cpp
	$(am__mv) $(DEPDIR)/alcc-md4.Tpo $(DEPDIR)/alcc-md4.Po
alcc-md4.obj: md4.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(alcc_CPPFLAGS) $(CPPFLAGS) $(alcc_CXXFLAGS) $(CXXFLAGS) -MT alcc-md4.obj -MD -MP -MF $(DEPDIR)/alcc-md4.Tpo -c -o alcc-md4.obj `if test -f 'md4.cpp'; then $(CYGPATH_W) 'md4.cpp'; else $(CYGPATH_W) '$(srcdir)/md4.cpp'; fi`
	$(am__mv) $(DEPDIR)/alcc-md4.Tpo $(DEPDIR)/alcc-md4.Po
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
all-am: Makefile $(PROGRAMS) $(HEADERS)
installdirs:
	for dir in "$(DESTDIR)$(bindir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
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
	-test -z "$(CLEANFILES)" || rm -f $(CLEANFILES)
distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)
maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
	-test -z "$(MAINTAINERCLEANFILES)" || rm -f $(MAINTAINERCLEANFILES)
clean: clean-am
clean-am: clean-binPROGRAMS clean-generic mostlyclean-am
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
install-exec-am: install-binPROGRAMS
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
uninstall-am: uninstall-binPROGRAMS
.MAKE: install-am install-strip
.PHONY: CTAGS GTAGS TAGS all all-am check check-am clean \
	clean-binPROGRAMS clean-generic cscopelist-am ctags ctags-am \
	distclean distclean-compile distclean-generic distclean-tags \
	distdir dvi dvi-am html html-am info info-am install \
	install-am install-binPROGRAMS install-data install-data-am \
	install-dvi install-dvi-am install-exec install-exec-am \
	install-html install-html-am install-info install-info-am \
	install-man install-pdf install-pdf-am install-ps \
	install-ps-am install-strip installcheck installcheck-am \
	installdirs maintainer-clean maintainer-clean-generic \
	mostlyclean mostlyclean-compile mostlyclean-generic pdf pdf-am \
	ps ps-am tags tags-am uninstall uninstall-am \
	uninstall-binPROGRAMS
.PRECIOUS: Makefile
.NOEXPORT:
