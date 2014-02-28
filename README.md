Learning Log Debian
===========

A debian package build for learning log.

Build your learning log source into this directory using the maven.tomcat.home
directive. Modify the debian/control file so you don't depend on the 'sakai'
package, modify the debian/install file so your learning log artefacts go into the
right place, update debian/changelog to reflect the new version, then run:

debuild --no-lintian -us -uc

learning log's .deb file will be be built into the directory above this one.
