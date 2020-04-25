# go-oculus-go
UnityでOculus Go/Quest用のVRアプリを作成する。各アプリのプロジェクトはリポジトリ内でサブフォルダに分けて配置する。
|サブフォルダ名|説明|
|-|-|
|hello|空間にキューブを浮かべているのをOculus Go/Questで見られるようにする|
|dance|人間のモデルを表示させダンスさせる|
|room|室内に物体と人間のモデルを配置し動作させる|

# 必要なもの
- Oculus Go/Quest
- MacまたはWindowsマシン
- ネットワーク環境
- Unity
- Blender

## Oculus Go/Quest
Oculus Go/Questは、OSがAndroidであるコンピュータにVRゴーグルが1体となったデバイス。VRゴーグル、アプリの実行環境として利用する。
| 機種 | 特徴 |
| - | - |
| Go | ゴーグルの回転角をxyzの3軸について検出できる |
| Quest | Goの回転に加え、ゴーグルの平行移動をxyzの3軸について検出できる |

これがないと始まらない。Questが望ましいがGoでも可。
- [Oculus Go/Quest開発者サイト](https://developer.oculus.com)
## MacまたはWindowsマシン、ネットワーク環境、Unity、Blender
アプリの開発自体はMacまたはWindowsマシンでUnityという開発ツールを使って行う。
- [Unity](https://unity.com/ja)

BlenderはこのUnityで扱う3Dモデルを作成するために使用する。
- [Blender](https://www.blender.org)

Unity、Blenderはインターネットからのダウンロードとなる。
# 準備
- MacまたはWindowsマシンにUnityをインストールしておく
- アプリ開発にあたりOculus Go/Questは開発者モードにしておかなければならない
- MacまたはWindowsマシンで開発したアプリをOculus Go/Questに転送させるため、両者間をUSBケーブルで繋ぐ必要がある
- Windowsマシンからの転送にはOculus ADB Driversも必要となる
## Unityをインストールしておく
Unityをダウンロードしインストールする。
この際にAndroidアプリを作れるようにする。
すでにインストール済みでAndroidアプリ作成未対応なら、Unity Hubを立ち上げ、インストールタブでインストールされているUnityのメニューからAndroid Build SupportおよびAndroid SDK & NDK Tools、OpenJDKにチェックを入れてインストールする。
## Oculus Go/Questを開発者モードにする
- Oculus Go/Quest開発者サイトで開発者登録する
- スマートフォンまたはタブレットにOculusアプリをインストールする
- 使用するOculus Go/QuestをOculusアプリに登録する
- 登録したOculus Go/Quest項目をタップすると設定に進めるので開発者モードを設定する
## Windowsマシンからの転送にはOculus ADB DriversをWindowsマシンにインストールする
- [Oculus ADB Drivers](https://developer.oculus.com/downloads/package/oculus-adb-drivers/)
## MacまたはWindowsマシンとOculus Go/QuestをUSBケーブルで繋ぐ
Oculus Go/Questの電源を入れてUSBケーブルを繋ぐと、初めての時はOculus Go/Quest側でMacまたはWindowsマシンとの接続を許可するか聞かれるので許可する。
# Unityでプロジェクトの登録
開発するOculus Go/QuestアプリのプロジェクトをUnityHubに登録しプロジェクトを開く。
# 実行
起動したプロジェクトでFile>Build and Runメニューを選ぶと、アプリがビルドされ、繋がれたOculus Go/Questに転送、実行される。


