# xianxia-cdn

遁一峰大厅悬浮窗（火狐角色卡）的构建产物，供 jsDelivr 按提交号取用。源码在私有仓库，这里的文件是 `split_build.py` 生成的，别手改。

- `dist/xianxia.css`、`dist/xianxia.js`：样式和脚本
- `dist/assets/`：图片、字体子集（文件名是内容哈希）

取用地址固定到提交号：`https://cdn.jsdelivr.net/gh/anonchihaya379-code/xianxia-cdn@<提交号>/dist/xianxia.js`（备用 `fastly.jsdelivr.net`）。

## 许可

- 字体子集：马善政（Ma Shan Zheng）、霞鹜文楷（LXGW WenKai）、思源宋体（Noto Serif SC），均为 SIL Open Font License 1.1，见 `OFL.txt`。
- 水墨素材部分取自 shuimo-ui（MIT）；一幅泼墨取自 OpenGameArt（CC0）。
- 三位角色的立绘由作者用即梦生成，用途以即梦的用户协议为准；其余图形为作者自绘或程序生成。未经许可请勿另作他用。
