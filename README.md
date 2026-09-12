# SUMMIT MC resource pack hosting

Hosts `summit-pack.zip` (the patch-pack.ps1 output) for the server's
`resource-pack=` URL. Each pack cycle: copy the new zip here, commit, push,
then point server.properties at the commit-pinned raw URL printed by
`tools/push-pack.ps1` in the main repo.
