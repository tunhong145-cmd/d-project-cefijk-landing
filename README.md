# D 項目落地頁：C、E、F、I、J、K

從 `tunhong145-cmd/d-project-cjfe-landing` 的已上線版本複製。

| 版本 | 路徑 |
| --- | --- |
| C | `/` |
| E | `/e/` |
| F | `/f/` |
| I | `/i/` |
| J | `/j/` |
| K | `/k/` |

## 設定與資料

- 沿用既有後台與 LINE 設定；FB 像素改為依固定倉庫編號 `copy2` 和版本獨立配置。
- C、E、F、I、J 依原版本寫入 D 項目訂單；K 沿用 X 貸款 K 版獨立提交流程。
- 在後台「複製倉庫二 · nexspirs.com」管理各版本 FB 像素。清空或讀取失敗時不回退共用像素。
- LINE、訂單歸類與甲方編號不受此 FB 配置隔離影響；同一像素 ID 若跨站重複配置，事件仍會匯入同一像素。

## 部署

GitHub Pages 使用 `main` 分支的根目錄。綁定新域名時，請到此倉庫的 Settings → Pages → Custom domain 設定，並在域名服務商設定 DNS。不要綁定其他投放網站正在使用的域名。
