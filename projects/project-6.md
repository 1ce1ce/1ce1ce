---
layout: project
type: project
image: images/huawei-square.jpg
title: Huawei ICT Competition Thailand 2018-2019
permalink: projects/project-huawei
# All dates must be YYYY-MM-DD format!
date: 2019-02-12
labels:
  - Competition
  - Huawei
summary: Huawei ICT Competition Thailand 2018-2019” เวทีการแข่งขันทักษะคอมพิวเตอร์ด้านเครือข่าย เพื่อเป็นตัวแทนเยาวชนไทยที่มีทักษะด้านระบบเครือข่ายไปแข่งขันบนเวทีระดับโลก
---

<img class="ui large centered rounded image" src="../images/huawei/huawei-1.jpg">

บริษัท หัวเว่ย เทคโนโลยี่  (ประเทศไทย) จำกัด  ร่วมกับบริษัท เออาร์ไอที จำกัด บริษัทชั้นนำเรื่องการฝึกอบรมและศูนย์สอบประกาศนียบัตรมาตรฐานสากล จัดทำโครงการ Huawei ICT Competition Thailand 2018-2019 เพื่อเฟ้นหาตัวแทนเยาวชนไทยไปแข่งขันในระดับเวทีโลก โดยมีวัตถุประสงค์เพื่อสร้างการพบปะการแลกเปลี่ยนประสบการณ์ใหม่ๆ ให้กับผู้เข้าร่วมการแข่งขัน และยังช่วยเพิ่มพูนทักษะด้านเครือข่าย (Network) ให้มีศักยภาพเพิ่มมากยิ่งขึ้น

สำหรับประกาศนียบัตรที่ใช้ในการแข่งขัน คือ HCNA (Huawei Certification Network Associate) เป็นประกาศนียบัตรรับรองความรู้และทักษะที่จำเป็นสำหรับการกำหนดค่าพื้นฐาน และการบำรุงรักษาระบบเครือข่ายขนาดเล็กไปจนถึงขนาดกลาง  ซึ่งหัวข้อการสอบ หลักสูตร HCNA ประกอบด้วย

* ระบบเครือข่ายขั้นพื้นฐาน

* เทคโนโลยีระบบเครือข่าย LAN , WAN , Routing

* การบริหารจัดการระบบเครือข่าย

* ความปลอดภัยของระบบเครือข่าย

* การจัดการ IP Address

* การวิเคราะห์และแก้ไขปัญหาระบบเครือข่ายขนาดเล็กถึงขนาดกลาง

<div class="ui small rounded images">
  <a href="../images/huawei/huawei-2.jpg">
    <img class="ui image" src="../images/huawei/huawei-2.jpg">
  </a>
  <a href="../images/huawei/huawei-3.jpg">
    <img class="ui image" src="../images/huawei/huawei-3.jpg">
  </a>
</div>


<div class="row">
  <div class="two wide column">
    <h3 class="ui left aligned header no-bottom">Awards</h3>
  </div>

  <div class="fourteen wide column no-bottom">
    {% for entry in site.data.bio.awards %}
    {% if entry.title == "Huawei" %}
    <div class="ui grid">
      <div class="twelve wide column no-bottom">
        <p class="ui no-bottom">
          <b>{{ entry.title }}</b>, {{ entry.awarder }}{% if entry.date %}, {{ entry.date }}{% endif %}
        </p>
        <p class="ui">{{ entry.summary }}</p>
      </div>
      <div class="four wide right aligned column no-bottom">
          <p class="ui no-bottom"><b>
            {% if entry.image %}
              <a class="ui button" href="../images/rewards/{{entry.image}}">
                Preview
              </a>
            {% endif %}
            <!-- {% include lightbox.html src="../images/molly.png" data="group" title="Sample Title" %} -->
          </b></p>
        </div>
    </div>
    {% endif %}
    {% endfor %}
  </div>
</div>

