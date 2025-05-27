
# proot Build 
[✓] Simple Build

# How to Use 
````
git clone https://github.com/SahrulGunawan-ID/proot.git
````
# Enter
````
cd proot
````
# Make Build I Give You 4 Options
# This is option 1
````
make -j$(nproc)
````
# This is option 2
````
make -j4 LDFLAGS="-static"
````
# This is option 3
````
make -j4 LDFLAGS="-static -Wl,-Bstatic -ltalloc -Wl,-Bdynamic"
````

# Build For Android / Termux ? You Can Download Libc.a Here Free SdkTools / NDK ToolsChain
# Via Clone Git
git clone https://github.com/SahrulGunawan-ID/Toolchain-Termux

# Direct Download For 32BIT
https://raw.githubusercontent.com/SahrulGunawan-ID/Toolchain-Termux/refs/heads/superuser/Archives/arm-linux-androideabi.tar.xz

# Direct Download For 64BIT
https://raw.githubusercontent.com/SahrulGunawan-ID/Toolchain-Termux/refs/heads/superuser/Archives/aarch64-linux-android.tar.xz

# GOOGLE HOSTED CLOUD
https://dl.google.com/android/repository/android-ndk-r28b-linux.zip

# GitHub Release
https://github.com/SahrulGunawan-ID/Toolchain-Termux/releases/tag/Toolchain

