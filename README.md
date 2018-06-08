## Kurulum

1. SSH yada Filezilla üzerinden sunucuya bağlanın.
2. "/etc/init.d/" konumuna "ts3" adlı dosyayı aktarın.
3. PuTTY veya herhangi bir program aracılığıyla SSH erişimi sağlayın.
4. "cd /etc/init.d" komutu ile "init.d" klasörüne erişin.
5. "chmod 0755 ts3" komutu ile "ts3" adlı dosyaya 755 izni uygulayın.
6. CentOS için "chkconfig ts3 on" , Debian/Ubuntu için "update-rc.d ts3 defaults" komutunu uygulayın.
7. Sunucuya reboot atın.
8. Son olarak "cd /etc/init.d" komutunu uygulayarak "init.d" klösrüne gidin ve "/etc/init.d/ts3 start" komutunu verin.

----- Bundan sonraki reboot veya kapanıp açılma işlemlerinde TeamSpeak sunucunuz otomatik olarak başlayacaktır -----

## Credits

Hasan CAN - https://hasan.im
