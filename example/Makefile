
all: gitlab redmine joomla nginx

gitlab:
	cd gitlab && /usr/share/qdk2/QDK/bin/qbuild --build-dir build

redmine:
	cd redmine && fakeroot /usr/share/qdk2/QDK/bin/qbuild --build-dir build

joomla:
	cd joomla && fakeroot /usr/share/qdk2/QDK/bin/qbuild --build-dir build

nginx:
	cd nginx && fakeroot /usr/share/qdk2/QDK/bin/qbuild --build-dir build

clean:
	sudo rm -f */build/*.qpkg

.PHONY: all clean gitlab redmine joomla nginx
