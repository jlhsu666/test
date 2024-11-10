https://miro.medium.com/v2/resize:fit:640/format:webp/0*TxjLuaHht6HgPlNQ.png

Git Flow 主要分成五條支線，以下分別說明每條支線的功能：

master
主要是放穩定可立即上線的版本，因此不會在這條支線上做直接的 commit 都是由其他分支合併過來。

Develop
是所有開發基礎的分支。

Hotfix
緊急修正穩定版本的支線，因此修正完後會合併到 master，同時也會合併到 Develop，避免開發版上線時問題又出現。

Release
為上線前測試的分支，測試完後會合併到 master 及 develop。

Feature
開發新功能的分支，為 Develop 切分出來的支線，待開發完畢就會合併回 Develop。
