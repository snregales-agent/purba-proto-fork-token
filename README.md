# purba-proto-fork-token

Throwaway. Arm A of the prototype for
[purba #80](https://github.com/kalonji-tools/purba/issues/80).

**One question:** on a pull request from a fork opened by an account with no
write access, is `GITHUB_TOKEN` writable?

`signoff.yml` in purba asserts it is read-only and that assertion was read from
documentation rather than measured. It is load-bearing: it is why the design
deletes the job that would append a trailer after approval.

Delete this repository once the result is recorded on the issue.
