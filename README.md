# elpa-deploy
ELPA deployment library

This library provides `elpa-deploy`: a complement to the function
`package-upload-file` from `package-x.el`, which automatizes the
deployment of simple and multi-file packages.  This function
automatizes the upload of a library to an ELPA directory so that no
other action is needed.  Particularly useful for rapid ELPA deployment
aiding testing and releases.  The procedures automatically taken care
of consist of updating the version field of a package source using the
current time-stamp, generating its tar archive if multi-file, and
uploading the results to a specified ELPA directory, while deleting
any previous version of the same package already deployed.
