NAME = postproc
DESC = FFmpeg postprocessing library
FFLIBS = avutil

HEADERS = postprocess.h        \
          version.h            \
          version_major.h      \

OBJS = postprocess.o           \
       version.o               \

# Windows resource file
SHLIBOBJS-$(HAVE_GNU_WINDRES) += postprocres.o

TESTPROGS = blocktest          \
            stripetest         \
            temptest	       \
