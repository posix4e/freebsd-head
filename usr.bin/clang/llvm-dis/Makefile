# $FreeBSD$

PROG_CXX=llvm-dis

SRCDIR=	tools/llvm-dis
SRCS=	llvm-dis.cpp
LLVM_REQUIRES_EH=

TGHDRS=	Intrinsics
LIBDEPS=llvmanalysis \
	llvmtarget \
	llvmmc \
	llvmobject \
	llvmbitreader \
	llvmcore \
	llvmsupport

.include "../clang.prog.mk"
