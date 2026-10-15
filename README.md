<!-- ffxiv-tc-port 繁體中文說明開始 -->
# OtterGuiInternal(台服 fork)

OtterGui 用來呼叫 Dear ImGui 內部 API（`imgui_internal` 那一層）的低階包裝與結構定義（上游 [Ottermandias/OtterGuiInternal](https://github.com/Ottermandias/OtterGuiInternal)）。

## 台服 fork 的目的

- 讓 OtterGui 的子模組網址指向本 org，建置不依賴上游 repo 是否還在、有沒有被改寫。上游 repo 現在是空的，本 repo 保留了原本的內容。

## 與上游的差異

- 沒有我方的 commit，分支內容與上游清空前相同。
- OtterGui 釘的是較早的版本，分支頂端多出的兩顆上游 commit 沒有採用。

## 誰在用它

- [OtterGui](https://github.com/ffxiv-tc-port/OtterGui)：子模組 `OtterGuiInternal`。
- 經由 OtterGui 間接使用：[Artisan](https://github.com/ffxiv-tc-port/Artisan)、[AutoRetainer](https://github.com/ffxiv-tc-port/AutoRetainer)、[GatherBuddyReborn](https://github.com/ffxiv-tc-port/GatherBuddyReborn)、[InventoryTools](https://github.com/ffxiv-tc-port/InventoryTools)、[Lifestream](https://github.com/ffxiv-tc-port/Lifestream)。

<!-- ffxiv-tc-port 繁體中文說明結束 -->
