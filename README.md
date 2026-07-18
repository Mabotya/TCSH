# TCSH - TRAIN CREW Sound Hub

TCSHは、**TRAIN CREW**のカスタムサウンド管理や音声制作、放送、API連動をまとめたWindows向けの非公式補助ツールです。

音声ファイルの変換・配置を簡単に行えるほか、プリセット、音声編集、作曲、マイク放送、ゲーム情報を表示するカスタムUIなどを利用できます。

> TCSHは非公式ツールです。  
> TRAIN CREW公式および関係各所とは一切関係ありません。

## ダウンロード

右側の「Releases」または以下のページから、最新版をダウンロードしてください。

**[最新版をダウンロード](../../releases/latest)**

## 主な機能

- TRAIN CREW用カスタムサウンドの設定・自動配置
- WAV変換、モノラル化、音量・長さ・フェード調整
- 音声エフェクト、波形表示、試聴
- プリセットの保存・共有・バックアップ
- よく使う音声を保存できる音声ライブラリ
- 複数の音声を組み合わせられる音声編集
- ピアノロールを使った簡易作曲・WAV出力
- マイクを使用した車内・車外放送
- グローバルPTT、車内・車外モード切り替え
- TRAIN CREW APIを利用した盲導鈴などの連動機能
- 速度、時刻、信号、ATS、ノッチなどを表示するカスタムUI
- 自動アップデート確認
- 日本語・英語・韓国語・繁体字中国語・簡体字中国語に対応

## 基本的な使い方

1. TCSHを起動します。
2. TRAIN CREWのCustomフォルダを選択します。
3. 変更したい項目に音声ファイルを設定します。
4. 必要に応じて音量や長さ、エフェクトを調整します。
5. Customフォルダへ保存します。
6. TRAIN CREWが起動中の場合は、ゲームを再起動します。

標準のCustomフォルダは以下です。

`Documents\TrainCrew\Custom`

## Microsoft Defender SmartScreenについて

個人開発のWindows向けソフトのため、初回起動時にMicrosoft Defender SmartScreenの警告が表示される場合があります。

このGitHubリポジトリからダウンロードしたことを確認したうえで実行する場合は、  
**「詳細情報」→「実行」** を選択してください。

配布元を確認できない場合や、不安がある場合は実行しないでください。

## 注意事項

- TRAIN CREW側の仕様変更により、正常に動作しなくなる場合があります。
- API連動機能やカスタムUIは、TRAIN CREWから取得できる情報に依存します。
- 音声やプリセットを共有する際は、著作権や利用規約を確認してください。
- 本ソフトの使用によって発生した不具合やデータ損失について、開発者は責任を負いません。

## 不具合報告・要望

不具合や機能要望は、以下のページから送信できます。

**[TCSH 不具合報告・要望フォーム](https://o-nnect.com/tcsh%e5%a0%b1%e5%91%8a/)**

## 配布について

本ソフトの無断転載、再配布、改変は禁止します。

---

## About TCSH

TCSH is an unofficial Windows utility that brings together custom sound management, audio production, broadcasting, and API-linked features for **TRAIN CREW**.

In addition to converting and placing audio files, TCSH provides presets, audio editing, music composition, microphone broadcasting, and a customizable window for displaying game information.

> TCSH is an unofficial utility.  
> It is not affiliated with the official TRAIN CREW team or any related parties.

## Download

Download the latest version from the “Releases” section on the right or from the page below.

**[Download the latest version](../../releases/latest)**

## Main Features

- Configure and automatically place custom sounds for TRAIN CREW
- Convert audio to WAV and adjust mono output, volume, duration, and fades
- Apply audio effects, view waveforms, and preview audio
- Save, share, and back up presets
- Store frequently used sounds in the audio library
- Combine multiple audio files with the multitrack audio editor
- Create simple music with the piano roll and export it as WAV
- Use a microphone for interior and exterior broadcasting
- Use global PTT and global interior/exterior mode switching
- Use API-linked features such as guide-bell playback
- Display speed, time, signals, ATS, controller notches, and other information in the Custom UI
- Automatically check for updates
- Supports Japanese, English, Korean, Traditional Chinese, and Simplified Chinese

## Basic Usage

1. Launch TCSH.
2. Select the TRAIN CREW Custom folder.
3. Assign an audio file to the item you want to change.
4. Adjust the volume, duration, effects, and other settings as needed.
5. Save the files to the Custom folder.
6. Restart TRAIN CREW if the game is already running.

The standard Custom folder is:

`Documents\TrainCrew\Custom`

## Microsoft Defender SmartScreen

Because TCSH is an independently developed Windows application, Microsoft Defender SmartScreen may display a warning when it is launched for the first time.

After confirming that TCSH was downloaded from this GitHub repository, select:

**“More info” → “Run anyway”**

Do not run the application if you cannot confirm where it was downloaded from or if you have any concerns.

## Notes

- Future changes to TRAIN CREW may prevent TCSH from working correctly.
- API-linked features and the Custom UI depend on information provided by TRAIN CREW.
- Check copyright and licensing terms before sharing audio files or presets.
- The developer assumes no responsibility for problems or data loss caused by the use of this software.

## Bug Reports and Feature Requests

Bug reports and feature requests can be submitted from the page below.

**[TCSH Bug Report and Feature Request Form](https://o-nnect.com/tcsh%e5%a0%b1%e5%91%8a/)**

## Distribution

Unauthorized uploading, redistribution, and modification of this software are prohibited.

## FFmpegについて

TCSHには、動画ファイルから音声を抽出するため、FFmpegを同梱しています。

- ソフトウェア: FFmpeg
- バージョン: 7.1-essentials_build-www.gyan.dev
- ライセンス: GNU General Public License version 3 (GPLv3)
- ビルド提供元: Gyan.dev
- ビルド形式: Windows 64-bit static essentials build
- FFmpegソースコミット: b08d7969c5
- 同梱ffmpeg.exe SHA-256:  
  `2CE797A0F88D7F067180338FB227F7B1928EA727BD9A4D7A1D022F7C52AF71A3`

FFmpegおよび同梱された関連ライブラリの著作権は、それぞれの権利者に帰属します。
TCSHはFFmpegを独立した実行ファイルとして起動し、別プロセスで利用しています。

### ライセンス

- GPLv3ライセンス全文:  
  https://www.gnu.org/licenses/gpl-3.0.html
- TCSHに同梱しているライセンス表示:  
  `tools/FFmpeg/LICENSE.txt`

### 配布元・プロジェクト

- ビルド提供元:  
  https://www.gyan.dev/ffmpeg/builds/
- FFmpegプロジェクト:  
  https://ffmpeg.org/

### 対応ソースコード

TCSHに同梱しているFFmpegバイナリに対応するソースコード、ビルド設定および関連資料は、以下から取得できます。

- 対応ソースコード一式:  
  [ffmpeg-7.1-essentials_build-corresponding-source.zip](実際のRelease AssetへのURL)
- 使用したFFmpeg本体のソース:  
  https://github.com/FFmpeg/FFmpeg/commit/b08d7969c5
- 同梱ビルドの構成情報:  
  `tools/FFmpeg/README.txt`
