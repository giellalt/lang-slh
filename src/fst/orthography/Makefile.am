## Process this file with automake to produce Makefile.in
## Copyright: Sámediggi/Divvun/UiT
## Licence: GPL v3+

# build before test
SUBDIRS=. test

####### Source file defs: ########

# Set these to names of available orthographic rules in regex and
# xfscript formats
GT_ORTHOGRAPHIC_REGEX_SRCS=\
		spellrelax.regex    \
		spellrelax-mobile-keyboard.regex \
		spellrelax-tags.regex \
		split-composed-chars.regex \
		inituppercase.regex

#		inituppercase.regex 

GT_ORTHOGRAPHIC_XFSCRIPT_SRCS=\
		allcaps.xfscript      \
		downcase-derived_proper-strings.xfscript \
		spellrelax-with-tags.xfscript

# Add extra targets here:
GIELLA_ORTH_EXTRA_TARGETS=

###### BEGIN: local build rules below here: ######

######  END: local build rules above here.  ######

# General build rules included from here:
include $(top_srcdir)/../giella-core/am-shared/src-orthography-dir-include.am
include $(top_srcdir)/../giella-core/am-shared/devtest-include.am
