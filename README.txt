Industry House website with stronger music timestamp carryover.

This version uses localStorage and also passes the current audio timestamp through internal page links using ?music=1&t=SECONDS.
That makes the next page restore the song from the same spot much more reliably.

Important: it still cannot be perfectly seamless because each HTML page reloads. But it should no longer restart from the beginning when moving between pages.
