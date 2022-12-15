TexLive Tables Problem
**********************

Got all my tables mangled when upgraded from TexLive 2018 to TexLive 2021.
Tried to reproduce the cause without success. Right now installed
TexLive 2021 alongside 2018 into ``/usr/local/texlive``
without touching ``/usr/local/texlive/texmf-local``
directory. Looks like the probable cause: last time I removed ``texmf-local``
before installing TexLive 2021, so far as I remember.

This MWE is preserved in case the problem should surface again.
