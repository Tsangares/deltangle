# Instructions

## Node.js

1.Install node

    curl -sL https://deb.nodesource.com/setup_9.x | sudo -E bash -
    sudo apt-get install -y nodejs

2.Install libs

    npm install -g iota.lib.js
    npm install -g diff
    npm install -g minimist

3.Set DELTANGLE_PATH

    echo export DELTANGLE_PATH=<deltangle path> >> ~/.profile
    echo 'export PATH="$DELTANGLE_PATH:$PATH" >> ~/.profile'
    source ~/.profile

4.Set execution permission

    chmod +x <deltangle path>/deltangle