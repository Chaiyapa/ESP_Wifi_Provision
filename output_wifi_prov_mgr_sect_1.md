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
I (83) boot:  2 factory          factory app      00 00 00010000 00140000
I (91) boot: End of partition table
I (95) esp_image: segment 0: paddr=00010020 vaddr=3f400020 size=2b374h (177012) map
I (164) esp_image: segment 1: paddr=0003b39c vaddr=3ffbdb60 size=04c7ch ( 19580) load
I (172) esp_image: segment 2: paddr=00040020 vaddr=400d0020 size=bafach (765868) map
I (434) esp_image: segment 3: paddr=000fafd4 vaddr=3ffc27dc size=00ed0h (  3792) load
I (436) esp_image: segment 4: paddr=000fbeac vaddr=40080000 size=1bd2ch (113964) load
I (499) boot: Loaded app from partition at offset 0x10000
I (499) boot: Disabling RNG early entropy source...
I (511) cpu_start: Multicore app
I (520) cpu_start: Pro cpu start user code
I (520) cpu_start: cpu freq: 160000000 Hz
I (520) app_init: Application information:
I (523) app_init: Project name:     ESP_Wifi_Provision
I (528) app_init: App version:      1
I (533) app_init: Compile time:     Sep 26 2024 13:32:56
I (539) app_init: ELF file SHA256:  616465be1...
I (544) app_init: ESP-IDF:          v5.3
I (549) efuse_init: Min chip rev:     v0.0
I (553) efuse_init: Max chip rev:     v3.99
I (558) efuse_init: Chip rev:         v1.0
I (563) heap_init: Initializing. RAM available for dynamic allocation:
I (570) heap_init: At 3FFAFF10 len 000000F0 (0 KiB): DRAM
I (576) heap_init: At 3FFB6388 len 00001C78 (7 KiB): DRAM
I (582) heap_init: At 3FFB9A20 len 00004108 (16 KiB): DRAM
I (589) heap_init: At 3FFC9E90 len 00016170 (88 KiB): DRAM
I (595) heap_init: At 3FFE0440 len 00003AE0 (14 KiB): D/IRAM
I (601) heap_init: At 3FFE4350 len 0001BCB0 (111 KiB): D/IRAM
I (608) heap_init: At 4009BD2C len 000042D4 (16 KiB): IRAM
I (616) spi_flash: detected chip: generic
I (618) spi_flash: flash io: dio
W (622) spi_flash: Detected size(4096k) larger than the size in the binary image header(2048k). Using the size in the binary image header.
I (636) coexist: coex firmware version: dab85ae96
I (642) main_task: Started on CPU0
I (652) main_task: Calling app_main()
I (682) wifi:wifi driver task: 3ffcdcf4, prio:23, stack:6656, core=0
I (682) wifi:wifi firmware version: 0caa81945
I (682) wifi:wifi certification version: v7.0
I (682) wifi:config NVS flash: enabled
I (682) wifi:config nano formating: disabled
I (692) wifi:Init data frame dynamic rx buffer num: 32
I (692) wifi:Init static rx mgmt buffer num: 5
I (702) wifi:Init management short buffer num: 32
I (702) wifi:Init dynamic tx buffer num: 32
I (702) wifi:Init static rx buffer size: 1600
I (712) wifi:Init static rx buffer num: 10
I (712) wifi:Init dynamic rx buffer num: 32
I (722) wifi_init: rx ba win: 6
I (722) wifi_init: accept mbox: 6
I (722) wifi_init: tcpip mbox: 32
I (732) wifi_init: udp mbox: 6
I (732) wifi_init: tcp mbox: 6
I (732) wifi_init: tcp tx win: 5760
I (742) wifi_init: tcp rx win: 5760
I (742) wifi_init: tcp mss: 1440
I (752) wifi_init: WiFi IRAM OP enabled
I (752) wifi_init: WiFi RX IRAM OP enabled
I (762) wifi_prov_scheme_ble: BT memory released
I (762) app: Starting provisioning
I (772) app: Development mode: using hard coded salt
I (772) app: Development mode: using hard coded verifier
I (782) phy_init: phy_version 4830,54550f7,Jun 20 2024,14:22:08
I (862) wifi:mode : sta (9c:9c:1f:d5:6a:00)
I (862) wifi:enable tsf
I (872) BTDM_INIT: BT controller compile version [f021fb7]
I (872) BTDM_INIT: Bluetooth MAC: 9c:9c:1f:d5:6a:02
I (1132) protocomm_nimble: BLE Host Task Started
I (1142) wifi_prov_mgr: Provisioning started with service name : PROV_D56A00
I (1142) app: Provisioning started
I (1152) app: Scan this QR code from the provisioning application for Provisioning.
I (1152) QRCODE: Encoding below text with ECC LVL 0 & QR Code Version 10
I (1162) QRCODE: {"ver":"v1","name":"PROV_D56A00","username":"wifiprov","pop":"abcd1234","transport":"ble"}
I (1182) NimBLE: GAP procedure initiated: advertise; 
I (1192) NimBLE: disc_mode=2
I (1192) NimBLE:  adv_channel_map=0 own_addr_type=0 adv_filter_policy=0 adv_itvl_min=256 adv_itvl_max=256
I (1192) NimBLE:


  █▀▀▀▀▀█ ███ ▀▄▀▀▀▄▄▄█▄▀▀▄▄▀▀  █▀▀▀▀▀█
  █ ███ █ █▄▀█ ▄▄▄█▀▀▀▄▀▀█▄▄ ▄█ █ ███ █
  █ ▀▀▀ █ ▄  ▄▄█▀▀▀  ▄▀█▄▀ ▀█▀  █ ▀▀▀ █   
  ▀▀▀▀▀▀▀ ▀▄▀ █ █ █▄▀ ▀▄▀▄▀ ▀▄█ ▀▀▀▀▀▀▀
  ▀▀  █▀▀▄  ▄▀▄▄█▄ ▀█▀▄▀██▀▄ ▄▀▄ █▄▀▀▀▀
  ▀█▄ ▄█▀██▀██▀▀ ▀█▄  ▄▄▄▀▄ █████ ▀█▄█▄   
  ▀█▄ ▀ ▀▄▀▀█ ▀  █▀██▀▀▀ ▄▀▄ ▄▀ ▀█▄▀█▄▀   
  ▄ ▄ █▄▀ ▀█▄ ▄ █▀██▀▄▀▄██▀▀▄█▄█▄█ █▄
  ▄█ █▄▄▀▀██▄▀▄▀█▄ ▀█▀▀█ █▀▄▄ ▄██▀▄ ▀▀▀   
   █▄▀ ▄▀▄ ▄▄█▀█▀█▀▄ ▄ █▄▀█ █▀▀█ █▄▀▄▄▄
   ███▀ ▀▀▄██ ▀█▄▄█▀ ▀▀▀ ▄ ▄ ▄▀██▀▄█▀█▀   
  ▀▀▀▄▄▄▀ ▀█  ▄ ▄▀██▀ ▀▄█▀ ▀ █ █▄▀ █▄▄▄
  █▄█▄▀█▀▀ ▄ ▀▄▀▀▄█▀ ▀▀▀█▄█ ▄▄▀▀█▀▄▀▀ ▀   
    ██▀▀▀ ▄ ▀█▀█▀▀ ▄ ▄ ██▀ ▀▀█▀ █▄█▄█▀▄
  ▀▀▀▀  ▀▀▄▄▀ ▀█▄█▄▀▄▀██▀█▄▄▄ █▀▀▀█ ▀▄
  █▀▀▀▀▀█ ▄▄▀ ▄ ▄███▄▄ ▄ ▀  ▄▀█ ▀ ██▄▄▄
  █ ███ █ ▀██▀▄▀▀▄██▄ ▄▀█▄█ ▄▄████▀▄█▄▄
  █ ▀▀▀ █ ▄▄██▀█▀▀▄▄▀▄ ████ █ ▄  ▀▄██▄
  ▀▀▀▀▀▀▀ ▀▀▀ ▀▀  ▀▀ ▀▀▀  ▀  ▀   ▀▀ ▀▀▀


I (1462) app: If QR code is not visible, copy paste the below URL in a browser.
https://espressif.github.io/esp-jumpstart/qrcode.html?data={"ver":"v1","name":"PROV_D56A00","username":"wifiprov","pop":"abcd1234","transport":"ble"}
I (149312) app: BLE transport: Connected!
I (149472) protocomm_nimble: mtu update event; conn_handle=0 cid=4 mtu=256
I (151242) security2: Using salt and verifier to generate public key...
I (152262) app: Secured session established!
I (295022) app: Received Wi-Fi credentials
        SSID     : AIS 4G Hi-Speed Home WiFi_76947550769475
        Password : 50769475
I (301122) wifi:new:<11,0>, old:<1,0>, ap:<255,255>, sta:<11,0>, prof:1, snd_ch_cfg:0x0
I (301132) wifi:state: init -> auth (0xb0)
I (301132) wifi:state: auth -> assoc (0x0)
I (301152) wifi:state: assoc -> run (0x10)
I (301172) wifi:connected with AIS 4G Hi-Speed Home WiFi_769475, aid = 8, channel 11, BW20, bssid = 30:0a:c5:9e:94:9f
I (301172) wifi:security: WPA2-PSK, phy: bgn, rssi: -53
I (301202) wifi:pm start, type: 1

I (301202) wifi:dp: 1, bi: 102400, li: 3, scale listen interval from 307200 us to 307200 us
I (301252) wifi:AP's beacon interval = 102400 us, DTIM period = 1
I (301362) wifi:<ba-add>idx:0 (ifx:0, 30:0a:c5:9e:94:9f), tid:0, ssn:2, winSize:64
I (308202) app: Connected with IP Address:192.168.1.189
I (308202) esp_netif_handlers: sta ip: 192.168.1.189, mask: 255.255.255.0, gw: 192.168.1.1
I (308202) wifi_prov_mgr: STA Got IP
I (308212) app: Provisioning successful
I (308212) app: Hello World!
I (309212) app: Hello World!
I (310212) app: Hello World!
I (311212) app: Hello World!
I (311522) NimBLE: GAP procedure initiated: stop advertising.

I (311522) NimBLE: GAP procedure initiated: stop advertising.

I (311522) NimBLE: GAP procedure initiated: terminate connection; conn_handle=0 hci_reason=19

E (311592) protocomm_nimble: Error setting advertisement data; rc = 30
I (311602) wifi_prov_mgr: Provisioning stopped
I (311602) app: BLE transport: Disconnected!
I (311602) wifi_prov_scheme_ble: BTDM memory released
I (312212) app: Hello World!
I (313212) app: Hello World!
I (314212) app: Hello World!
I (315212) app: Hello World!
I (316212) app: Hello World!
I (317212) app: Hello World!
I (318212) app: Hello World!
I (319212) app: Hello World!