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
subdir = src/utils/xas/docs
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
am__v_P_1 = :
am__v_GEN_1 = 
am__v_at_1 = 
SOURCES =
DIST_SOURCES =
am__can_run_installinfo = \
  case $$AM_UPDATE_INFO_DIR in \
    n|no|NO) false;; \
    *) (install-info --version) >/dev/null 2>&1;; \
  esac
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
man1dir = $(mandir)/man1
am__installdirs = "$(DESTDIR)$(man1dir)"
NROFF = nroff
MANS = $(dist_man_MANS)
am__tagged_files = $(HEADERS) $(SOURCES) $(TAGS_FILES) $(LISP)
am__DIST_COMMON = $(dist_man_MANS) $(srcdir)/Makefile.in \
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
abs_builddir = /home/pablo/aMule-2.3.3/src/utils/xas/docs
abs_srcdir = /home/pablo/aMule-2.3.3/src/utils/xas/docs
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
dist_man_MANS = xas.1
man_langs = de es fr hu it ro ru tr zh_TW
EXTRA_DIST = xas.de.1 xas.es.1 xas.fr.1 xas.hu.1 xas.it.1 xas.ro.1 xas.ru.1 xas.tr.1 xas.zh_TW.1
MAINTAINERCLEANFILES = Makefile.in
all: all-am
.SUFFIXES:
$(srcdir)/Makefile.in: # $(srcdir)/Makefile.am  $(am__configure_deps)
	@for dep in $?; do \
	  case '$(am__configure_deps)' in \
	    *$$dep*) \
	      ( cd $(top_builddir) && $(MAKE) $(AM_MAKEFLAGS) am--refresh ) \
	        && { if test -f $@; then exit 0; else break; fi; }; \
	      exit 1;; \
	  esac; \
	done; \
	echo ' cd $(top_srcdir) && $(AUTOMAKE) --foreign src/utils/xas/docs/Makefile'>/dev/null; \
	$(am__cd) $(top_srcdir) && \
	  $(AUTOMAKE) --foreign src/utils/xas/docs/Makefile
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
install-man1: $(dist_man_MANS)
	@$(NORMAL_INSTALL)
	@list1=''; \
	list2='$(dist_man_MANS)'; \
	test -n "$(man1dir)" \
	  && test -n "`echo $$list1$$list2`" \
	  || exit 0; \
	echo " $(MKDIR_P) '$(DESTDIR)$(man1dir)'"; \
	$(MKDIR_P) "$(DESTDIR)$(man1dir)" || exit 1; \
	{ for i in $$list1; do echo "$$i"; done;  \
	if test -n "$$list2"; then \
	  for i in $$list2; do echo "$$i"; done \
	    | sed -n '/\.1[a-z]*$$/p'; \
	fi; \
	} | while read p; do \
	  if test -f $$p; then d=; else d="$(srcdir)/"; fi; \
	  echo "$$d$$p"; echo "$$p"; \
	done | \
	sed -e 'n;s,.*/,,;p;h;s,.*\.,,;s,^[^1][0-9a-z]*$$,1,;x' \
	      -e 's,\.[0-9a-z]*$$,,;$(transform);G;s,\n,.,' | \
	sed 'N;N;s,\n, ,g' | { \
	list=; while read file base inst; do \
	  if test "$$base" = "$$inst"; then list="$$list $$file"; else \
	    echo " $(INSTALL_DATA) '$$file' '$(DESTDIR)$(man1dir)/$$inst'">/dev/null; \
	echo "Installing $(man1dir)/$$inst"; \
	    $(INSTALL_DATA) "$$file" "$(DESTDIR)$(man1dir)/$$inst" || exit $$?; \
	  fi; \
	done; \
	for i in $$list; do echo "$$i"; done | $(am__base_list) | \
	while read files; do \
	  test -z "$$files" || { \
	    echo " $(INSTALL_DATA) $$files '$(DESTDIR)$(man1dir)'">/dev/null; \
	echo "Installing $(man1dir)"; \
	    $(INSTALL_DATA) $$files "$(DESTDIR)$(man1dir)" || exit $$?; }; \
	done; }
uninstall-man1:
	@$(NORMAL_UNINSTALL)
	@list=''; test -n "$(man1dir)" || exit 0; \
	files=`{ for i in $$list; do echo "$$i"; done; \
	l2='$(dist_man_MANS)'; for i in $$l2; do echo "$$i"; done | \
	  sed -n '/\.1[a-z]*$$/p'; \
	} | sed -e 's,.*/,,;h;s,.*\.,,;s,^[^1][0-9a-z]*$$,1,;x' \
	      -e 's,\.[0-9a-z]*$$,,;$(transform);G;s,\n,.,'`; \
	dir='$(DESTDIR)$(man1dir)'; $(am__uninstall_files_from_dir)
tags TAGS:
ctags CTAGS:
cscope cscopelist:
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
all-am: Makefile $(MANS)
installdirs:
	for dir in "$(DESTDIR)$(man1dir)"; do \
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
distclean-generic:
	-test -z "$(CONFIG_CLEAN_FILES)" || rm -f $(CONFIG_CLEAN_FILES)
	-test . = "$(srcdir)" || test -z "$(CONFIG_CLEAN_VPATH_FILES)" || rm -f $(CONFIG_CLEAN_VPATH_FILES)
maintainer-clean-generic:
	@echo "This command is intended for maintainers to use"
	@echo "it deletes files that may require special tools to rebuild."
	-test -z "$(MAINTAINERCLEANFILES)" || rm -f $(MAINTAINERCLEANFILES)
clean: clean-am
clean-am: clean-generic mostlyclean-am
distclean: distclean-am
	-rm -f Makefile
distclean-am: clean-am distclean-generic
dvi: dvi-am
dvi-am:
html: html-am
html-am:
info: info-am
info-am:
install-data-am: install-man
	@$(NORMAL_INSTALL)
	$(MAKE) $(AM_MAKEFLAGS) install-data-hook
install-dvi: install-dvi-am
install-dvi-am:
install-exec-am:
install-html: install-html-am
install-html-am:
install-info: install-info-am
install-info-am:
install-man: install-man1
install-pdf: install-pdf-am
install-pdf-am:
install-ps: install-ps-am
install-ps-am:
installcheck-am:
maintainer-clean: maintainer-clean-am
	-rm -f Makefile
maintainer-clean-am: distclean-am maintainer-clean-generic
mostlyclean: mostlyclean-am
mostlyclean-am: mostlyclean-generic
pdf: pdf-am
pdf-am:
ps: ps-am
ps-am:
uninstall-am: uninstall-man
	@$(NORMAL_INSTALL)
	$(MAKE) $(AM_MAKEFLAGS) uninstall-hook
uninstall-man: uninstall-man1
.MAKE: install-am install-data-am install-strip uninstall-am
.PHONY: all all-am check check-am clean clean-generic cscopelist-am \
	ctags-am distclean distclean-generic distdir dvi dvi-am html \
	html-am info info-am install install-am install-data \
	install-data-am install-data-hook install-dvi install-dvi-am \
	install-exec install-exec-am install-html install-html-am \
	install-info install-info-am install-man install-man1 \
	install-pdf install-pdf-am install-ps install-ps-am \
	install-strip installcheck installcheck-am installdirs \
	maintainer-clean maintainer-clean-generic mostlyclean \
	mostlyclean-generic pdf pdf-am ps ps-am tags-am uninstall \
	uninstall-am uninstall-hook uninstall-man uninstall-man1
.PRECIOUS: Makefile
install-data-hook:
	@for lang in $(man_langs); do \
		echo " $(mkinstalldirs) $(DESTDIR)$(mandir)/$$lang/man1" >/dev/null; \
		$(mkinstalldirs) $(DESTDIR)$(mandir)/$$lang/man1 >/dev/null; \
		list='$(dist_man_MANS)' ; \
		for file in $$list; do \
			tmp=`echo $$file | sed -e "s/\.1/\.$$lang\.1/"` ; \
			if test -f $(srcdir)/$$tmp; then name=$(srcdir)/$$tmp; \
			else name=$$tmp; fi; \
			inst=`echo $$file | sed -e "s/\.1//" -e '$(transform)'`.1 ; \
			echo " $(INSTALL_DATA) $$name $(DESTDIR)$(mandir)/$$lang/man1/$$inst" >/dev/null; \
	echo "Installing $(mandir)/$$lang/man1/$$inst"; \
			$(INSTALL_DATA) $$name $(DESTDIR)$(mandir)/$$lang/man1/$$inst ; \
		done ; \
	done
uninstall-hook:
	@for lang in $(man_langs); do \
		list='$(dist_man_MANS)' ; \
		for file in $$list; do \
			inst=`echo $$file | sed -e "s/\.1//" -e '$(transform)'`.1 ; \
			echo " rm -f $(DESTDIR)$(mandir)/$$lang/man1/$$inst" >/dev/null; \
	echo "Uninstalling $(mandir)/$$lang/man1/$$inst"; \
			rm -f $(DESTDIR)$(mandir)/$$lang/man1/$$inst ; \
		done ; \
	done
.NOEXPORT:
