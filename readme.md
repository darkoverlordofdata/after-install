# clouds, man...


Post Install
===================================================

    mkdir ~/Desktop
    mkdir ~/Documents/GitHub

    sudo apt update 
    sudo apt upgrade 
    sudo apt dist-upgrade 
    sudo apt install ubuntu-restricted-extras 
    sudo apt install libavcodec-extra 
    sudo apt install libdvd-pkg  

        libdvd-pkg: `apt-get check` failed, you may have broken packages. Aborting..
        sudo dpkg-reconfigure libdvd-pkg 

    sudo apt install software-properties-common 
    sudo add-apt-repository ppa:philip.scott/elementary-tweaks 
    sudo apt update 
    sudo apt install elementary-tweaks 
    sudo apt-add-repository ppa:jconti/recent-notifications
    sudo apt update 
    sudo apt install recent-notifications
    
    sudo apt install git 
    wget -qO - https://download.sublimetext.com/sublimehq-pub.gpg | sudo apt-key add - 
    sudo apt-get install apt-transport-https 
    echo "deb https://download.sublimetext.com/ apt/stable/" | sudo tee /etc/apt/sources.list.d/sublime-text.list 
    sudo apt update 
    sudo apt install sublime-text 
    sudo apt install python3-pip 
    sudo apt install ninja-build 
    pip3 install –user meson 
    sudo apt install clang 
    sudo apt install valac
    cd ./Downloads
    wget https://swift.org/builds/swift-5.0.1-release/ubuntu1804/swift-5.0.1-RELEASE/swift-5.0.1-RELEASE-ubuntu18.04.tar.gz
    tar xzf swift-5.0.1-RELEASE-ubuntu18.04.tar.gz
    sudo mv swift-5.0.1-RELEASE-ubuntu18.04 /usr/share/swift
    sudo apt install libgtk-3-dev libgranite-dev libjson-glib-dev libappindicator3-dev libsoup2.4-dev libnotify-dev -y



Edit .bashrc
===================================================

    export PATH=$PATH:/home/darko/.local/bin
    export PATH=$PATH:/usr/share/swift/usr/bin
    source  ~/.bashrc

Install from Appcenter
===================================================

    Eddy 
    Desktop folder 
    AppEditor  

Install using Eddy
===================================================

    wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
    https://www.gitkraken.com/download
    https://code.visualstudio.com/download

Install VSCode extensions
===================================================

    Microsoft/vscode-cpptools
    vector-of-bool/vscode-cmake-tools
    twxs/vs.language.cmake
    thiagoabreu/vala-code
    vadimcn/vscode-lldb
    asabil/vscode-meson
    kasik96/Swift-VS-Code

Install SublimeText packages
===================================================

    https://packagecontrol.io/installation


My cloud apps
===================================================

    cd Documents/GitHub
    git clone https://github.com/darkoverlordofdata/after-install.git
    merge ~/Documents/GitHub/after-install/.config into ~/.config
    copy links to the *.desktop files to ~/.local/applications, to put them on the menu.

Wallpaper
===================================================

    sudo apt-add-repository ppa:darkoverlordofdata/badabing
    sudo apt update 
    sudo apt install com.github.darkoverlordofdata.badabing

    
