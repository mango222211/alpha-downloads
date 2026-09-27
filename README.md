# Alpha AI downloads

[Download Alpha AI v4.1](https://mango222211.github.io/alpha-downloads/?v=4.1.0) · [Open Alpha on the web](https://alphaaiweb.com/)

macOS Apple Silicon / Intel and Windows installers. v4.1 migrates the official server address, adds relevant automatic search with an opt-out, and lets macOS enforce screen capture authorization rather than stopping only on stale preflight status.

Mac PKG and Windows Setup replace the existing installation and preserve app data. Copies in other folders are not automatically removed. Development builds are not production signed or notarized. Some Macs still require screen permission re-registration after replacing a development build; capture success on the affected environment remains unverified. Windows hardware capture remains to be checked.

85 server/native and 165 desktop/JavaScript checks passed. App installation and connection to the new server were verified on macOS. Prepared operator datasets are not newly trained model weights; full 8B training remains constrained by memory.

This public repository contains only the download page, installation guide and binary release files. Server development source, secrets, user data and model weights are not included. GitHub's automatic source archives contain only this public download page and guide.
