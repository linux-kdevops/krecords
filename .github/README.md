<!-- SPDX-License-Identifier: copyleft-next-0.3.1 -->
<!-- validate refuses a file at the top of the tree that is no record. -->

# krecords

The records of what tools reported on patch series for the Linux kernel
and QEMU, in the format of [kresults]. Each push to `main` is checked
with kresults' `validate`, rendered with its `krender`, and published at
<https://linux-kdevops.github.io/krecords/>.

[kresults' format] says where each record lies and what it holds.

[kresults]: https://github.com/linux-kdevops/kresults
[kresults' format]: https://github.com/linux-kdevops/kresults/blob/main/format/README.md
