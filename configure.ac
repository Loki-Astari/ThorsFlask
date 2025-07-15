AC_INIT([ThorsFlask], [0.1], [Loki.Astari+ThorsFlask@gmail.com])
AC_PREREQ([2.65])

AC_CONFIG_MACRO_DIR([build/autotools/m4])
AC_CONFIG_AUX_DIR([build/autotools/build])

AX_THOR_FUNC_INIT_BUILD([ThorsFlask], [src/ThorsFlask/ThorsFlask.cpp])


#
# Add extra configuration here
#
AX_THOR_CHECK_USE_THORS_SERIALIZE_HEADER_ONLY
AX_THOR_CHECK_USE_THORS_SERIALIZE


LT_INIT

AX_THOR_FEATURE_HEADER_ONLY_VARIANT([THORSFLASK])
AX_THOR_FUNC_TERM_BUILD([THORSFLASK], [src/ThorsFlask/ThorsFlaskConfig.h:config.h.in])

AC_OUTPUT
