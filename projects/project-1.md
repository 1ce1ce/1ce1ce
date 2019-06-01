---
layout: project
type: project
image: images/vcaption-square.png
title: Online Caption Editor
permalink: projects/vcaption-editor
# All dates must be YYYY-MM-DD format!
date: 2018-07-01
labels:
  - Vue.js
  - MongoDB
  - Javaascript
  - Express Framework
  - Meterial UI
  - Libjass
summary: เว็บแอพพลิเคชั่นขึ้นมาจัดการคำบรรยาย โดยรองรับไฟล์คำบรรยายในรูปแบบ .ASS และเพิ่มความรวดเร็วในการทำงานด้วยการทำงานแบบร่วมกัน
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

โครงงานวิจัยระดับปริญญาตรีเรื่อง ระบบจัดการคำบรรยายออนไลน์ (Captioning Editor Online) สาขาวิชาเทคโนโลยีสารสนเทศ คณะวิทยาศาสตร์และเทคโนโลยี มหาวิทยาลัยเทคโนโลยีราชมงคลธัญบุรี จัดทำโดยมีวัตถุประสงค์เพื่อแก้ไขปัญหาการจัดทำ และจัดการคำบรรยายที่ยุ่งยาก ให้ง่ายดายมากยิ่งขึ้น ไม่จำเป็นต้องเปิดโปรแกรมเพื่อเป็นการลดการทรัพยากรคอมพิวเตอร์ และยังช่วยอำนวยความสะดวกในการเช้างานที่สามารถทำได้ทุกที่ทุกเวลา และทำงานร่วมกับผู้อื่นได้ส่งผลให้การดำเนินงานมีความรวดเร็วมากยิ่งขึ้น โดยทางผู้พัฒนาได้จัดทำระบบจัดการคำบรรยายออนไลน์เป็นรูปแบบของ Single page application ช่วยให้ไม่ต้องรอโหลดหน้าเว็บเวลาใช้งานฟังก์ชั่นต่าง ๆ เช่น การสมัครสมาชิก การเข้าสู่ระบบ การสร้างโปรเจ็ค การเลือกรายการโปรเจ็ค การจัดการ Dialogของคำบรรยาย การจัดการ style dialog การแบ่งปันโปรเจ็ค การเผยแพร่ และรับชมวิดีโอผลงานผ่านตัวเล่นวิดีโอของระบบจัดการคำบรรยายออนไลน์ รวมถึงการเก็บยอดจำนวนผู้ชม เป็นต้น นอกจากนี้ระบบยังมีความปลอดภัย และความเป็นส่วนตัวด้วยการกำหนดสิทธิ์การเข้าใช้งานด้วยตัวผู้ใช้ที่เป็นเจ้าของผลงานเพื่อความความปลอดภัย และรักษาความลับของผลงาน

```js
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



