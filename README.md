# macOS_Monterey_Python2
macOS Montery python2 install


> eval "$(brew shellenv)"
> export PATH="/opt/homebrew/bin:/usr/local/bin:${PATH}"
> brew install pyenv
> pyenv install 2.7.18
> ln -s "${HOME}/.pyenv/versions/2.7.18/bin/python2.7" "${HOMEBREW_PREFIX}/bin/python"

if (Permission denied @ apply2files - /usr/local/lib/node_modules/expo-cli/node_modules/extglob/lib/.DS_Store) {
  sudo chown -R $(whoami):admin /usr/local/* \
&& sudo chmod -R g+rwx /usr/local/*
}
