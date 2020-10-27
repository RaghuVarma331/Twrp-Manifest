## Getting Started ##
---------------


    mkdir twrp
    cd twrp
    echo -ne '\n' | repo init -u git://github.com/RaghuVarma331/Twrp-Manifest.git -b android-10.0 --depth=1
    repo sync -c -j$(nproc --all) --force-sync --no-clone-bundle --no-tags
