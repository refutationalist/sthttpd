# EXPERIMENTAL VERSION, UNUSED

This version of sthttpd has support for handing files ending with &asp;&asp;.php to a PHP interpreter, as well as extra junk said CGI interpreter requires.   Not well tested, was using on retrocomputing projects.   I have mostly moved on to other web servers.

# Original README


      sthttpd - a fork of thttpd, a tiny/turbo/throttling HTTP server
                    version 2.27.0 Oct 3, 2014

sthttpd is a fork of Jef Poskanzer's popular thttpd server.  This fork aims to simply maintain the original codebase as bugs or security issues are found.

Please read README.thttpd for more information.

Credits:

* The original codebase is by * Jef Poskanzer <jef@mail.acme.com>  http://www.acme.com/jef/ Please send all kudos to him.

* The fork is by Anthony G. Basile <blueness@gentoo.org> https://github.com/blueness/sthttpd Send all blame to him.

* thttpd is released under a BSD license.  Any extended code added by sthttpd is also released under the same license.  Here's a copy of it from the src/thttpd.c file:


 Copyright � 1995,1998,1999,2000,2001 by Jef Poskanzer <jef@mail.acme.com>.
 All rights reserved.

 Redistribution and use in source and binary forms, with or without
 modification, are permitted provided that the following conditions
 are met:
 1. Redistributions of source code must retain the above copyright
    notice, this list of conditions and the following disclaimer.
 2. Redistributions in binary form must reproduce the above copyright
    notice, this list of conditions and the following disclaimer in the
    documentation and/or other materials provided with the distribution.

 THIS SOFTWARE IS PROVIDED BY THE AUTHOR AND CONTRIBUTORS ``AS IS'' AND
 ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
 IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
 ARE DISCLAIMED.  IN NO EVENT SHALL THE AUTHOR OR CONTRIBUTORS BE LIABLE
 FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL
 DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS
 OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION)
 HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
 LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY
 OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF
 SUCH DAMAGE.

## Build status
[![Build Status](https://travis-ci.org/blueness/sthttpd.svg?branch=master)](https://travis-ci.org/blueness/sthttpd)

