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
subdir = src/utils/plasmamule
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
DIST_COMMON = $(srcdir)/Makefile.am $(am__dist_apps_DATA_DIST) \
	$(am__dist_icon_DATA_DIST) $(am__dist_mime_DATA_DIST) \
	$(am__dist_service_DATA_DIST) $(noinst_HEADERS) \
	$(am__DIST_COMMON)
mkinstalldirs = $(SHELL) $(top_srcdir)/mkinstalldirs
CONFIG_HEADER = $(top_builddir)/config.h
CONFIG_CLEAN_FILES =
CONFIG_CLEAN_VPATH_FILES =
am__installdirs = "$(DESTDIR)$(bindir)" "$(DESTDIR)$(modulesdir)" \
	"$(DESTDIR)$(appsdir)" "$(DESTDIR)$(icondir)" \
	"$(DESTDIR)$(mimedir)" "$(DESTDIR)$(servicedir)"
PROGRAMS = $(bin_PROGRAMS) $(modules_PROGRAMS)
am_plasma_applet_plasmamule_so_OBJECTS = plasma_applet_plasmamule_so-plasma-applet-plasmamule.$(OBJEXT) \
	plasma_applet_plasmamule_so-plasmamule-dbus.$(OBJEXT)
nodist_plasma_applet_plasmamule_so_OBJECTS =
plasma_applet_plasmamule_so_OBJECTS =  \
	$(am_plasma_applet_plasmamule_so_OBJECTS) \
	$(nodist_plasma_applet_plasmamule_so_OBJECTS)
plasma_applet_plasmamule_so_LDADD = $(LDADD)
plasma_applet_plasmamule_so_LINK = $(CXXLD) \
	$(plasma_applet_plasmamule_so_CXXFLAGS) $(CXXFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
am_plasma_engine_plasmamule_so_OBJECTS = plasma_engine_plasmamule_so-plasma-engine-plasmamule.$(OBJEXT) \
	plasma_engine_plasmamule_so-qt-emc.$(OBJEXT)
nodist_plasma_engine_plasmamule_so_OBJECTS =
plasma_engine_plasmamule_so_OBJECTS =  \
	$(am_plasma_engine_plasmamule_so_OBJECTS) \
	$(nodist_plasma_engine_plasmamule_so_OBJECTS)
plasma_engine_plasmamule_so_LDADD = $(LDADD)
plasma_engine_plasmamule_so_LINK = $(CXXLD) \
	$(plasma_engine_plasmamule_so_CXXFLAGS) $(CXXFLAGS) \
	$(AM_LDFLAGS) $(LDFLAGS) -o $@
am_plasmamule_engine_feeder_OBJECTS =  \
	plasmamule_engine_feeder-plasmamule-engine-feeder.$(OBJEXT) \
	plasmamule_engine_feeder-plasmamule-dbus.$(OBJEXT)
plasmamule_engine_feeder_OBJECTS =  \
	$(am_plasmamule_engine_feeder_OBJECTS)
am__DEPENDENCIES_1 =
plasmamule_engine_feeder_DEPENDENCIES = $(am__DEPENDENCIES_1) \
	$(am__DEPENDENCIES_1)
plasmamule_engine_feeder_LINK = $(CXXLD) \
	$(plasmamule_engine_feeder_CXXFLAGS) $(CXXFLAGS) $(AM_LDFLAGS) \
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
SOURCES = $(plasma_applet_plasmamule_so_SOURCES) \
	$(nodist_plasma_applet_plasmamule_so_SOURCES) \
	$(plasma_engine_plasmamule_so_SOURCES) \
	$(nodist_plasma_engine_plasmamule_so_SOURCES) \
	$(plasmamule_engine_feeder_SOURCES)
DIST_SOURCES = $(plasma_applet_plasmamule_so_SOURCES) \
	$(plasma_engine_plasmamule_so_SOURCES) \
	$(plasmamule_engine_feeder_SOURCES)
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
am__dist_apps_DATA_DIST = plasmamule-engine-feeder.desktop
am__vpath_adj_setup = srcdirstrip=`echo "$(srcdir)" | sed 's|.|.|g'`;
am__vpath_adj = case $$p in \
    $(srcdir)/*) f=`echo "$$p" | sed "s|^$$srcdirstrip/||"`;; \
    *) f=$$p;; \
  esac;
am__strip_dir = f=`echo $$p | sed -e 's|^.*/||'`;
am__install_max = 40
am__nobase_strip_setup = \
  srcdirstrip=`echo "$(srcdir)" | sed 's/[].[^$$\\*|]/\\\\&/g'`
am__nobase_strip = \
  for p in $$list; do echo "$$p"; done | sed -e "s|$$srcdirstrip/||"
am__nobase_list = $(am__nobase_strip_setup); \
  for p in $$list; do echo "$$p $$p"; done | \
  sed "s| $$srcdirstrip/| |;"' / .*\//!s/ .*/ ./; s,\( .*\)/[^/]*$$,\1,' | \
  $(AWK) 'BEGIN { files["."] = "" } { files[$$2] = files[$$2] " " $$1; \
    if (++n[$$2] == $(am__install_max)) \
      { print $$2, files[$$2]; n[$$2] = 0; files[$$2] = "" } } \
    END { for (dir in files) print dir, files[dir] }'
am__base_list = \
  sed '$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;$$!N;s/\n/ /g' | \
  sed '$$!N;$$!N;$$!N;$$!N;s/\n/ /g'
am__uninstall_files_from_dir = { \
  test -z "$$files" \
    || { test ! -d "$$dir" && test ! -f "$$dir" && test ! -r "$$dir"; } \
    || { echo " ( cd '$$dir' && rm -f" $$files ")"; \
         $(am__cd) "$$dir" && rm -f $$files; }; \
  }
am__dist_icon_DATA_DIST = application-x-emulecollection.svg
am__dist_mime_DATA_DIST = amule.xml
am__dist_service_DATA_DIST = plasma-engine-plasmamule.desktop \
	plasma-applet-plasmamule.desktop ed2k.protocol magnet.protocol
DATA = $(dist_apps_DATA) $(dist_icon_DATA) $(dist_mime_DATA) \
	$(dist_service_DATA)
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
abs_builddir = /home/pablo/aMule-2.3.3/src/utils/plasmamule
abs_srcdir = /home/pablo/aMule-2.3.3/src/utils/plasmamule
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
plasma_engine_plasmamule_so_SOURCES = plasma-engine-plasmamule.cpp qt-emc.cpp
plasma_applet_plasmamule_so_SOURCES = plasma-applet-plasmamule.cpp plasmamule-dbus.cpp
plasmamule_engine_feeder_SOURCES = plasmamule-engine-feeder.cpp plasmamule-dbus.cpp
nodist_plasma_engine_plasmamule_so_SOURCES = plasma-engine-plasmamule.moc
nodist_plasma_applet_plasmamule_so_SOURCES = plasma-applet-plasmamule.moc
plasma_engine_plasmamule_so_CXXFLAGS = -shared -I${KDE_HEADER_DIR} ${QT_CORE_CXXFLAGS} -DPIC -fPIC ${DEBUGFLAG}
plasma_applet_plasmamule_so_CXXFLAGS = -shared -D__IMG_PATH__=\"${KDE_ICON_PATH}\" -I${KDE_HEADER_DIR} ${QT_GUI_CXXFLAGS} -DPIC -fPIC ${DEBUGFLAG}
plasmamule_engine_feeder_CXXFLAGS = -I${KDE_HEADER_DIR} ${QT_GUI_CXXFLAGS} ${DEBUGFLAG}
plasmamule_engine_feeder_LDADD = ${QT_GUI_LIBS} -lkdecore -lplasma ${QT_DBUS_LDFLAGS}
noinst_HEADERS = plasma-engine-plasmamule.h plasma-applet-plasmamule.h plasmamule-dbus.h qt-emc.h
CLEANFILES = *.moc
MAINTAINERCLEANFILES = Makefile.in
all: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) all-am
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
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign src/utils/plasmamule/Makefile'>/dev/null; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign src/utils/plasmamule/Makefile
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
install-modulesPROGRAMS: $(modules_PROGRAMS)
	@$(NORMAL_INSTALL)
	@list='$(modules_PROGRAMS)'; test -n "$(modulesdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(modulesdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(modulesdir)" || exit 1; \
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
	      echo " $(INSTALL_PROGRAM_ENV) $(INSTALL_PROGRAM) $$files '$(DESTDIR)$(modulesdir)$$dir'">/dev/null; \
	echo "Installing $(modulesdir)"; \
	      $(INSTALL_PROGRAM_ENV) $(INSTALL_PROGRAM) $$files "$(DESTDIR)$(modulesdir)$$dir" || exit $$?; \
	    } \
	; done
uninstall-modulesPROGRAMS:
	@$(NORMAL_UNINSTALL)
	@list='$(modules_PROGRAMS)'; test -n "$(modulesdir)" || list=; \
	files=`for p in $$list; do echo "$$p"; done | \
	  sed -e 'h;s,^.*/,,;s/$(EXEEXT)$$//;$(transform)' \
	      -e 's/$$/$(EXEEXT)/' \
	`; \
	test -n "$$list" || exit 0; \
	echo " ( cd '$(DESTDIR)$(modulesdir)' && rm -f" $$files ")">/dev/null; \
	cd "$(DESTDIR)$(modulesdir)" && rm -f $$files
clean-modulesPROGRAMS:
	-test -z "$(modules_PROGRAMS)" || rm -f $(modules_PROGRAMS)
plasma-applet-plasmamule.so$(EXEEXT): $(plasma_applet_plasmamule_so_OBJECTS) $(plasma_applet_plasmamule_so_DEPENDENCIES) $(EXTRA_plasma_applet_plasmamule_so_DEPENDENCIES) 
	echo "Linking $(@F)"
	@rm -f plasma-applet-plasmamule.so$(EXEEXT)
	$(plasma_applet_plasmamule_so_LINK) $(plasma_applet_plasmamule_so_OBJECTS) $(plasma_applet_plasmamule_so_LDADD) $(LIBS)
plasma-engine-plasmamule.so$(EXEEXT): $(plasma_engine_plasmamule_so_OBJECTS) $(plasma_engine_plasmamule_so_DEPENDENCIES) $(EXTRA_plasma_engine_plasmamule_so_DEPENDENCIES) 
	echo "Linking $(@F)"
	@rm -f plasma-engine-plasmamule.so$(EXEEXT)
	$(plasma_engine_plasmamule_so_LINK) $(plasma_engine_plasmamule_so_OBJECTS) $(plasma_engine_plasmamule_so_LDADD) $(LIBS)
plasmamule-engine-feeder$(EXEEXT): $(plasmamule_engine_feeder_OBJECTS) $(plasmamule_engine_feeder_DEPENDENCIES) $(EXTRA_plasmamule_engine_feeder_DEPENDENCIES) 
	echo "Linking $(@F)"
	@rm -f plasmamule-engine-feeder$(EXEEXT)
	$(plasmamule_engine_feeder_LINK) $(plasmamule_engine_feeder_OBJECTS) $(plasmamule_engine_feeder_LDADD) $(LIBS)
mostlyclean-compile:
	-rm -f *.$(OBJEXT)
distclean-compile:
	-rm -f *.tab.c
include ./$(DEPDIR)/plasma_applet_plasmamule_so-plasma-applet-plasmamule.Po
include ./$(DEPDIR)/plasma_applet_plasmamule_so-plasmamule-dbus.Po
include ./$(DEPDIR)/plasma_engine_plasmamule_so-plasma-engine-plasmamule.Po
include ./$(DEPDIR)/plasma_engine_plasmamule_so-qt-emc.Po
include ./$(DEPDIR)/plasmamule_engine_feeder-plasmamule-dbus.Po
include ./$(DEPDIR)/plasmamule_engine_feeder-plasmamule-engine-feeder.Po
.cpp.o:
	echo "Compiling $(<F)"
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ $<
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
.cpp.obj:
	echo "Compiling $(<F)"
	$(CXXCOMPILE) -MT $@ -MD -MP -MF $(DEPDIR)/$*.Tpo -c -o $@ `$(CYGPATH_W) '$<'`
	$(am__mv) $(DEPDIR)/$*.Tpo $(DEPDIR)/$*.Po
plasma_applet_plasmamule_so-plasma-applet-plasmamule.o: plasma-applet-plasmamule.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasma_applet_plasmamule_so_CXXFLAGS) $(CXXFLAGS) -MT plasma_applet_plasmamule_so-plasma-applet-plasmamule.o -MD -MP -MF $(DEPDIR)/plasma_applet_plasmamule_so-plasma-applet-plasmamule.Tpo -c -o plasma_applet_plasmamule_so-plasma-applet-plasmamule.o `test -f 'plasma-applet-plasmamule.cpp' || echo '$(srcdir)/'`plasma-applet-plasmamule.cpp
	$(am__mv) $(DEPDIR)/plasma_applet_plasmamule_so-plasma-applet-plasmamule.Tpo $(DEPDIR)/plasma_applet_plasmamule_so-plasma-applet-plasmamule.Po
plasma_applet_plasmamule_so-plasma-applet-plasmamule.obj: plasma-applet-plasmamule.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasma_applet_plasmamule_so_CXXFLAGS) $(CXXFLAGS) -MT plasma_applet_plasmamule_so-plasma-applet-plasmamule.obj -MD -MP -MF $(DEPDIR)/plasma_applet_plasmamule_so-plasma-applet-plasmamule.Tpo -c -o plasma_applet_plasmamule_so-plasma-applet-plasmamule.obj `if test -f 'plasma-applet-plasmamule.cpp'; then $(CYGPATH_W) 'plasma-applet-plasmamule.cpp'; else $(CYGPATH_W) '$(srcdir)/plasma-applet-plasmamule.cpp'; fi`
	$(am__mv) $(DEPDIR)/plasma_applet_plasmamule_so-plasma-applet-plasmamule.Tpo $(DEPDIR)/plasma_applet_plasmamule_so-plasma-applet-plasmamule.Po
plasma_applet_plasmamule_so-plasmamule-dbus.o: plasmamule-dbus.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasma_applet_plasmamule_so_CXXFLAGS) $(CXXFLAGS) -MT plasma_applet_plasmamule_so-plasmamule-dbus.o -MD -MP -MF $(DEPDIR)/plasma_applet_plasmamule_so-plasmamule-dbus.Tpo -c -o plasma_applet_plasmamule_so-plasmamule-dbus.o `test -f 'plasmamule-dbus.cpp' || echo '$(srcdir)/'`plasmamule-dbus.cpp
	$(am__mv) $(DEPDIR)/plasma_applet_plasmamule_so-plasmamule-dbus.Tpo $(DEPDIR)/plasma_applet_plasmamule_so-plasmamule-dbus.Po
plasma_applet_plasmamule_so-plasmamule-dbus.obj: plasmamule-dbus.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasma_applet_plasmamule_so_CXXFLAGS) $(CXXFLAGS) -MT plasma_applet_plasmamule_so-plasmamule-dbus.obj -MD -MP -MF $(DEPDIR)/plasma_applet_plasmamule_so-plasmamule-dbus.Tpo -c -o plasma_applet_plasmamule_so-plasmamule-dbus.obj `if test -f 'plasmamule-dbus.cpp'; then $(CYGPATH_W) 'plasmamule-dbus.cpp'; else $(CYGPATH_W) '$(srcdir)/plasmamule-dbus.cpp'; fi`
	$(am__mv) $(DEPDIR)/plasma_applet_plasmamule_so-plasmamule-dbus.Tpo $(DEPDIR)/plasma_applet_plasmamule_so-plasmamule-dbus.Po
plasma_engine_plasmamule_so-plasma-engine-plasmamule.o: plasma-engine-plasmamule.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasma_engine_plasmamule_so_CXXFLAGS) $(CXXFLAGS) -MT plasma_engine_plasmamule_so-plasma-engine-plasmamule.o -MD -MP -MF $(DEPDIR)/plasma_engine_plasmamule_so-plasma-engine-plasmamule.Tpo -c -o plasma_engine_plasmamule_so-plasma-engine-plasmamule.o `test -f 'plasma-engine-plasmamule.cpp' || echo '$(srcdir)/'`plasma-engine-plasmamule.cpp
	$(am__mv) $(DEPDIR)/plasma_engine_plasmamule_so-plasma-engine-plasmamule.Tpo $(DEPDIR)/plasma_engine_plasmamule_so-plasma-engine-plasmamule.Po
plasma_engine_plasmamule_so-plasma-engine-plasmamule.obj: plasma-engine-plasmamule.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasma_engine_plasmamule_so_CXXFLAGS) $(CXXFLAGS) -MT plasma_engine_plasmamule_so-plasma-engine-plasmamule.obj -MD -MP -MF $(DEPDIR)/plasma_engine_plasmamule_so-plasma-engine-plasmamule.Tpo -c -o plasma_engine_plasmamule_so-plasma-engine-plasmamule.obj `if test -f 'plasma-engine-plasmamule.cpp'; then $(CYGPATH_W) 'plasma-engine-plasmamule.cpp'; else $(CYGPATH_W) '$(srcdir)/plasma-engine-plasmamule.cpp'; fi`
	$(am__mv) $(DEPDIR)/plasma_engine_plasmamule_so-plasma-engine-plasmamule.Tpo $(DEPDIR)/plasma_engine_plasmamule_so-plasma-engine-plasmamule.Po
plasma_engine_plasmamule_so-qt-emc.o: qt-emc.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasma_engine_plasmamule_so_CXXFLAGS) $(CXXFLAGS) -MT plasma_engine_plasmamule_so-qt-emc.o -MD -MP -MF $(DEPDIR)/plasma_engine_plasmamule_so-qt-emc.Tpo -c -o plasma_engine_plasmamule_so-qt-emc.o `test -f 'qt-emc.cpp' || echo '$(srcdir)/'`qt-emc.cpp
	$(am__mv) $(DEPDIR)/plasma_engine_plasmamule_so-qt-emc.Tpo $(DEPDIR)/plasma_engine_plasmamule_so-qt-emc.Po
plasma_engine_plasmamule_so-qt-emc.obj: qt-emc.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasma_engine_plasmamule_so_CXXFLAGS) $(CXXFLAGS) -MT plasma_engine_plasmamule_so-qt-emc.obj -MD -MP -MF $(DEPDIR)/plasma_engine_plasmamule_so-qt-emc.Tpo -c -o plasma_engine_plasmamule_so-qt-emc.obj `if test -f 'qt-emc.cpp'; then $(CYGPATH_W) 'qt-emc.cpp'; else $(CYGPATH_W) '$(srcdir)/qt-emc.cpp'; fi`
	$(am__mv) $(DEPDIR)/plasma_engine_plasmamule_so-qt-emc.Tpo $(DEPDIR)/plasma_engine_plasmamule_so-qt-emc.Po
plasmamule_engine_feeder-plasmamule-engine-feeder.o: plasmamule-engine-feeder.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasmamule_engine_feeder_CXXFLAGS) $(CXXFLAGS) -MT plasmamule_engine_feeder-plasmamule-engine-feeder.o -MD -MP -MF $(DEPDIR)/plasmamule_engine_feeder-plasmamule-engine-feeder.Tpo -c -o plasmamule_engine_feeder-plasmamule-engine-feeder.o `test -f 'plasmamule-engine-feeder.cpp' || echo '$(srcdir)/'`plasmamule-engine-feeder.cpp
	$(am__mv) $(DEPDIR)/plasmamule_engine_feeder-plasmamule-engine-feeder.Tpo $(DEPDIR)/plasmamule_engine_feeder-plasmamule-engine-feeder.Po
plasmamule_engine_feeder-plasmamule-engine-feeder.obj: plasmamule-engine-feeder.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasmamule_engine_feeder_CXXFLAGS) $(CXXFLAGS) -MT plasmamule_engine_feeder-plasmamule-engine-feeder.obj -MD -MP -MF $(DEPDIR)/plasmamule_engine_feeder-plasmamule-engine-feeder.Tpo -c -o plasmamule_engine_feeder-plasmamule-engine-feeder.obj `if test -f 'plasmamule-engine-feeder.cpp'; then $(CYGPATH_W) 'plasmamule-engine-feeder.cpp'; else $(CYGPATH_W) '$(srcdir)/plasmamule-engine-feeder.cpp'; fi`
	$(am__mv) $(DEPDIR)/plasmamule_engine_feeder-plasmamule-engine-feeder.Tpo $(DEPDIR)/plasmamule_engine_feeder-plasmamule-engine-feeder.Po
plasmamule_engine_feeder-plasmamule-dbus.o: plasmamule-dbus.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasmamule_engine_feeder_CXXFLAGS) $(CXXFLAGS) -MT plasmamule_engine_feeder-plasmamule-dbus.o -MD -MP -MF $(DEPDIR)/plasmamule_engine_feeder-plasmamule-dbus.Tpo -c -o plasmamule_engine_feeder-plasmamule-dbus.o `test -f 'plasmamule-dbus.cpp' || echo '$(srcdir)/'`plasmamule-dbus.cpp
	$(am__mv) $(DEPDIR)/plasmamule_engine_feeder-plasmamule-dbus.Tpo $(DEPDIR)/plasmamule_engine_feeder-plasmamule-dbus.Po
plasmamule_engine_feeder-plasmamule-dbus.obj: plasmamule-dbus.cpp
	echo "Compiling $(<F)"
	$(CXX) $(DEFS) $(DEFAULT_INCLUDES) $(INCLUDES) $(AM_CPPFLAGS) $(CPPFLAGS) $(plasmamule_engine_feeder_CXXFLAGS) $(CXXFLAGS) -MT plasmamule_engine_feeder-plasmamule-dbus.obj -MD -MP -MF $(DEPDIR)/plasmamule_engine_feeder-plasmamule-dbus.Tpo -c -o plasmamule_engine_feeder-plasmamule-dbus.obj `if test -f 'plasmamule-dbus.cpp'; then $(CYGPATH_W) 'plasmamule-dbus.cpp'; else $(CYGPATH_W) '$(srcdir)/plasmamule-dbus.cpp'; fi`
	$(am__mv) $(DEPDIR)/plasmamule_engine_feeder-plasmamule-dbus.Tpo $(DEPDIR)/plasmamule_engine_feeder-plasmamule-dbus.Po
install-dist_appsDATA: $(dist_apps_DATA)
	@$(NORMAL_INSTALL)
	@list='$(dist_apps_DATA)'; test -n "$(appsdir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(appsdir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(appsdir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(appsdir)'">/dev/null; \
	echo "Installing $(appsdir)"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(appsdir)" || exit $$?; \
	done
uninstall-dist_appsDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(dist_apps_DATA)'; test -n "$(appsdir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(appsdir)'; $(am__uninstall_files_from_dir)
install-dist_iconDATA: $(dist_icon_DATA)
	@$(NORMAL_INSTALL)
	@list='$(dist_icon_DATA)'; test -n "$(icondir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(icondir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(icondir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(icondir)'">/dev/null; \
	echo "Installing $(icondir)"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(icondir)" || exit $$?; \
	done
uninstall-dist_iconDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(dist_icon_DATA)'; test -n "$(icondir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(icondir)'; $(am__uninstall_files_from_dir)
install-dist_mimeDATA: $(dist_mime_DATA)
	@$(NORMAL_INSTALL)
	@list='$(dist_mime_DATA)'; test -n "$(mimedir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(mimedir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(mimedir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(mimedir)'">/dev/null; \
	echo "Installing $(mimedir)"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(mimedir)" || exit $$?; \
	done
uninstall-dist_mimeDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(dist_mime_DATA)'; test -n "$(mimedir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(mimedir)'; $(am__uninstall_files_from_dir)
install-dist_serviceDATA: $(dist_service_DATA)
	@$(NORMAL_INSTALL)
	@list='$(dist_service_DATA)'; test -n "$(servicedir)" || list=; \
	if test -n "$$list"; then \
	  echo " $(MKDIR_P) '$(DESTDIR)$(servicedir)'"; \
	  $(MKDIR_P) "$(DESTDIR)$(servicedir)" || exit 1; \
	fi; \
	for p in $$list; do \
	  if test -f "$$p"; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; \
	done | $(am__base_list) | \
	while read files; do \
	  echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(servicedir)'">/dev/null; \
	echo "Installing $(servicedir)"; \
	  $(INSTALL_DATA) $$files "$(DESTDIR)$(servicedir)" || exit $$?; \
	done
uninstall-dist_serviceDATA:
	@$(NORMAL_UNINSTALL)
	@list='$(dist_service_DATA)'; test -n "$(servicedir)" || list=; \
	files=`for p in $$list; do echo $$p; done | sed -e 's|^.*/||'`; \
	dir='$(DESTDIR)$(servicedir)'; $(am__uninstall_files_from_dir)
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
check: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) check-am
all-am: Makefile $(PROGRAMS) $(DATA) $(HEADERS)
installdirs:
	for dir in "$(DESTDIR)$(bindir)" "$(DESTDIR)$(modulesdir)" "$(DESTDIR)$(appsdir)" "$(DESTDIR)$(icondir)" "$(DESTDIR)$(mimedir)" "$(DESTDIR)$(servicedir)"; do \
	  test -z "$$dir" || $(MKDIR_P) "$$dir"; \
	done
install: $(BUILT_SOURCES)
	$(MAKE) $(AM_MAKEFLAGS) install-am
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
	-test -z "$(BUILT_SOURCES)" || rm -f $(BUILT_SOURCES)
	-test -z "$(MAINTAINERCLEANFILES)" || rm -f $(MAINTAINERCLEANFILES)
clean: clean-am
clean-am: clean-binPROGRAMS clean-generic clean-modulesPROGRAMS \
	mostlyclean-am
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
install-data-am: install-dist_appsDATA install-dist_iconDATA \
	install-dist_mimeDATA install-dist_serviceDATA \
	install-modulesPROGRAMS
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
uninstall-am: uninstall-binPROGRAMS uninstall-dist_appsDATA \
	uninstall-dist_iconDATA uninstall-dist_mimeDATA \
	uninstall-dist_serviceDATA uninstall-modulesPROGRAMS
.MAKE: all check install install-am install-strip
.PHONY: CTAGS GTAGS TAGS all all-am check check-am clean \
	clean-binPROGRAMS clean-generic clean-modulesPROGRAMS \
	cscopelist-am ctags ctags-am distclean distclean-compile \
	distclean-generic distclean-tags distdir dvi dvi-am html \
	html-am info info-am install install-am install-binPROGRAMS \
	install-data install-data-am install-dist_appsDATA \
	install-dist_iconDATA install-dist_mimeDATA \
	install-dist_serviceDATA install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-info install-info-am install-man \
	install-modulesPROGRAMS install-pdf install-pdf-am install-ps \
	install-ps-am install-strip installcheck installcheck-am \
	installdirs maintainer-clean maintainer-clean-generic \
	mostlyclean mostlyclean-compile mostlyclean-generic pdf pdf-am \
	ps ps-am tags tags-am uninstall uninstall-am \
	uninstall-binPROGRAMS uninstall-dist_appsDATA \
	uninstall-dist_iconDATA uninstall-dist_mimeDATA \
	uninstall-dist_serviceDATA uninstall-modulesPROGRAMS
.PRECIOUS: Makefile
%.moc : %.h
	${QT_MOC} -o $@ $<
.NOEXPORT:
