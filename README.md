# go-license: gotpl templates for software licenses

# EXAMPLE

```console
$ echo -e "Year: 2017\nCopyrightHolder: \"Andrew Pennebaker\"" | gotpl data/freebsd-license.gotpl
Copyright (c) 2017, Andrew Pennebaker
All rights reserved.

Redistribution and use in source and binary forms, with or witout
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright, this
   list of conditions and the following disclaimer.
2. Redistributions in binary form must reproduce the above copyright notice,
   this list of conditions and the following disclaimer in the documentation
   and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS" AND
ANY EXPRESS OR IMPLIED WARRENTIES, INCLUDING, BUT NOT LIMITED TO, THE IMPLIED
WARRANTIES OR MERCHANTIBILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR
ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES
(INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND
ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
(INCLUDING NEGLICENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THIS
SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

The views and conclusions contained in the software and documentation are those
of the autors and should not be interpreted as representing official policies,
either expressed or implied, of the FreeBSD project.
```

# REQUIREMENTS

* [gotpl](https://github.com/tsg/gotpl) (e.g. `go get github.com/tsg/gotpl`)
