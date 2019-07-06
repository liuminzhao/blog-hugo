---
title: Emacs GDB Debug Fortran
date: '2012-06-25'
tags:
  - emacs
  - gdb
  - fortran
slug: emacs-gdb-debug-fortran
---


Emacs Debug Fortran Using GDB
==========

<http://vimeo.com/8109291>
	
	M-x compile
	gfortran -g foo.f 
	b main
	r # run debugger
	s
	RET
	print Sum
	

# Debug R ESS Emacs #

	C-u M-x R <RET> -d gdb
	M-x R , then M-x gdb
	
# Debug compiled code #

	$ R -d gdb --vanilla
	...
	gdb> run

# Emacs and GDB #

<http://csm.mech.utah.edu/content/2011/03/01/208/>

	break fsdfa.cc:557
	continue
	print fsskjfla
