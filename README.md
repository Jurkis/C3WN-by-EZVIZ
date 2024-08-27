# C3WN-by-EZVIZ
Camera C3WN (model CS-CV310 (A0-1C2WFR)(4mm)) by EZVIZ setup in 'tinyCam PRO' Android app.
# Setup in 'tinyCam PRO' Android app
This is how I setup 'tinyCam PRO' Android app to work with my camera C3WN of Ezviz:
1. Name: Any name you wish
2. Vendor: Hikvision
3. Model: DC-2CD2012-I (Camera model was selected the first from cameras list)
4. Hostname: 192.168.1.7 [or any IP you wish, make it static in your LAN]
5. Web port: 8000
6. Protocol: RTSP over TCP
7. RTSP port: 554
8. HTTPS: no
9. Username: admin
10. Password: [camerapassword]

# Enable RTSP on your camera
The local RTSP server on your camera needs to be enabled. To do that:
1. Open the EZVIZ mobile app.
2. Select the profile icon.
3. Navigate to Settings > LAN Live View > Start Scanning.
4. Select your camera.
5. Select the gear-like icon in the top-right corner > Local Server Settings > enable RTSP.
