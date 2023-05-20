
## 터미널에서 데이터를 전송하는 샘플

> {"dataType":"SENSOR","param":[{"id":"sensor1","desc":"1번 센서","value":10},{"id":"sensor2","desc":"2번 센서","value":20}]}

> 0A 55 89 00 00 00 7B 22 64 61 74 61 54 79 70 65 22 3A 22 53 45 4E 53 4F 52 22 2C 22 70 61 72 61 6D 22 3A 5B 7B 22 69 64 22 3A 22 73 65 6E 73 6F 72 31 22 2C 22 64 65 73 63 22 3A 22 31 EB B2 88 20 EC 84 BC EC 84 9C 22 2C 22 76 61 6C 75 65 22 3A 31 30 7D 2C 7B 22 69 64 22 3A 22 73 65 6E 73 6F 72 32 22 2C 22 64 65 73 63 22 3A 22 32 EB B2 88 20 EC 84 BC EC 84 9C 22 2C 22 76 61 6C 75 65 22 3A 32 30 7D 5D 7D 18 B7

```sh
project\entry\js_test is 📦 v0.1.0 via  v16.20.0
❯ node .\src\main.js
{"dataType":"SENSOR","param":[{"id":"sensor1","desc":"1번 센서","value":10},{"id":"sensor2","desc":"2번 센서","value":20}]}
packetLength: 137 / jsonBytes.length: 129 / crc16: 46872
0A 55 89 00 00 00 7B 22 64 61 74 61 54 79 70 65 22 3A 22 53 45 4E 53 4F 52 22 2C 22 70 61 72 61 6D 22 3A 5B 7B 22 69 64 22 3A 22 73 65 6E 73 6F 72 31 22 2C 22 64 65 73 63 22 3A 22 31 EB B2 88 20 EC 84 BC EC 84 9C 22 2C 22 76 61 6C 75 65 22 3A 31 30 7D 2C 7B 22 69 64 22 3A 22 73 65 6E 73 6F 72 32 22 2C 22 64 65 73 63 22 3A 22 32 EB B2 88 20 EC 84 BC EC 84 9C 22 2C 22 76 61 6C 75 65 22 3A 32 30 7D 5D 7D 18 B7
dataArray.length: 137
i: 0, data: A / 10, indexSession: 0, indexReceiver: 0
i: 1, data: 55 / 85, indexSession: 0, indexReceiver: 1
i: 2, data: 89 / 137, indexSession: 1, indexReceiver: 0
i: 3, data: 0 / 0, indexSession: 1, indexReceiver: 1
i: 4, data: 0 / 0, indexSession: 1, indexReceiver: 2
i: 5, data: 0 / 0, indexSession: 1, indexReceiver: 3
dataLength: 129
i: 6, data: 7B / 123, indexSession: 2, indexReceiver: 0
i: 7, data: 22 / 34, indexSession: 2, indexReceiver: 1
i: 8, data: 64 / 100, indexSession: 2, indexReceiver: 2
i: 9, data: 61 / 97, indexSession: 2, indexReceiver: 3
i: 10, data: 74 / 116, indexSession: 2, indexReceiver: 4
i: 11, data: 61 / 97, indexSession: 2, indexReceiver: 5
i: 12, data: 54 / 84, indexSession: 2, indexReceiver: 6
i: 13, data: 79 / 121, indexSession: 2, indexReceiver: 7
i: 14, data: 70 / 112, indexSession: 2, indexReceiver: 8
i: 15, data: 65 / 101, indexSession: 2, indexReceiver: 9
i: 16, data: 22 / 34, indexSession: 2, indexReceiver: 10
i: 17, data: 3A / 58, indexSession: 2, indexReceiver: 11
i: 18, data: 22 / 34, indexSession: 2, indexReceiver: 12
i: 19, data: 53 / 83, indexSession: 2, indexReceiver: 13
i: 20, data: 45 / 69, indexSession: 2, indexReceiver: 14
i: 21, data: 4E / 78, indexSession: 2, indexReceiver: 15
i: 22, data: 53 / 83, indexSession: 2, indexReceiver: 16
i: 23, data: 4F / 79, indexSession: 2, indexReceiver: 17
i: 24, data: 52 / 82, indexSession: 2, indexReceiver: 18
i: 25, data: 22 / 34, indexSession: 2, indexReceiver: 19
i: 26, data: 2C / 44, indexSession: 2, indexReceiver: 20
i: 27, data: 22 / 34, indexSession: 2, indexReceiver: 21
i: 28, data: 70 / 112, indexSession: 2, indexReceiver: 22
i: 29, data: 61 / 97, indexSession: 2, indexReceiver: 23
i: 30, data: 72 / 114, indexSession: 2, indexReceiver: 24
i: 31, data: 61 / 97, indexSession: 2, indexReceiver: 25
i: 32, data: 6D / 109, indexSession: 2, indexReceiver: 26
i: 33, data: 22 / 34, indexSession: 2, indexReceiver: 27
i: 34, data: 3A / 58, indexSession: 2, indexReceiver: 28
i: 35, data: 5B / 91, indexSession: 2, indexReceiver: 29
i: 36, data: 7B / 123, indexSession: 2, indexReceiver: 30
i: 37, data: 22 / 34, indexSession: 2, indexReceiver: 31
i: 38, data: 69 / 105, indexSession: 2, indexReceiver: 32
i: 39, data: 64 / 100, indexSession: 2, indexReceiver: 33
i: 40, data: 22 / 34, indexSession: 2, indexReceiver: 34
i: 41, data: 3A / 58, indexSession: 2, indexReceiver: 35
i: 42, data: 22 / 34, indexSession: 2, indexReceiver: 36
i: 43, data: 73 / 115, indexSession: 2, indexReceiver: 37
i: 44, data: 65 / 101, indexSession: 2, indexReceiver: 38
i: 45, data: 6E / 110, indexSession: 2, indexReceiver: 39
i: 46, data: 73 / 115, indexSession: 2, indexReceiver: 40
i: 47, data: 6F / 111, indexSession: 2, indexReceiver: 41
i: 48, data: 72 / 114, indexSession: 2, indexReceiver: 42
i: 49, data: 31 / 49, indexSession: 2, indexReceiver: 43
i: 50, data: 22 / 34, indexSession: 2, indexReceiver: 44
i: 51, data: 2C / 44, indexSession: 2, indexReceiver: 45
i: 52, data: 22 / 34, indexSession: 2, indexReceiver: 46
i: 53, data: 64 / 100, indexSession: 2, indexReceiver: 47
i: 54, data: 65 / 101, indexSession: 2, indexReceiver: 48
i: 55, data: 73 / 115, indexSession: 2, indexReceiver: 49
i: 56, data: 63 / 99, indexSession: 2, indexReceiver: 50
i: 57, data: 22 / 34, indexSession: 2, indexReceiver: 51
i: 58, data: 3A / 58, indexSession: 2, indexReceiver: 52
i: 59, data: 22 / 34, indexSession: 2, indexReceiver: 53
i: 60, data: 31 / 49, indexSession: 2, indexReceiver: 54
i: 61, data: EB / 235, indexSession: 2, indexReceiver: 55
i: 62, data: B2 / 178, indexSession: 2, indexReceiver: 56
i: 63, data: 88 / 136, indexSession: 2, indexReceiver: 57
i: 64, data: 20 / 32, indexSession: 2, indexReceiver: 58
i: 65, data: EC / 236, indexSession: 2, indexReceiver: 59
i: 66, data: 84 / 132, indexSession: 2, indexReceiver: 60
i: 67, data: BC / 188, indexSession: 2, indexReceiver: 61
i: 68, data: EC / 236, indexSession: 2, indexReceiver: 62
i: 69, data: 84 / 132, indexSession: 2, indexReceiver: 63
i: 70, data: 9C / 156, indexSession: 2, indexReceiver: 64
i: 71, data: 22 / 34, indexSession: 2, indexReceiver: 65
i: 72, data: 2C / 44, indexSession: 2, indexReceiver: 66
i: 73, data: 22 / 34, indexSession: 2, indexReceiver: 67
i: 74, data: 76 / 118, indexSession: 2, indexReceiver: 68
i: 75, data: 61 / 97, indexSession: 2, indexReceiver: 69
i: 76, data: 6C / 108, indexSession: 2, indexReceiver: 70
i: 77, data: 75 / 117, indexSession: 2, indexReceiver: 71
i: 78, data: 65 / 101, indexSession: 2, indexReceiver: 72
i: 79, data: 22 / 34, indexSession: 2, indexReceiver: 73
i: 80, data: 3A / 58, indexSession: 2, indexReceiver: 74
i: 81, data: 31 / 49, indexSession: 2, indexReceiver: 75
i: 82, data: 30 / 48, indexSession: 2, indexReceiver: 76
i: 83, data: 7D / 125, indexSession: 2, indexReceiver: 77
i: 84, data: 2C / 44, indexSession: 2, indexReceiver: 78
i: 85, data: 7B / 123, indexSession: 2, indexReceiver: 79
i: 86, data: 22 / 34, indexSession: 2, indexReceiver: 80
i: 87, data: 69 / 105, indexSession: 2, indexReceiver: 81
i: 88, data: 64 / 100, indexSession: 2, indexReceiver: 82
i: 89, data: 22 / 34, indexSession: 2, indexReceiver: 83
i: 90, data: 3A / 58, indexSession: 2, indexReceiver: 84
i: 91, data: 22 / 34, indexSession: 2, indexReceiver: 85
i: 92, data: 73 / 115, indexSession: 2, indexReceiver: 86
i: 93, data: 65 / 101, indexSession: 2, indexReceiver: 87
i: 94, data: 6E / 110, indexSession: 2, indexReceiver: 88
i: 95, data: 73 / 115, indexSession: 2, indexReceiver: 89
i: 96, data: 6F / 111, indexSession: 2, indexReceiver: 90
i: 97, data: 72 / 114, indexSession: 2, indexReceiver: 91
i: 98, data: 32 / 50, indexSession: 2, indexReceiver: 92
i: 99, data: 22 / 34, indexSession: 2, indexReceiver: 93
i: 100, data: 2C / 44, indexSession: 2, indexReceiver: 94
i: 101, data: 22 / 34, indexSession: 2, indexReceiver: 95
i: 102, data: 64 / 100, indexSession: 2, indexReceiver: 96
i: 103, data: 65 / 101, indexSession: 2, indexReceiver: 97
i: 104, data: 73 / 115, indexSession: 2, indexReceiver: 98
i: 105, data: 63 / 99, indexSession: 2, indexReceiver: 99
i: 106, data: 22 / 34, indexSession: 2, indexReceiver: 100
i: 107, data: 3A / 58, indexSession: 2, indexReceiver: 101
i: 108, data: 22 / 34, indexSession: 2, indexReceiver: 102
i: 109, data: 32 / 50, indexSession: 2, indexReceiver: 103
i: 110, data: EB / 235, indexSession: 2, indexReceiver: 104
i: 111, data: B2 / 178, indexSession: 2, indexReceiver: 105
i: 112, data: 88 / 136, indexSession: 2, indexReceiver: 106
i: 113, data: 20 / 32, indexSession: 2, indexReceiver: 107
i: 114, data: EC / 236, indexSession: 2, indexReceiver: 108
i: 115, data: 84 / 132, indexSession: 2, indexReceiver: 109
i: 116, data: BC / 188, indexSession: 2, indexReceiver: 110
i: 117, data: EC / 236, indexSession: 2, indexReceiver: 111
i: 118, data: 84 / 132, indexSession: 2, indexReceiver: 112
i: 119, data: 9C / 156, indexSession: 2, indexReceiver: 113
i: 120, data: 22 / 34, indexSession: 2, indexReceiver: 114
i: 121, data: 2C / 44, indexSession: 2, indexReceiver: 115
i: 122, data: 22 / 34, indexSession: 2, indexReceiver: 116
i: 123, data: 76 / 118, indexSession: 2, indexReceiver: 117
i: 124, data: 61 / 97, indexSession: 2, indexReceiver: 118
i: 125, data: 6C / 108, indexSession: 2, indexReceiver: 119
i: 126, data: 75 / 117, indexSession: 2, indexReceiver: 120
i: 127, data: 65 / 101, indexSession: 2, indexReceiver: 121
i: 128, data: 22 / 34, indexSession: 2, indexReceiver: 122
i: 129, data: 3A / 58, indexSession: 2, indexReceiver: 123
i: 130, data: 32 / 50, indexSession: 2, indexReceiver: 124
i: 131, data: 30 / 48, indexSession: 2, indexReceiver: 125
i: 132, data: 7D / 125, indexSession: 2, indexReceiver: 126
i: 133, data: 5D / 93, indexSession: 2, indexReceiver: 127
i: 134, data: 7D / 125, indexSession: 2, indexReceiver: 128
i: 135, data: 18 / 24, indexSession: 3, indexReceiver: 0
i: 136, data: B7 / 183, indexSession: 3, indexReceiver: 1
BASE - Receiver - CRC16 - Calculated : B718, Received : B718
{"dataType":"SENSOR","param":[{"id":"sensor1","desc":"1번 센서","value":10},{"id":"sensor2","desc":"2번 센서","value":20}]}

```