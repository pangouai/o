# OneDrive to OneDrive Transfer

GitHub Actions + rclone
用于 OneDrive 到 OneDrive 的自动转存。

## 使用步骤
1. 本地配置 rclone.conf（两个 OneDrive）
2. 将 rclone.conf 内容保存到 GitHub Secret：RCLONE_CONF
3. 修改 workflow 中的 remote 名称
4. 手动或定时运行 Action
