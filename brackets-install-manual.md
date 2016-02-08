equo install mc

equo install deb2targz
download https://github.com/gbevan/portage-brackets-bin-overlay
equo install git
layman -f -a gbevan-brackets
emerge -v --ask brackets-bin
ebuild brackets-bin-1.6.ebuild merge

ssh-keygen -t rsa -C "greenrobotmail@gmail.com"

To enable Live Preview:
ln -s /opt/google/chrome/google-chrome /bin/google-chrome

equo install nodejs
npm install -g gulp

in current project folder (public_html):
npm install semantic-ui --save
cd semantic/
gulp build

