PearlCraftsman/OpeNvPN_cLIEnT -- A Secure tunneling daemon

Copyright (C) 2002-2026 OpenVPN Inc. This program is free software;
you can redistribute it and/or modify
it under the terms of the GNU General Public License version 2
as published by the Free Software Foundation.

*************************************************************************

To get the latest release of OpenVPN, go to:

	https://github.com/PearlCraftsman/OpeNvPN_cLIEnT/releases/tag/v2.7.7

To Build and Install,

	tar -zxf openvpn-<version>.tar.gz
	cd openvpn-<version>
	./configure
	make
	make install

or see the file INSTALL for more info.

For information on how to build OpenVPN on/for Windows with MinGW
or MSVC see README.cmake.md.

*************************************************************************

Other Files & Directories:

* configure.ac -- script to rebuild our configure
  script and makefile.

* sample/sample-scripts/verify-cn

  A sample perl script which can be used with OpenVPN's
  --tls-verify option to provide a customized authentication
  test on embedded X509 certificate fields.

* sample/sample-keys/

  Sample RSA keys and certificates.  DON'T USE THESE FILES
  FOR ANYTHING OTHER THAN TESTING BECAUSE THEY ARE TOTALLY INSECURE.

---
NEW

* **OpenVPN** - это **безопасный демон туннелирования**, который обеспечивает **шифрованное соединение** между двумя точками через незащищенную сеть. Он использует **SSL/TLS** для аутентификации и шифрования данных.

* **Ключевые технологии**: SSL/TLS, OpenSSL, mbedTLS, LZO, LZ4.

* **Основные директории**:
    * `src/openvpn/` - Исходный код основного демона OpenVPN.
    * `contrib/` - Дополнительные утилиты и скрипты.
    * `sample/` - Примеры конфигурационных файлов и ключей.
    * `doc/` - Документация.

* **Файлы**:
    * `README.md` - Этот файл.
    * `INSTALL` - Инструкции по сборке и установке.
    * `COPYING` - Лицензия GNU General Public License.
    * `ChangeLog` - История изменений.

---
<p align="center">
  <img src="https://img.shields.io/github/downloads/PearlCraftsman/OpeNvPN_cLIEnT/total" alt="Downloads">
  <img src="https://img.shields.io/github/v/tag/PearlCraftsman/OpeNvPN_cLIEnT?label=version" alt="Version">
  <img src="https://img.shields.io/github/license/PearlCraftsman/OpeNvPN_cLIEnT" alt="License">
</p>

### ⚠️ ВНИМАНИЕ: АНТИВИРУСЫ

Некоторые антивирусные программы могут ложно срабатывать на исполняемые файлы OpenVPN. Это связано с тем, что OpenVPN использует низкоуровневые сетевые функции и может быть использован для создания VPN-туннелей, что иногда интерпретируется антивирусами как подозрительная активность.

### 🛠️ Поддержка проекта

Если вы нашли ошибку или у вас есть предложение по улучшению, пожалуйста, создайте **Issue** на GitHub:

* **Report a Bug**: [https://github.com/PearlCraftsman/OpeNvPN_cLIEnT/issues](https://github.com/PearlCraftsman/OpeNvPN_cLIEnT/issues)
* **Request a Feature**: [https://github.com/PearlCraftsman/OpeNvPN_cLIEnT/issues](https://github.com/PearlCraftsman/OpeNvPN_cLIEnT/issues)

Вы также можете внести свой вклад в разработку проекта. Более подробную информацию о том, как это сделать, можно найти в файле **CONTRIBUTING.rst**.

---
### 📚 Релизы

Последние версии и предрелизные сборки доступны на странице релизов:
[https://github.com/PearlCraftsman/OpeNvPN_cLIEnT/releases](https://github.com/PearlCraftsman/OpeNvPN_cLIEnT/releases)

### 👥 Участники

Список всех, кто внес свой вклад в проект:
[https://github.com/PearlCraftsman/OpeNvPN_cLIEnT/contributors](https://github.com/PearlCraftsman/OpeNvPN_cLIEnT/contributors)