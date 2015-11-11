# cleanup-dot-ensime

Remove bad jar files from .ensime files generated by gen-ensime.

Run this script after gen-ensime, for example:

    sbt gen-ensime
    mv .ensime .ensime.original
    cleanup-dot-ensime .ensime.original > .ensime

References:
 * https://github.com/ensime/ensime-server/issues/825
