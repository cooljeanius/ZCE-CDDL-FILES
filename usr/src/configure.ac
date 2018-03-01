dnl#                                               -*- Autoconf -*-
dnl# Process this file with autoconf to produce a configure script.

AC_PREREQ([2.61])
AC_INIT([ZCE-CDDL-FILES],[2012.09.14],[file:///dev/null])
AC_CONFIG_SRCDIR([cmd/stat/common/common.c])
AC_CONFIG_AUX_DIR([build-aux])
AC_CONFIG_LIBOBJ_DIR([lib/libgnu])
AC_CONFIG_MACRO_DIR([m4])
AC_CONFIG_HEADER([config.h])dnl

AM_INIT_AUTOMAKE([1.9 foreign])dnl

# Checks for programs.
AC_USE_SYSTEM_EXTENSIONS
AC_DEFUN([AC_REQUIRE_CC],[
  AC_REQUIRE([AC_PROG_CC])dnl
])dnl
AC_REQUIRE_CC

# Checks for libraries.

# Checks for header files.
AC_FUNC_ALLOCA
AC_HEADER_DIRENT
AC_HEADER_RESOLV
AC_DEFUN([AC_REQUIRE_HEADER_STDC],[
  AC_REQUIRE([AC_HEADER_STDC])dnl
])dnl
AC_REQUIRE_HEADER_STDC
AC_HEADER_MAJOR
AC_HEADER_SYS_WAIT
AC_CHECK_HEADERS([fcntl.h inttypes.h langinfo.h libintl.h limits.h locale.h \
                  malloc.h malloc/malloc.h memory.h netdb.h netinet/in.h \
                  nl_types.h stddef.h stdint.h stdio_ext.h stdlib.h string.h \
                  strings.h sys/acl.h sys/file.h sys/fstyp.h sys/ioctl.h \
                  sys/mntent.h sys/mount.h sys/param.h sys/socket.h \
                  sys/statfs.h sys/statvfs.h sys/systeminfo.h sys/time.h \
                  sys/vfs.h syslog.h unistd.h utmp.h utmpx.h values.h \
                  wchar.h wctype.h])dnl

# Checks for typedefs, structures, and compiler characteristics.
AC_CHECK_HEADER_STDBOOL
AC_C_CONST
AC_TYPE_UID_T
AC_C_INLINE
AC_TYPE_INT16_T
AC_TYPE_INT32_T
AC_TYPE_INT64_T
AC_TYPE_INT8_T
AC_TYPE_MODE_T
AC_TYPE_OFF_T
AC_TYPE_PID_T
AC_TYPE_SIZE_T
AC_TYPE_SSIZE_T
AC_CHECK_MEMBERS([struct stat.st_blksize])
AC_STRUCT_ST_BLOCKS
AC_CHECK_MEMBERS([struct stat.st_rdev])
AC_HEADER_TIME
AC_STRUCT_TM
AC_TYPE_UINT16_T
AC_TYPE_UINT32_T
AC_TYPE_UINT64_T
AC_TYPE_UINT8_T
AC_C_VOLATILE
AC_CHECK_TYPES([ptrdiff_t])dnl

# Checks for library functions.
AC_DEFUN([AC_LIBOBJ],[AC_MSG_NOTICE([skipping adding libobj for $1])])
AC_DEFUN([AC_REPLACE_FUNCS],[AC_CHECK_FUNCS])
AC_FUNC_CHOWN
AC_FUNC_CLOSEDIR_VOID
AM_GNU_GETTEXT([external])
AM_GNU_GETTEXT_VERSION([0.19.8])
AC_REPLACE_FNMATCH
AC_FUNC_FORK
AC_FUNC_FSEEKO
AC_FUNC_GETGROUPS
AC_FUNC_GETLOADAVG
AC_FUNC_GETMNTENT
AC_FUNC_GETPGRP
AC_PROG_GCC_TRADITIONAL
AC_FUNC_LSTAT
AC_FUNC_LSTAT_FOLLOWS_SLASHED_SYMLINK
AC_FUNC_MALLOC
AC_FUNC_MEMCMP
AC_FUNC_MMAP
AC_FUNC_REALLOC
AC_FUNC_SELECT_ARGTYPES
AC_FUNC_SETPGRP
AC_FUNC_SETVBUF_REVERSED
AC_TYPE_SIGNAL
AC_FUNC_STAT
AC_FUNC_STRERROR_R
AC_FUNC_STRFTIME
AC_FUNC_STRNLEN
AC_FUNC_STRTOD
AC_FUNC_UTIME_NULL
AC_FUNC_VPRINTF
AC_FUNC_WAIT3
AC_CHECK_FUNCS([__fpending acl alarm bzero clock_gettime dup2 endgrent \
                endpwent fchdir fdatasync ftime ftruncate getcwd getdelim \
                gethostbyaddr gethostbyname gethostname gethrtime getmntent \
                getpagesize getpass getspnam gettimeofday getusershell \
                hasmntopt isascii iswprint lchown localtime_r mblen memchr \
                memmove memset mkdir mkfifo munmap nl_langinfo pathconf pow \
                putenv re_comp realpath regcmp regcomp resolvepath rmdir \
                select setenv sethostname setlocale socket stime stpcpy \
                strcasecmp strchr strcspn strdup strerror strncasecmp \
                strndup strpbrk strrchr strspn strstr strtol strtoul \
                strtoull strtoumax sysinfo tzset uname utime utmpname \
                utmpxname wcwidth])dnl

# Output.
AC_SUBST([top_builddir])dnl
AC_CONFIG_FILES([Makefile po/Makefile.in po/Makevars])
AC_OUTPUT
