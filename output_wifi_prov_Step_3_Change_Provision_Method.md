I (31) boot: ESP-IDF v5.3 2nd stage bootloader
I (31) boot: compile time Sep 26 2024 13:34:13
I (31) boot: Multicore bootloader
I (35) boot: chip revision: v1.0
I (39) boot.esp32: SPI Speed      : 40MHz
I (43) boot.esp32: SPI Mode       : DIO
I (48) boot.esp32: SPI Flash Size : 2MB
I (52) boot: Enabling RNG early entropy source...
I (58) boot: Partition Table:
I (61) boot: ## Label            Usage          Type ST Offset   Length
I (69) boot:  0 nvs              WiFi data        01 02 00009000 00006000
I (76) boot:  1 phy_init         RF data          01 01 0000f000 00001000
I (84) boot:  2 factory          factory app      00 00 00010000 00140000
I (91) boot: End of partition table
I (95) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=2a1ach (172460) map
I (163) esp_image: segment 1: paddr=0003a1d4 vaddr=3ffbdb60 size=0571ch ( 22300) load
I (171) esp_image: segment 2: paddr=0003f8f8 vaddr=40080000 size=00720h (  1824) load
I (172) esp_image: segment 3: paddr=00040020 vaddr=400d0020 size=a2510h (664848) map
I (405) esp_image: segment 4: paddr=000e2538 vaddr=40080720 size=15a18h ( 88600) load
I (451) boot: Loaded app from partition at offset 0x10000
I (451) boot: Disabling RNG early entropy source...
I (463) cpu_start: Multicore app
I (472) cpu_start: Pro cpu start user code
I (472) cpu_start: cpu freq: 160000000 Hz
I (472) app_init: Application information:
I (475) app_init: Project name:     ESP_Wifi_Provision
I (481) app_init: App version:      1
I (485) app_init: Compile time:     Sep 26 2024 14:29:13
I (491) app_init: ELF file SHA256:  269a4f63d...
I (496) app_init: ESP-IDF:          v5.3
I (501) efuse_init: Min chip rev:     v0.0
I (506) efuse_init: Max chip rev:     v3.99 
I (511) efuse_init: Chip rev:         v1.0
I (516) heap_init: Initializing. RAM available for dynamic allocation:
I (523) heap_init: At 3FFAE6E0 len 0000F480 (61 KiB): DRAM
I (529) heap_init: At 3FFC74D0 len 00018B30 (98 KiB): DRAM
I (535) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (541) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (548) heap_init: At 40096138 len 00009EC8 (39 KiB): IRAM
I (556) spi_flash: detected chip: generic
I (558) spi_flash: flash io: dio
W (562) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (577) coexist: coex firmware version: dab85ae96
I (582) main_task: Started on CPU0
I (592) main_task: Calling app_main()
I (632) wifi:wifi driver task: 3ffb80e8, prio:23, stack:6656, core=0
I (642) wifi:wifi firmware version: 0caa81945
I (642) wifi:wifi certification version: v7.0
I (642) wifi:config NVS flash: enabled
I (642) wifi:config nano formating: disabled
I (642) wifi:Init data frame dynamic rx buffer num: 32
I (652) wifi:Init static rx mgmt buffer num: 5
I (652) wifi:Init management short buffer num: 32
I (662) wifi:Init dynamic tx buffer num: 32
I (662) wifi:Init static rx buffer size: 1600
I (672) wifi:Init static rx buffer num: 10
I (672) wifi:Init dynamic rx buffer num: 32
I (672) wifi_init: rx ba win: 6
I (682) wifi_init: accept mbox: 6
I (682) wifi_init: tcpip mbox: 32
I (682) wifi_init: udp mbox: 6
I (692) wifi_init: tcp mbox: 6
I (692) wifi_init: tcp tx win: 5760
I (702) wifi_init: tcp rx win: 5760
I (702) wifi_init: tcp mss: 1440
I (702) wifi_init: WiFi IRAM OP enabled
I (712) wifi_init: WiFi RX IRAM OP enabled
I (812) app: Button pressed
I (812) app: Starting provisioning
I (822) app: Development mode: using hard coded salt
I (822) app: Development mode: using hard coded verifier
I (822) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (902) wifi:mode : sta (9c:9c:1f:d5:6a:00)
I (912) wifi:enable tsf
I (922) wifi:mode : sta (9c:9c:1f:d5:6a:00) + softAP (9c:9c:1f:d5:6a:01)
I (922) wifi:Total power save buffer number: 16
I (922) wifi:Init max length of beacon: 752/752
I (922) wifi:Init max length of beacon: 752/752
I (932) esp_netif_lwip: DHCP server started on interface WIFI_AP_DEF with IP: 192.168.4.1
I (932) wifi:Total power save buffer number: 16
I (942) esp_netif_lwip: DHCP server started on interface WIFI_AP_DEF with IP: 192.168.4.1
I (952) wifi_prov_mgr: Provisioning started with service name : PROV_D56A00 
I (962) app: Provisioning started
I (962) app: Scan this QR code from the provisioning application for Provisioning.
I (972) QRCODE: Encoding below text with ECC LVL 0 & QR Code Version 10
I (982) QRCODE: {"ver":"v1","name":"PROV_D56A00","username":"wifiprov","pop":"abcd1234","transport":"softap"}

  █▀▀▀▀▀█ ▄▄█  ███   ▀▀ ▄█ ▀███ █▀▀▀▀▀█
  █ ███ █ ▀▄  ▄ ███▀ █▄ ███  █▀ █ ███ █   
  █ ▀▀▀ █ █▀█ █▀▀█▀ ▄▄▀▀▄▀▄▀██  █ ▀▀▀ █
  ▀▀▀▀▀▀▀ █ █▄▀ ▀ █▄▀ ▀▄▀▄▀ ▀▄█ ▀▀▀▀▀▀▀   
  █▀ █ ▄▀█ ▄ ████ ▀▄▀ ▀█▄ ███   ██▀▄▀█▄
  █▄ ██▄▀ ██▀███▄  ▀▀█▀█▀▄██ ▄  ▄█▄▄▀ █
   ▄ ▄  ▀█▀▀▀█ ▀ ▀▄▀▀▄███ █▀▄ ▄▄█  █  █
   ▄▀▄█▀▀▄  ▀█ ▄▄ ▀█  ▀█▀█ █▄▄ ██▀ ▄  ▀   
   ██▀█▄▀ ▀▀  █▄   ▀▀▀▀▀ ██▄▄▄▄█▀▀▄▄▀▀█
  █ ▄▀ █▀▄█▀ ▀█ ▀▄▀█▀▄▀▄▄ ▄ ▄ ▀▄▀██ ▄██   
   ▀▄▀█▀▀▄▄▀█▄ █  ▄▄▄ ▄█▀▀▄██   ▀ ▀▀  █
  ▄ █ ▄ ▀█ ▄█  ▄█    █▄█ ▄▀▄█▄█ █▄█▄▀▀█
   ▄ ▄▄ ▀▀▀▀▄▄██▄  █▄▄██  ▀█  ▄█▀▄ █▄▄█
  ▀▄█▀█▀▀▀▀▄▀ █▄█ ▄▄▀  ▄▀▀▀█▀▄█ ▄ ██▀▀█   
  ▀▀▀ ▀▀▀ ▄█ ▀ ▀█▀▄▀ ▀█▀▀█ ▄▄▄█▀▀▀█▄▀▄▄
  █▀▀▀▀▀█ ▀ █▄ █ ▄█▄█▄▀█  ▀ █ █ ▀ █▄▄▀▀   
  █ ███ █ ▄▄███▄▀ ▄  ▀▀█▄▀▀▀▀ █▀▀██ ▄     
  █ ▀▀▀ █ ▄█ ███▀ ▀▀ ▀█▄  ▄█ ▀▀█▀▄▀▄ ▀▀   
  ▀▀▀▀▀▀▀ ▀ ▀▀  ▀  ▀  ▀▀▀ ▀▀ ▀▀   ▀  ▀▀


I (1242) app: If QR code is not visible, copy paste the below URL in a browser.
https://espressif.github.io/esp-jumpstart/qrcode.html?data={"ver":"v1","name":"PROV_D56A00","username":"wifiprov","pop":"abcd1234","transport":"softap"}
I (46762) wifi:new:<1,0>, old:<1,1>, ap:<1,1>, sta:<0,0>, prof:1, snd_ch_cfg:0x0
I (46762) wifi:station: d2:2c:57:fc:9f:d9 join, AID=1, bgn, 20
I (46762) app: SoftAP transport: Connected!
I (47162) wifi:<ba-add>idx:2 (ifx:1, d2:2c:57:fc:9f:d9), tid:0, ssn:0, winSize:64
I (48572) esp_netif_lwip: DHCP server assigned IP to a client, IP is: 192.168.4.2
I (68142) security2: Using salt and verifier to generate public key...
I (68642) app: Secured session established!
W (77942) httpd_txrx: httpd_sock_err: error in recv : 104
I (98542) wifi:<ba-add>idx:3 (ifx:1, d2:2c:57:fc:9f:d9), tid:1, ssn:0, winSize:64
I (98572) wifi:<ba-add>idx:4 (ifx:1, d2:2c:57:fc:9f:d9), tid:5, ssn:0, winSize:64
I (108682) app: Received Wi-Fi credentials
        SSID     : AIS 4G Hi-Speed Home WiFi_76947550769475
        Password : 50769475
I (112792) wifi:primary chan differ, old=1, new=11, start CSA timer
I (113192) wifi:switch to channel 11
I (113192) wifi:ap channel adjust o:1,1 n:11,2
I (113192) wifi:new:<11,0>, old:<1,0>, ap:<11,2>, sta:<0,0>, prof:1, snd_ch_cfg:0x0
I (113202) wifi:new:<11,2>, old:<11,0>, ap:<11,2>, sta:<11,0>, prof:1, snd_ch_cfg:0x0
I (113212) wifi:state: init -> auth (0xb0)
I (113222) wifi:state: auth -> assoc (0x0)
I (113232) wifi:state: assoc -> run (0x10)
I (113252) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 8, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (113252) wifi:security: WPA2-PSK, phy: bgn, rssi: -58
I (113272) wifi:pm start, type: 1

I (113272) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (113272) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (114282) app: Connected with IP Address:192.168.1.189
I (114282) esp_netif_handlers: sta ip: 192.168.1.189, mask: 255.255.255.0, gw: 192.168.1.1
I (114282) wifi_prov_mgr: STA Got IP
I (114292) app: Provisioning successful
I (114292) app: Hello World!
I (115102) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:4, winSize:64
I (115292) app: Hello World!
I (116292) app: Hello World!
I (117292) app: Hello World!
I (118292) app: Hello World!
I (119292) app: Hello World!
I (119882) wifi:station: d2:2c:57:fc:9f:d9 leave, AID = 1, reason = 4, bss_flags is 33721459, bss:0x3ffcb39c
I (119882) wifi:new:<11,0>, old:<11,2>, ap:<11,2>, sta:<11,0>, prof:1, snd_ch_cfg:0x0
I (119882) wifi:<ba-del>idx:2, tid:0
I (119892) wifi:<ba-del>idx:3, tid:1
I (119892) wifi:<ba-del>idx:4, tid:5
I (119892) wifi:mode : sta (9c:9c:1f:d5:6a:00)
I (119912) wifi_prov_mgr: Provisioning stopped
I (119912) app: SoftAP transport: Disconnected!
I (120292) app: Hello World!
I (121292) app: Hello World!
I (122292) app: Hello World!
I (123292) app: Hello World!
I (124292) app: Hello World!
I (125292) app: Hello World!
I (126292) app: Hello World!
I (127292) app: Hello World!
I (128292) app: Hello World!
I (129292) app: Hello World!
I (130292) app: Hello World!
I (131292) app: Hello World!
I (132292) app: Hello World!
I (133292) app: Hello World!
I (134292) app: Hello World!
I (135292) app: Hello World!
I (136292) app: Hello World!
I (137292) app: Hello World!
I (138292) app: Hello World!
I (139292) app: Hello World!
I (140292) app: Hello World!
I (141292) app: Hello World!
I (142292) app: Hello World!
I (143292) app: Hello World!
I (144292) app: Hello World!
I (145292) app: Hello World!
I (146292) app: Hello World!