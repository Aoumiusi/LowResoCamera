# LowResoCamera

An Android camera app that lets you take photos in a retro game or pixel art style.

---

## 📱 Overview

**LowResoCamera** is an Android camera app that automatically reduces the resolution and color count of captured photos. You can easily create flavorful pictures that look like retro games or pixel art from the 80s and 90s.

### ✨ Features

- 🎮 **Retro Game Style**: Nostalgic, dot-art-style photos with 8 to 256 colors.
- 🎨 **Customizable**: Freely set resolution, color count, and monochrome mode.
- 📸 **Real-Time Preview**: Check the finished look before taking the picture.
- 🔄 **Multiple Camera Support**: Switch between front and back cameras.
- 🎯 **Pinch Zoom**: Intuitive zoom operation with two fingers.
- 🌍 **Multilingual Support**: Available in Japanese and English.
- 🆓 **Completely Free**: No ads, no in-app purchases.

---

## 🎯 Key Features

### Camera Features
- **High-Quality Preview**: Smooth, real-time camera preview.
- **Multi-Camera**: Supports all device cameras (front/back/ultra-wide, etc.).
- **Pinch Zoom**: Digital zoom up to 10x magnification.
- **Auto-Rotation**: Correctly captures photos in both portrait and landscape orientation.
- **Hardware Buttons**: Supports volume buttons, camera buttons, and Bluetooth shutters.

### Image Processing
- **Resolution Selection**: Choose from 128 / 192 / 256 / 384 / 512 px.
- **Color Reduction**: Choose from 8 / 16 / 32 / 64 / 256 colors.
- **Monochrome Mode**: For a black-and-white retro atmosphere.
- **High-Quality Algorithm**: Natural color reduction using the Median Cut method.

### Save Formats
- **JPEG**: High compression, small file size.
- **PNG**: Lossless compression, high quality.

### Other
- **Preview Function**: Review the photo immediately after capturing before saving.
- **Shutter Sound**: Can be turned On/Off.
- **Settings Persistence**: Remembers your settings even after closing the app.

---

## 📥 Installation

### Requirements
- Android 7.0 (API Level 24) or higher
- Device with a camera
- Storage write permission (requested automatically)

### Download
1. Download the APK file.
2. Allow installation from "Unknown sources."
3. Tap the APK to install.
4. Grant camera permission.

---

## 🚀 Quick Start

### 1. Launch the App
Please grant camera permission upon the first launch.

### 2. Adjust Settings (Optional)
You can set your preferred image quality from the ⚙️ Settings button on the bottom left.

### 3. Capture
- Tap the center ⭕️ button
- Or, press the volume button

### 4. Save
Tap "Save" on the preview screen to save the image to the `Pictures/LowResoCamera` folder.

---

## 🎨 Usage Examples

### Retro Game Style (8 Colors, 128px)
Creates a feel similar to old Game Boy or Famicom games.

**Recommended Settings**:
- Size: 128
- Color Count: 8 Colors
- Monochrome: Off

### Pixel Art Style (32 Colors, 256px)
For pixel art or dot-picture-like expression.

**Recommended Settings**:
- Size: 256
- Color Count: 32 Colors
- Monochrome: Off

### Monochrome Art (16 Colors, 384px)
For artistic black-and-white photos.

**Recommended Settings**:
- Size: 384
- Color Count: 16 Colors
- Monochrome: On

### Abstract Art (256 Colors, 512px)
For an Impressionist-like expression with reduced colors.

**Recommended Settings**:
- Size: 512
- Color Count: 256 Colors
- Monochrome: Off

---

## ⚙️ Settings Items

| Item | Description | Default |
|------|-------------|-----------|
| **Shutter Sound** | On/Off for the sound when taking a photo | On |
| **Preview Display** | Display the preview after taking a photo | On |
| **Size** | The size of the image's longest side | 256px |
| **Color Count** | The number of colors to use | 32 Colors |
| **Monochrome** | Convert the image to black and white | Off |
| **Image Format** | JPEG or PNG | JPEG |

---

## 🆚 Full Version vs. Demo Version

### Full Version (LowResoCamera)
- All features are available.
- Settings can be customized.

### Demo Version (LowResoCamera Demo)
- Only the capture function is available.
- Settings are fixed (256px, 32 colors).
- Can be installed simultaneously with the Full Version.

---

## 💡 Tips

### For Better Photos

1. **Shoot in Bright Light**: Since the color count is low, shooting in bright places is recommended.
2. **Be Mindful of Contrast**: Subjects with clear color contrast look good.
3. **Simple Composition**: Simple compositions are more effective than complex backgrounds.
4. **Shoot Close-Up**: Small subjects may be blurred out at low resolution, so take a close-up shot.
5. **Experiment**: Try various settings to discover interesting expressions.

### Comfortable Shooting with Hardware Buttons

- **Volume Buttons**: Easy shooting with one hand.
- **Bluetooth Shutter**: Convenient for selfies and group photos.
- Hardware buttons skip the preview and save directly.

---

## 🔧 Technical Information

### Technologies Used
- **Language**: Kotlin
- **Camera API**: CameraX 1.5.1
- **Minimum SDK**: Android 7.0 (API 24)
- **Architecture**: Component-based

### Image Processing Algorithms
- **Color Reduction**: Median Cut Algorithm
- **Monochrome Conversion**: Weighted Average Method (ITU-R BT.601)
- **Resize**: Bicubic Interpolation

---

## 🙋 FAQ

### Q: Where are the saved images?
A: They are saved in the "LowResCamera" folder within the "Pictures" folder on your device.

### Q: The orientation of the preview and the saved image is different.
A: This has been fixed in the latest version. Please update the app.

### Q: I can't switch cameras.
A: The switch button will not appear if your device only has one camera.

### Q: I can't zoom.
A: You can zoom by pinching (pinching) the screen with two fingers.

### Q: Settings are not being saved.
A: The settings are fixed in the Demo Version. Please use the Full Version.

---

## 🐛 Troubleshooting

### Camera Not Launching
1. Check if camera permission is granted.
2. Check if another app is using the camera.
3. Restart the app.
4. Restart the device.

### App Crashing
1. Update the app to the latest version.
2. Check the device's storage capacity.
3. Clear app data (Settings → Apps → LowResoCamera → Storage → Clear Data).

### Image Not Saving
1. Check the storage capacity.
2. Check if camera permission is granted.
3. Check the "Pictures/LowResCamera" folder with a file manager.

---

## 📞 Support

If the problem persists, please contact us with the following information:
- Device Name
- Android Version
- App Version
- Detailed description of the issue

---

## 📝 Update History

### Version 1.0 (2025-01-XX)
- Initial Release
- Basic camera functionality
- Image processing features (resolution adjustment, color reduction, monochrome)
- Settings screen
- Multilingual support (Japanese/English)
- Full/Demo build variants

---

## 🎉 Acknowledgments

Thanks to all the users who use this app.
We hope we can assist you in your creative work.

---

**LowResoCamera** - Bring a retro flavor to your photos.

© 2025 aoumiusi. All rights reserved.

---
# LowResoCamera

レトロゲーム風・ピクセルアート風の写真が撮れる Android カメラアプリ

---

## 📱 概要

**LowResoCamera** は、撮影した写真を自動的に低解像度＆色数削減処理する Android カメラアプリです。まるで80〜90年代のレトロゲームやピクセルアートのような、味わい深い写真を簡単に作成できます。

### ✨ 特徴

- 🎮 **レトロゲーム風**: 8色〜256色の懐かしいドット絵風写真
- 🎨 **カスタマイズ可能**: 解像度・色数・モノクロを自由に設定
- 📸 **リアルタイムプレビュー**: 撮影前に仕上がりイメージを確認
- 🔄 **複数カメラ対応**: フロント・バックカメラの切り替え
- 🎯 **ピンチズーム**: 2本指で直感的にズーム操作
- 🌍 **多言語対応**: 日本語・英語に対応
- 🆓 **完全無料**: 広告なし、アプリ内課金なし

---

## 🎯 主な機能

### カメラ機能
- **高品質プレビュー**: スムーズなリアルタイムカメラプレビュー
- **マルチカメラ**: デバイスの全カメラに対応（フロント/バック/超広角など）
- **ピンチズーム**: 最大10倍までのデジタルズーム
- **自動回転**: 縦横どちらの向きでも正しく撮影
- **ハードウェアボタン**: 音量ボタン、カメラボタン、Bluetoothシャッターに対応

### 画像処理
- **解像度選択**: 128 / 192 / 256 / 384 / 512 px から選択
- **色数削減**: 8 / 16 / 32 / 64 / 256 色から選択
- **モノクロモード**: 白黒のレトロな雰囲気に
- **高品質アルゴリズム**: Median Cut 方式で自然な色削減

### 保存形式
- **JPEG**: 高圧縮、ファイルサイズ小
- **PNG**: 可逆圧縮、高品質

### その他
- **プレビュー機能**: 撮影直後に確認してから保存
- **シャッター音**: オン/オフ切り替え可能
- **設定保持**: アプリを閉じても設定を記憶

---

## 📥 インストール

### 必要要件
- Android 7.0 (API Level 24) 以上
- カメラ搭載デバイス
- ストレージ書き込み権限（自動的に要求されます）

### ダウンロード
1. APKファイルをダウンロード
2. 「提供元不明のアプリ」のインストールを許可
3. APKをタップしてインストール
4. カメラ権限を許可

---

## 🚀 クイックスタート

### 1. アプリを起動
初回起動時にカメラ権限を許可してください。

### 2. 設定を調整（オプション）
左下の⚙️設定ボタンから、お好みの画質を設定できます。

### 3. 撮影
- 中央の⭕️ボタンをタップ
- または、音量ボタンを押す

### 4. 保存
プレビュー画面で「保存」をタップすると、Pictures/LowResoCameraフォルダに保存されます。

---

## 🎨 使用例

### レトロゲーム風（8色・128px）
昔のゲームボーイやファミコンのような雰囲気に。

**推奨設定**:
- サイズ: 128
- 色数: 8色
- モノクロ: オフ

### ドット絵風（32色・256px）
ピクセルアートやドット絵のような表現に。

**推奨設定**:
- サイズ: 256
- 色数: 32色
- モノクロ: オフ

### モノクロアート（16色・384px）
白黒の芸術的な写真に。

**推奨設定**:
- サイズ: 384
- 色数: 16色
- モノクロ: オン

### 抽象アート（256色・512px）
色数を抑えた印象派風の表現に。

**推奨設定**:
- サイズ: 512
- 色数: 256色
- モノクロ: オフ

---

## ⚙️ 設定項目

| 項目 | 説明 | デフォルト |
|------|------|-----------|
| **シャッター音** | 撮影時の音のオン/オフ | オン |
| **プレビュー表示** | 撮影後のプレビュー表示 | オン |
| **サイズ** | 画像の長辺サイズ | 256px |
| **色数** | 使用する色の数 | 32色 |
| **モノクロ** | 白黒画像に変換 | オフ |
| **画像形式** | JPEG または PNG | JPEG |

---

## 🆚 製品版とデモ版の違い

### 製品版（LowResoCamera）
- すべての機能が利用可能
- 設定のカスタマイズが可能

### デモ版（LowResoCamera Demo）
- 撮影機能のみ利用可能
- 設定は固定（256px、32色）
- 製品版と同時インストール可能

---

## 💡 Tips

### より良い写真を撮るために

1. **明るい場所で撮影**: 色数が少ないため、明るい場所での撮影がおすすめ
2. **コントラストを意識**: はっきりした色の対比がある被写体が映える
3. **シンプルな構図**: 複雑な背景より、シンプルな構図が効果的
4. **近づいて撮影**: 小さい被写体は解像度が低いと潰れるため、大きく撮る
5. **実験してみる**: 設定を変えて色々試すと面白い表現が見つかります

### ハードウェアボタンで快適撮影

- **音量ボタン**: 片手で簡単に撮影
- **Bluetoothシャッター**: 自撮りや集合写真に便利
- ハードウェアボタンはプレビューをスキップして直接保存されます

---

## 🔧 技術情報

### 使用技術
- **言語**: Kotlin
- **カメラAPI**: CameraX 1.5.1
- **最小SDK**: Android 7.0 (API 24)
- **アーキテクチャ**: コンポーネントベース

### 画像処理アルゴリズム
- **色削減**: Median Cut アルゴリズム
- **モノクロ変換**: 加重平均法（ITU-R BT.601）
- **リサイズ**: Bicubic補間

---

## 🙋 FAQ

### Q: 保存した画像はどこにありますか？
A: 端末の「Pictures」フォルダ内の「LowResCamera」フォルダに保存されています。

### Q: プレビューと保存画像の向きが違う
A: 最新版では修正されています。アプリを最新版に更新してください。

### Q: カメラの切り替えができない
A: デバイスにカメラが1つしかない場合、切り替えボタンは表示されません。

### Q: ズームできない
A: 2本の指で画面をピンチ（つまむ）するとズームできます。

### Q: 設定が保存されない
A: デモ版は設定が固定されています。製品版をご利用ください。

---

## 🐛 トラブルシューティング

### カメラが起動しない
1. カメラ権限が許可されているか確認
2. 他のアプリがカメラを使用していないか確認
3. アプリを再起動
4. デバイスを再起動

### アプリがクラッシュする
1. アプリを最新版に更新
2. デバイスのストレージ容量を確認
3. アプリデータをクリア（設定 → アプリ → LowResoCamera → ストレージ → データを消去）

### 画像が保存されない
1. ストレージ容量を確認
2. カメラ権限が許可されているか確認
3. ファイルマネージャーで「Pictures/LowResCamera」フォルダを確認

---

## 📞 サポート

問題が解決しない場合は、以下の情報を添えてお問い合わせください：
- デバイス名
- Androidバージョン
- アプリバージョン
- 問題の詳細

---

## 📝 更新履歴

### Version 1.0 (2025-01-XX)
- 初回リリース
- 基本的なカメラ機能
- 画像処理機能（解像度調整、色数削減、モノクロ）
- 設定画面
- 多言語対応（日本語/英語）
- 製品版/デモ版ビルドバリアント

---

## 🎉 謝辞

このアプリを使ってくださるすべてのユーザーの皆様に感謝します。
皆様のクリエイティブな作品作りのお手伝いができれば幸いです。

---

**LowResoCamera** - レトロな味わいを、あなたの写真に。

© 2025 aoumiusi. All rights reserved.
