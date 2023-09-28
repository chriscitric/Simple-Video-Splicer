Some Notes of what i have setup so far:

    Instructions i used to do this build was in https://tauri.app/v1/guides/

    Needed to install the C++ Visual Studio Build Tools to install and initialize Tauri

    Evergreen Bootstrapper for the Tauri Prereq of Webview2
    (Do note that you might already have it installed but in case you don't the link is below)
    https://developer.microsoft.com/en-us/microsoft-edge/webview2/#download-section

    Rust
    This needs to be constantly updated so up until final build assume that the version i am using will
    always be the latest version (I will update this notes to include latest version when I get the chance)

    Be sure to execute "rustup default stable-msvc" once you have Tauri installed for full support
    Which sets the toolchain is set in your workspace to the MSVC Rust Toolchain.

    Also needed to install tauri-cli and create-tauri-app