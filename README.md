# Visual Studio Code: Insiders edition

This tree hosts a Flatpak for the [Insiders edition](https://code.visualstudio.com/insiders/) of [Visual Studio Code](https://code.visualstudio.com/).

Insiders is a beta stream of Code, built from a development branch. Insiders is a rapidly-changing edition of VS Code which offers fixes not yet available in stable releases, as well as providing early access to features which are not yet enabled in stable builds.

You should use this edition if you need this early access, and you are prepared to deal with bugs and issues associated with development versions. If you prefer a stable build, please use the [stable Visual Studio Code](https://flathub.org/apps/details/com.visualstudio.code) Flatpak also available on Flathub.

Please report any issues with this Flatpak itself against this repository; however, bug reports against VS Code itself should be filed on the [VS Code upstream repository](http://github.com/microsoft/vscode).

## Installing Insiders

If you already have the Flathub beta remote installed, you can run `flatpak install flathub-beta com.visualstudio.code.insiders`.

If you do not yet have the remote enabled, you can add it with `flatpak remote-add flathub-beta https://flathub.org/beta-repo/flathub-beta.flatpakrepo`.

The Insiders edition Flatpak co-exists with the regular Code install, so you can have both installed. They are named differently so you can select which one to start, and are also differentiated by icon; the regular edition has a blue icon, and the Insiders edition has a green icon.
