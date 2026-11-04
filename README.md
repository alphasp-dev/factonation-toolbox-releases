# Factonation Toolbox — downloads

โปรแกรมฟรีสำหรับอ่าน เขียน และบันทึกค่า PLC / HMI Samkoon ผ่าน Modbus TCP
ดาวน์โหลดและคู่มือการใช้งานที่ **[factonation.com](https://factonation.com)**

Free Windows app (Windows 10/11, 64-bit) to read, write and log Samkoon PLC /
HMI addresses over Modbus TCP. This repository only hosts the installers; get
them, and the setup guide, from [factonation.com](https://factonation.com) or
from [Releases](../../releases/latest).

- **Installer:** `FactonationToolbox-setup.exe` (per-user install, no admin rights needed)
- **Command-line tool:** `ftb.exe` (portable, for diagnostics and support)

## วิธีติดตั้ง

1. ดาวน์โหลด `FactonationToolbox-setup.exe` จาก [Releases](../../releases/latest) แล้วดับเบิลคลิก
2. ถ้า Windows ขึ้นหน้าจอสีน้ำเงิน "Windows protected your PC" ให้กด **More info** แล้วกด **Run anyway**
   โปรแกรมยังไม่ได้เซ็นรับรองดิจิทัล ข้อความนี้จะขึ้นกับทุกเวอร์ชันใหม่
3. ติดตั้งได้โดยไม่ต้องใช้สิทธิ์ผู้ดูแลระบบ แล้วเปิดโปรแกรมจากเมนู Start

The installer is not code-signed yet: on the blue SmartScreen screen, click
**More info → Run anyway**.

No telemetry: the only internet request is the update check against this
repository, which sends nothing about you or your PLC and can be turned off in
the app. Support: admin@factonation.com

Published by Alpha Spare Parts Co., Ltd. under the Factonation brand.
**Samkoon** is a trademark of Shenzhen Samkoon Technology Co., Ltd.; this tool
is not affiliated with or endorsed by Samkoon.
