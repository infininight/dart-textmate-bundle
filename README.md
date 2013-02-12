# Dart bundle for TextMate

This bundle provides basic Dart support for Textmate. At this point the bundle
provides:

* Syntax highlighting.
* Preferences for comments so that you can use CMD-/ to (de)comment source
  lines.
* Some snippets for inserting common Dart code.

The bundle identifies dart source by the file extension (.dart).

INSTALLATION
============

From the command line. From the root of this repository, type:
`open Dart.tmbundle`.

-OR-

From inside TextMate:
Open (File->Open...) the Dart.tmbundle file

Looking for an IDE experience? Try [Dart Editor][1],
[Dart plugin for Eclipse][2], or [Dart plugin for IntelliJ/WebStorm][3].

DEVELOPMENT
===========

Please ensure that all .tmPreferences, .tmLanguage, .tmSnippets, etc. files stay
in sync with the related [Dart Sublime repository][4].

License:

    Copyright 2012, the Dart project authors. All rights reserved.
    Redistribution and use in source and binary forms, with or without
    modification, are permitted provided that the following conditions are
    met:
        * Redistributions of source code must retain the above copyright
          notice, this list of conditions and the following disclaimer.
        * Redistributions in binary form must reproduce the above
          copyright notice, this list of conditions and the following
          disclaimer in the documentation and/or other materials provided
          with the distribution.
        * Neither the name of Google Inc. nor the names of its
          contributors may be used to endorse or promote products derived
          from this software without specific prior written permission.
    THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
    "AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
    LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR
    A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT
    OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL,
    SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT
    LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE,
    DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER CAUSED AND ON ANY
    THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT
    (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE
    OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.

[1]: http://www.dartlang.org/editor
[2]: http://news.dartlang.org/2012/08/dart-plugin-for-eclipse-is-ready-for.html
[3]: http://plugins.intellij.net/plugin/?id=6351
[4]: http://github.com/dart-lang/dart-sublime-bundle
