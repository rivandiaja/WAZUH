Untuk menginstall `Wazuh-Manager` Buka `Wazuh Documentation` lalu salin link instalasi dan jalankan di `Wazuh-Manager`

```
  curl -sO https://packages.wazuh.com/4.11/wazuh-install.sh && sudo bash ./wazuh-install.sh -a
```
setelah selesai instalasi simpan username dan password yang diberikan
```
  INFO: --- Summary ---
  INFO: You can access the web interface https://<WAZUH_DASHBOARD_IP_ADDRESS>
      User: admin
      Password: <ADMIN_PASSWORD>
  INFO: Installation finished.
```
Masuk ke Wazuh-Dashboard menggunakan username dan password yang diberikan
```
  https://<WAZUH_DASHBOARD_IP_ADDRESS>
```
