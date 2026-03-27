---
layout: default
title: センサー一覧
---

# スマートフォンで取得できるセンサー・データ総覧

凡例: ○ = 対応　△ = 一部対応（端末依存・OS バージョン条件あり、または代替手段あり）　× = 非対応（一般公開 API なし・代替手段なし）

※ BG（バックグラウンド）列は、端末がそのセンサーを搭載している前提での対応状況を示す。

## 対応状況一覧

| 種別 | センサー / データ | Android | Android BG | iOS | iOS BG |
|---|---|:---:|:---:|:---:|:---:|
| **動作・姿勢系** | 加速度（3軸） | ○ | ○ | ○ | × |
| | <span style="color:#808080b3">加速度（未補正）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | ジャイロスコープ（3軸） | ○ | ○ | ○ | × |
| | <span style="color:#808080b3">ジャイロスコープ（未補正）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | 磁気センサー（3軸） | ○ | ○ | ○ | × |
| | <span style="color:#808080b3">磁気センサー（未補正）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | 重力センサー | ○ | ○ | ○ | × |
| | 線形加速度（重力除去） | ○ | ○ | ○ | × |
| | <span style="color:#808080b3">姿勢（attitude / 回転ベクトル）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">ゲーム用姿勢（地磁気非依存）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | コンパス方位 | ○ | ○ | ○ | × |
| **歩行・活動系** | 歩数（累積） | ○ | ○ | ○ | ○ |
| | <span style="color:#808080b3">歩行検出（一歩ごと）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">歩行 cadence / pace</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">階数（昇降）</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">オドメータ（移動距離）</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○ (iOS 17.0+)</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">Significant Motion（大きな動きの検出）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">Motion Detect / Stationary Detect</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">Off-body Detect（端末が身体から離れた検知）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">×</span> |
| **環境センサー** | 気圧 | △ | ○ | ○ | × |
| | <span style="color:#808080b3">相対高度</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">絶対高度</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | 照度（周囲の明るさ） | ○ | ○ | × | × |
| | 近接センサー | ○ | ○ | ○ | × |
| | 周囲温度 | △ | ○ | × | × |
| | 相対湿度 | △ | ○ | × | × |
| **位置・測位系** | GPS / GNSS（緯度経度・高度・速度・進行方向） | ○ | ○ | ○ | ○ |
| | <span style="color:#808080b3">Wi-Fi 測位</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">Bluetooth / BLE 測位（ビーコン）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">基地局測位</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">GNSS Raw Measurements（生の衛星計測）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">GNSS Antenna Info</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">UWB 近距離測位</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> |
| **カメラ・映像系** | <span style="color:#808080b3">カメラ（前面・背面）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">TrueDepth 深度（前面）</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | LiDAR 深度（背面） | × | × | ○ | × |
| <span style="color:#808080b3">**音声・通信系**</span> | <span style="color:#808080b3">マイク</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">Wi-Fi 情報（SSID・電波強度・周辺 AP）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">Bluetooth 周辺デバイス情報</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">NFC</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> |
| <span style="color:#808080b3">**生体・健康系**</span> | <span style="color:#808080b3">心拍センサー</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">生体認証（指紋 / 顔認証）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">歩数・活動量（ペドメーター）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| <span style="color:#808080b3">**デバイス状態系**</span> | <span style="color:#808080b3">バッテリー（残量・充電状態・温度）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">ネットワーク状態（Wi-Fi / 4G / 5G 等）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">画面状態（オン/オフ・輝度）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">音量・サイレントモード</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> |
| | <span style="color:#808080b3">ヘッドトラッキング（対応ヘッドホン）</span> | <span style="color:#808080b3">○ (API 33+)</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> |
| | <span style="color:#808080b3">ヒンジ角（折りたたみ端末）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">×</span> | <span style="color:#808080b3">×</span> |
| | <span style="color:#808080b3">6DoF Pose（位置 + 姿勢の 6 自由度）</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">○</span> | <span style="color:#808080b3">△</span> | <span style="color:#808080b3">×</span> |

---

## 各センサー・データの説明

### 動作・姿勢系

**加速度センサー** は端末に加わる加速度を x / y / z の 3 軸で計測する。端末の動き・振動・傾きの検出に使われ、補正済みの値と補正前（未補正）の生値の両方が取得できる。未補正値は Android では公開 API があるが、iOS には明示的な同等 API はない。

**ジャイロスコープ** は端末の回転角速度を 3 軸で計測する。加速度センサーと組み合わせることで、端末の姿勢変化を精密に追跡できる。ドリフト補正前の未補正値も Android では取得可能。

**磁気センサー（コンパス）** は地磁気の強さを 3 軸で計測し、方位の推定に用いられる。未補正値は Android のみ公開 API で取得できる。

**重力センサー** はセンサー融合によって算出した重力ベクトルを返す。加速度センサーの値から重力成分だけを抽出したもので、端末の傾き検出に使われる。

**線形加速度** は加速度から重力成分を除いた値で、端末の操作や衝撃による加速度のみを取り出せる。

**姿勢（attitude / 回転ベクトル）** は加速度・ジャイロ・磁気センサーを統合し、端末の roll / pitch / yaw（傾き・回転）を表す。Android では `TYPE_ROTATION_VECTOR`、iOS では `CMDeviceMotion.attitude` が対応する。

**ゲーム用姿勢** は地磁気に依存しない姿勢情報で、磁気干渉の多い環境でも安定した回転追跡が必要な場合に使われる。iOS には同名の公開 API はなく `CMDeviceMotion` で代用する。

**コンパス方位** は北を基準とした方位角を返す。Android では磁気センサーと加速度センサーを組み合わせて算出し、iOS では `CLHeading` を用いる。

---

### 歩行・活動系

**歩数（累積）** は端末起動からの累積歩数を返すセンサーで、Android 4.4 以降・iOS 8.0 以降で対応する。Android 10 以降は `ACTIVITY_RECOGNITION` 権限が必要。

**歩行検出** は一歩踏み出すたびにイベントを発火させるセンサー。歩数カウントの低レイテンシ実装に用いられる。iOS には直接同名の API はなく、ペドメーターイベントで代替する。

**歩行 cadence / pace** は単位時間あたりの歩数（テンポ）と 1 歩あたりの所要時間（ペース）を示す。iOS の `CMPedometer` が専用の項目を持つ一方、Android は実装依存になることが多い。

**階数** はエレベーターや階段での昇降階数を返す。気圧センサーを利用する場合が多い。iOS の `CMPedometer` で取得できるが、Android には標準 API がない。

**オドメータ** は移動距離の高次情報を提供する iOS 専用 API（`CMOdometerData`、iOS 17.0 以降）。Android には対応する標準 API がない。

**Significant Motion** は端末が大きく動いたことを検知するトリガーセンサー。バックグラウンドでの位置更新契機などに使われる Android 固有の機能。iOS には同名の API はないが、`CMMotionActivityManager` で動作状態の変化を検知することで代替できる。

**Motion Detect / Stationary Detect** は端末が動いているか静止しているかを検知する Android 固有センサー（API 24 以降）。iOS には同名の API はないが、`CMMotionActivityManager` の `stationary` / `walking` 等のアクティビティで代替できる。

**Off-body Detect** は端末が身体（ポケットなど）から離れたことを検知する Android 固有センサー（API 26 以降）。

---

### 環境センサー

**気圧センサー** は大気圧を計測し、高度推定や天候変化の検出に利用される。Android・iOS 両対応で、iOS では `CMAltimeter` が担当する。

**相対高度 / 絶対高度** は気圧センサーを基に算出される高度情報。相対高度はアプリ起動時点からの変化量、絶対高度は海抜基準の値を返す。iOS は `CMAltimeter` に専用 API があり、絶対高度は iOS 15.0 以降・対応端末限定。Android は Location API や気圧センサーの組み合わせで近似する。

**照度センサー** は周囲の明るさを計測し、画面輝度の自動調整などに利用される。Android のみ公開 API が提供されており、iOS には一般公開の照度センサー API はない。

**近接センサー** は顔や物体が端末に近づいたことを検知する。通話中の画面自動消灯や誤タッチ防止に使われ、Android・iOS 両対応。

**周囲温度・相対湿度** は周囲の気温・湿度を計測するセンサー。Android の API は存在するが搭載端末は少なく、iOS では公開 API が存在しない。

---

### 位置・測位系

**GPS / GNSS** は衛星測位により緯度・経度・高度・速度・進行方向を取得する。GPS 単体ではなく Wi-Fi・基地局・気圧センサーとの組み合わせで精度を補う（GNSS 融合測位）。Android・iOS ともに Location API で統合的に利用できる。

**Wi-Fi 測位・基地局測位** は周囲の Wi-Fi アクセスポイントや携帯基地局の情報から位置を推定する。GPS が届かない屋内や地下でも機能するが、精度は低い。

**Bluetooth / BLE 測位（ビーコン）** は BLE ビーコンの電波強度から屋内位置を推定する。iBeacon として iOS が先行して整備したが、Android でも BLE スキャンで対応可能。

**GNSS Raw Measurements** は衛星からの生の測距情報（搬送波位相・擬似距離など）を取得する Android 固有 API（Android 7 以降）。高精度測位や RTK 処理に利用される。iOS には一般公開 API がない。

**UWB 近距離測位** は Ultra Wideband 電波を用いて端末間の相対距離・方向を数十 cm 精度で測定する。iOS は iPhone 11 以降の Nearby Interaction フレームワークで対応。Android は対応端末依存。

---

### カメラ・映像系

**カメラ（前面・背面）** は静止画・動画撮影、QR コード読み取り、AR などに利用される。Android・iOS ともに標準 API で制御できる。

**TrueDepth 深度（前面）** は赤外線ドットパターン投影による前面の深度マップで、Face ID 搭載の iPhone で利用できる。iOS の `AVFoundation` で取得可能。

**LiDAR 深度（背面）** は背面 LiDAR センサーによる高精度な深度マップで、iPhone/iPad Pro 系モデルで利用できる。AR アプリや 3D スキャンに活用される。

---

### 音声・通信系

**マイク** は音声入力・環境音録音・音量レベル検出に使われる。Android・iOS ともに対応しており、バックグラウンド利用には権限が必要。

**Wi-Fi 情報** は接続中の SSID・電波強度・周辺アクセスポイント一覧などを返す。Android は比較的自由に取得できるが、iOS はプライバシー制限により接続先 SSID の取得に特別なエンタイトルメントが必要。

**Bluetooth** は周辺デバイスのスキャン・接続・通信を行う。BLE を利用したセンサー連携やビーコン測位にも使われる。

**NFC** は NFC タグや IC カードの読み取りに対応。Android は読み書き両対応、iOS は iOS 11 以降でタグ読み取りが可能（書き込みは iOS 13 以降）。

---

### 生体・健康系

**心拍センサー** は心拍数をリアルタイムで計測する。Android でも `TYPE_HEART_RATE` が定義されているが搭載端末は少なく、iPhone 本体に一般公開の心拍 API はない（Apple Watch 等のウェアラブルは別）。

**生体認証（指紋 / 顔認証）** はユーザーの本人確認に使われる。Android は指紋センサーが主流で、iOS は Touch ID（一部機種）および Face ID を生体認証に利用する。どちらも OS の認証 API（Android BiometricPrompt / iOS LocalAuthentication）経由でアプリから呼び出せる。

**歩数・活動量（ペドメーター）** は端末内蔵のモーションコプロセッサがバックグラウンドで歩数・距離・階数などを蓄積する。Android は `TYPE_STEP_COUNTER`、iOS は `CMPedometer` で取得できる。

---

### デバイス状態系

**バッテリー** は残量・充電状態（充電中 / 満充電 / 放電中）・温度などを返す。Android・iOS ともに標準 API で取得でき、省電力制御の判断に使われる。

**ネットワーク状態** は現在の通信種別（Wi-Fi / 4G / 5G など）や接続状況を返す。オフライン検出や通信切り替え処理に利用される。

**画面状態** は画面のオン/オフ・輝度設定を返す。バックグラウンド処理の制御や UI 適応に利用される。

**音量・サイレントモード** は現在の音量レベルやマナーモード（サイレント）状態を取得する。通知制御などに利用される。iOS ではバックグラウンドで現在値の読み取り（`AVAudioSession.outputVolume`）は可能だが、音量変化のリアルタイム検知（`outputVolumeDidChange`）はバックグラウンドでは受信されない。

**ヘッドトラッキング** は対応ヘッドホンの姿勢（向き・傾き）を取得する。Android は API 33 以降の `TYPE_HEAD_TRACKER`、iOS は `CMHeadphoneMotionManager`（iOS 14.0 以降）が対応。空間オーディオなどに利用される。

**ヒンジ角** は折りたたみ Android 端末の開閉角度を取得するセンサー（API 30 以降）。折りたたみ状態に応じた UI 切り替えなどに利用される。iOS には該当センサーがない。

**6DoF Pose** は端末の 3 次元位置と 3 軸姿勢を組み合わせた 6 自由度の位置姿勢情報。Android 固有（API 24 以降）で、AR 向けの精密な端末追跡に利用される。

---

## プラットフォーム差異まとめ

| 観点 | Android | iOS |
|---|---|---|
| センサー API の種類 | 多い（端末依存の差が大きい） | 少なめだが品質が安定している |
| バックグラウンド取得 | 比較的自由 | 厳しく制限される |
| 環境温度・湿度・照度 | 一部機種で可 | 基本不可 |
| LiDAR / TrueDepth | 一部機種のみ | Pro 系モデル・Face ID 搭載機 |
| 高精度 GNSS（生データ） | 対応（Android 7+） | 非対応 |
| UWB 近距離測位 | 対応端末依存 | iPhone 11 以降で対応 |
| 権限モデル | API 23 以降はランタイム権限 | 明示的なユーザー許可が必要 |


## 参考資料

- [Android センサーの概要](https://developer.android.com/develop/sensors-and-location/sensors/sensors_overview?hl=ja)

