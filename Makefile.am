# Copyright 2019-2022 OARC, Inc.
# Copyright 2017-2018 Akamai Technologies
# Copyright 2006-2016 Nominum, Inc.
# All rights reserved.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
# You may obtain a copy of the License at
#
#     http://www.apache.org/licenses/LICENSE-2.0
#
# Unless required by applicable law or agreed to in writing, software
# distributed under the License is distributed on an "AS IS" BASIS,
# WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
# See the License for the specific language governing permissions and
# limitations under the License.

ACLOCAL_AMFLAGS = -I m4

MAINTAINERCLEANFILES = $(srcdir)/Makefile.in \
  $(srcdir)/src/config.h.in~ \
  $(srcdir)/configure

SUBDIRS = src

dist_doc_DATA = CHANGES README.md LICENSE

EXTRA_DIST = m4 contrib

test: check
