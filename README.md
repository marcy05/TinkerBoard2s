# manifest

1. Please refer to the following URL to install Docker Engine on Ubuntu.

    https://docs.docker.com/engine/install/ubuntu/

2. Please refer to the following URL to install Repo. 

    https://source.android.com/setup/develop#installing-repo

3. (Optional) Please refer to the following URL to understand how to download the AOSP soure.

    https://source.android.com/setup/build/downloading

4. Then, you can issue the following commands to donwload the Android source for Tinker Board 2/2S.

    $ repo init -u https://github.com/marcy05/TinkerBoard2s.git -b android14-rk3399 -m tinker_board_2-android14-0.0.1.xml
    $ repo sync
