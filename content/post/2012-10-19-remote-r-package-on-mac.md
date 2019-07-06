---
title: remote r package on mac
date: '2012-10-19'
tags:
  - mac
  - R
slug: remote-r-package-on-mac
---


Install R Package on Mac through SSH 
==========

All on remote 

	ssh -Y username@address

# Download #

	curl -O packageaddress
	
# Install #

	R CMD INSTALL packagename lib
	R CMD INSTALL multicore_0.1-7.tgz ~/Documents/Rpackages/

