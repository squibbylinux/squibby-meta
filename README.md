squibby-meta source package
===========================

This package is responsible for generating the main squibby metapackages,
using information from the seeds (with the help of "germinate").

Run the "update" script to automatically generate new dependency
lists.  The result will be based on the published seed lists, filtered
by:

- The Packages files (nonexistent packages will be skipped)

- debootstrap (packages not yet added to debootstrap will not be added
  to ubuntu-base)
