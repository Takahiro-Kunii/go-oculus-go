# go-oculus-go
UnityでOculus Go/Quest用のVRアプリを作成する。

# 必要なもの
- Oculus Go/Quest
- MacまたはWindowsマシン
- ネットワーク環境
- Unity
- Blender

## Oculus Go/Quest
これがないと始まらない。Questが望ましいがGoでも可。
- [Oculus Go/Quest](https://developer.oculus.com)

VRゴーグル、アプリの実行環境として利用。

Oculus Go/Questは、OSがAndroidであるコンピュータにVRゴーグルが1体となったデバイス。
| 機種 | 特徴 |
| - | - |
| Go | ゴーグルの回転角をxyzの3軸について検出できる |
| Quest | これに加え、ゴーグルの平行移動をxyzの3軸について検出できる |
## MacまたはWindowsマシン、ネットワーク環境、Unity、Blender
アプリの開発自体はMacまたはWindowsマシンでUnityという開発ツールを使って行う。
- [Unity](https://unity.com/ja)

BlenderはこのUnityで扱う3Dモデルを作成するために使用する。
- [Blender](https://www.blender.org)

Unity、Blenderはインターネットからのダウンロードとなる。

# 準備せよ
アプリ開発にあたりOculus Go/Questは開発者モードにしておかなければならない。
## Oculus Go/Questを開発者モードにする
また、MacまたはWindowsマシンで開発したアプリをOculus Go/Questに転送させるため、両者間をUSBケーブルで繋ぐ必要がある。
Windowsマシンからの転送にはOculus ADB Driversも必要。
- [Oculus ADB Drivers](https://developer.oculus.com/downloads/package/oculus-adb-drivers/)
## UnityにはAndroid開発環境をインストールしておく
Unity Hubを立ち上げ、インストールタブでインストールされているUnityのメニューからAndroid Build SupportおよびAndroid SDK & NDK Tools、OpenJDKにチェックを入れてインストールする。
# Unityでプロジェクトの作成
開発するOculus Go/Questアプリのプロジェクトを作成する。このリポジトリでは以下が該当する。
- [tank-girl-unity]()
# 実行
起動したプロエクトのFile>Build and Runメニューを選ぶと、アプリがビルドされ、繋がれたOculus Go/Questに転送、実行される。


