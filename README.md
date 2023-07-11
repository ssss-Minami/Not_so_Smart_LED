# Not_so_Smart_LED
+ 创建热点
  >ssid: LAPTOP-DH47FHT3 6509
  >
  >key: 22332233

+ nuc连接至热点，修改IP地址、子网掩码为
  >192.168.137.21
  >
  >255.255.255.0

+ 重启MQTT服务器
  >sudo systermctl restart mosquitto.service

+ 运行
  >python3 person_detect_mqtt.py
  .py文件在/home/person什么什么的一个文件夹里

+ 结果
  >SDKVersion[0x3020201]
  >Connected to MQTT Broker!
  >Find 1 devices!
  >
  >u3v device: [0]
  >device model name: MV-CA016-10UC
  >user serial number: 00K01829492
  >press a key to stop grabbing.
  >INFO: Created TensorFlow Lite XNNPACK delegate for CPU.
  >Send `0.058794498443603516`, `0.5515105128288269`, `-0.041321564465761185` to topic `pose_x`, `pose_y`, `pose_z`
  >Send `0.7573527097702026`, `0.48874354362487793`, `-1.3059470653533936` to topic `pose_x`, `pose_y`, `pose_z`
  >Send `0.7348895072937012`, `0.5120759010314941`, `-0.9977606534957886` to topic `pose_x`, `pose_y`, `pose_z`
  >Send `0.7130177021026611`, `0.436440110206604`, `-1.1693328619003296` to topic `pose_x`, `pose_y`, `pose_z`

+ 注意事项
  1.相机USB接口应在电源接口上方
  2.热点仅2.4g


