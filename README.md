# dsh-avatar-manager-v1.0.0

为 DeepSeek Harness（dsh）工作区增加可自定义的头像：助手（左侧）与用户（右侧）头像，支持圆形 / 方形头像框，方形裁剪不产生偏移。

> dsh 第三方插件。本仓库提供可直接安装的发布包。

## 下载

- [`dsh-avatar-manager-v1.0.0.zip`](./dsh-avatar-manager-v1.0.0.zip) —— 完整发布包（7.2 KB）

## 安装

1. 解压 `dsh-avatar-manager-v1.0.0.zip`，得到目录 `dsh-avatar-manager`
2. 把 `dsh-avatar-manager` 整个目录放到：

   ```
   %USERPROFILE%\.dsh\external\
   ```

3. 在 `%USERPROFILE%\.dsh\profiles\desktop\package.json` 的 `dsh.profile.bundles` 中加入
   `@dsh-external/dsh-avatar-manager`，或使用 dsh 的插件管理面板安装
4. 重启 DeepSeek Harness

## 兼容性

| 项目 | 值 |
| --- | --- |
| 插件版本 | 1.0.0 |
| 声明的宿主版本范围 | `0.1.0-rc.6 - 0.2.1-rc.5` |
| 宿主平台 | web |
| 许可 | MIT |

超出声明范围运行不保证稳定。

## 包内文件

| 文件 | 大小 |
| --- | --- |
| `cordis.patch.yml` | 0.1 KB |
| `package.json` | 0.8 KB |
| `README.md` | 0.5 KB |
| `lib/client.js` | 18.5 KB |
| `lib/index.js` | 0.1 KB |

## 说明

本仓库仅托管发布包与说明文档，问题请在 Issues 中反馈。
