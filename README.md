How to release
==============

* tag a commit with a tag name of "release-x.y.z" and push the tag
* travis goes to town
* bump the snapshot version (mvn versions:set -DnewVersion=1.0.0-SNAPSHOT)

inspired by https://axelfontaine.com/blog/final-nail.html
