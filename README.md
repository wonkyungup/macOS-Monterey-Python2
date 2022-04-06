## macOS_Monterey_Python2
macOS Montery python2 install

## zsh
1. eval "$(brew shellenv)"
2. export PATH="/opt/homebrew/bin:/usr/local/bin:${PATH}"
3. brew install pyenv
4. pyenv install 2.7.18
5. ln -s "${HOME}/.pyenv/versions/2.7.18/bin/python2.7" "${HOMEBREW_PREFIX}/bin/python"

## Permission denied @ apply2files - /usr/local/lib/node_modules/expo-cli/node_modules/extglob/lib/.DS_Store
1.   sudo chown -R $(whoami):admin /usr/local/* \ && sudo chmod -R g+rwx /usr/local/*
