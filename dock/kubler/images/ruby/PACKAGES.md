### kubler/ruby:20180127

Built: Mon Jan 29 16:55:45 CET 2018
Image Size: 58.3MB

#### Installed
Package | USE Flags
--------|----------
app-eselect/eselect-ruby-20170723 | ``
dev-lang/ruby-2.4.3 | `berkdb rdoc ssl -debug -doc -examples -gdbm -ipv6 -jemalloc -libressl -rubytests -socks5 -static-libs -tk -xemacs`
dev-libs/gmp-6.1.2 | `asm cxx -doc -pgo -static-libs`
dev-libs/libffi-3.2.1 | `-debug -pax`
dev-libs/libyaml-0.1.7 | `-doc -examples -static-libs {-test}`
dev-ruby/did_you_mean-1.1.2 | `{-test}`
dev-ruby/json-2.1.0 | `-doc {-test}`
dev-ruby/minitest-5.10.3 | `-doc {-test}`
dev-ruby/net-telnet-0.1.1-r1 | `-doc {-test}`
dev-ruby/power_assert-0.4.1 | `-doc {-test}`
dev-ruby/rake-12.0.0 | `-doc {-test}`
dev-ruby/rdoc-5.1.0 | `-doc {-test}`
dev-ruby/rubygems-2.6.14 | `-server {-test}`
dev-ruby/test-unit-3.2.5 | `-doc {-test}`
dev-ruby/xmlrpc-0.2.1 | `-doc {-test}`
sys-libs/db-5.3.28-r2 | `cxx -doc -examples -java -tcl {-test}`
#### Inherited
Package | USE Flags
--------|----------
**FROM kubler/bash** |
app-admin/eselect-1.4.11 | `-doc -emacs -vim-syntax`
app-portage/portage-utils-0.64 | `nls -static`
app-shells/bash-4.4_p12 | `net nls (readline) -afs -bashlogger -examples -mem-scramble -plugins`
dev-libs/iniparser-3.1-r1 | `-doc -examples -static-libs`
net-misc/curl-7.58.0 | `ssl threads -adns -brotli -http2 -idn -ipv6 -kerberos -ldap -metalink -rtmp -samba -ssh -static-libs {-test}`
sys-apps/acl-2.2.52-r1 | `nls -static-libs`
sys-apps/attr-2.4.47-r2 | `nls -static-libs`
sys-apps/coreutils-8.28-r1 | `acl nls (xattr) -caps -gmp -hostname -kill -multicall (-selinux) -static {-test} -vanilla`
sys-apps/file-5.32 | `zlib -python -static-libs`
sys-apps/sed-4.2.2 | `acl nls (-selinux) -static`
sys-libs/ncurses-6.0-r1 | `cxx minimal threads unicode -ada -debug -doc -gpm (-profile) -static-libs {-test} -tinfo -trace`
sys-libs/readline-7.0_p3 | `-static-libs -utils`
**FROM kubler/openssl** |
app-misc/ca-certificates-20161130.3.30.2 | `-cacert -insecure`
app-misc/c_rehash-1.7-r1 | ``
dev-libs/openssl-1.0.2n | `asm sslv3 tls-heartbeat zlib -bindist -gmp -kerberos -rfc3779 -sctp -sslv2 -static-libs {-test} -vanilla`
sys-apps/debianutils-4.8.3 | `-static`
sys-libs/zlib-1.2.11-r1 | `-minizip -static-libs`
**FROM kubler/s6** |
dev-lang/execline-2.3.0.4 | `-static -static-libs`
dev-libs/skalibs-2.6.3.0 | `-doc -ipv6 -static-libs`
sys-apps/s6-2.7.0.0 | `-static -static-libs`
*manual install*: entr-3.9 | http://entrproject.org/
**FROM kubler/glibc** |
sys-apps/gentoo-functions-0.12 | ``
sys-libs/glibc-2.25-r9 | `hardened rpc -audit -caps -debug -gd -headers-only (-multilib) -nscd (-profile) (-selinux) -suid -systemtap (-vanilla)`
sys-libs/timezone-data-2017c | `nls -leaps`
**FROM kubler/busybox** |
sys-apps/busybox-1.28.0 | `make-symlinks static -debug -ipv6 -livecd -math -mdev -pam -savedconfig (-selinux) -sep-usr -syslog -systemd`
#### Purged
- [x] Headers
- [x] Static Libs
