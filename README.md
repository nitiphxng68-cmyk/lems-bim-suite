# lem's BIM Suite for SketchUp (Releases & Auto-Update Distribution)

คลังสำหรับดาวน์โหลดและอัปเดตออนไลน์อัตโนมัติของปลั๊กอิน SketchUp ตระกูล **`lem's ...`** (Minimalist Small-BIM Edition):

- **`lem's tags`** (ล่าสุด: `v2.2.0`) — จัดการ Tags, Auto-Prefix ตาม Group, Rebar Layer Generator (`04_Rebar`), Paint & Alt-Sample Tool, Outliner Sync
- **`lem's management`** (ล่าสุด: `v2.3.0`) — Project Browser, Revit Properties, View Templates, Interactive Graphic Grid & Level Setup, Workplane & 3D Section Box

---

## ดาวน์โหลดติดตั้งครั้งแรก (`.rbz`)

เข้าไปที่หน้า **[Releases (Latest)](https://github.com/nitiphxng68-cmyk/lems-bim-suite/releases/latest)** แล้วดาวน์โหลดไฟล์ทั้ง 2 ตัว:
1. `lems_tags_v2.2.0.rbz`
2. `lems_management_v2.3.0.rbz`

จากนั้นเปิด SketchUp ไปที่ **Extensions > Extension Manager > Install Extension...** และติดตั้งทั้ง 2 ไฟล์

---

## การอัปเดตออนไลน์อัตโนมัติจากใน SketchUp

ตั้งแต่เวอร์ชัน `lem's tags v2.2.0` และ `lem's management v2.3.0` เป็นต้นไป ปลั๊กอินตั้งค่า URL อัปเดตชี้มายัง Manifest นี้ไว้ให้ล่วงหน้าแล้ว:

```text
https://raw.githubusercontent.com/nitiphxng68-cmyk/lems-bim-suite/main/update_manifest.json
```

หากมีเวอร์ชันใหม่ออกมา ปลั๊กอินจะแสดง **จุดแจ้งเตือนที่ปุ่ม Updater มุมขวาบนของหน้าต่าง** ให้กด **Check / Install vX.Y.Z** เพื่อดาวน์โหลด `.rbz` ใหม่ ติดตั้งทับ และ Hot-Reload หน้าต่างทันทีโดยไม่ต้องลบตัวเก่าทิ้งครับ
