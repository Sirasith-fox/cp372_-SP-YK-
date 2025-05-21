# CP372 Data Analytic Project : การวิเคราะห์ข้อมูลการจัดส่งพิซซ่า

---
จัดทำโดย

นายศิรสิทธิ์ พงศ์ศุภศักดิ์ 65102010127

นายโยเฮ คาโต้ 65102010422

**เสนอ : อาจารย์ ผศ.ดร. รัตน์ชัยนันท์ ธรรมสุจริต**

## บทนำ

โครงงานฉบับนี้เป็นส่วนหนึ่งของการเรียนการสอนในรายวิชา CP372 Data Analytics and Business Intelligence สำหรับนิสิตชั้นปีที่ 3 จัดทำขึ้นเพื่อเสริมสร้างความเข้าใจเกี่ยวกับการวิเคราะห์ข้อมูล รวมถึงการประยุกต์ใช้เครื่องมือด้าน Business Intelligence เพื่อช่วยในการตัดสินใจและพัฒนาศักยภาพทางธุรกิจ โดยใช้ซอฟต์แวร์ที่เกี่ยวข้อง เช่น Microsoft Excel และ Tableau เป็นเครื่องมือหลักในการวิเคราะห์และแสดงผลข้อมูล

คณะผู้จัดทำมีความตั้งใจให้โครงงานนี้เป็นแหล่งเรียนรู้ที่เป็นประโยชน์สำหรับผู้ที่สนใจในด้าน Data Analytics และ Business Intelligence ทั้งในระดับเริ่มต้นและระดับที่มีพื้นฐานแล้ว ทั้งนี้ หากมีข้อผิดพลาดประการใด ทางผู้จัดทำขอน้อมรับและขออภัยมา ณ โอกาสนี้

## สารบัญ
[Overview](#overview)

[Data Preparation](#2data-preparation)

[Exploratory Data Analysis](#3exploratory-data-analysis)

[In-Depth Analysis](#4-in-depth-analysis)

[Insights & Recommendations](#5-insights--recommendations)

## Overview

โครงงานนี้มุ่งเน้นการวิเคราะห์ข้อมูลการจัดส่งพิซซ่า โดยมีจุดประสงค์เพื่อให้นิสิตสามารถนำความรู้จากรายวิชา CP372 Data Analytics and Business Intelligence มาประยุกต์ใช้กับข้อมูลที่มีลักษณะใกล้เคียงกับสถานการณ์จริง ซึ่งช่วยพัฒนาและเพิ่มพูนทักษะในด้านการวิเคราะห์ข้อมูล การสื่อสารผลลัพธ์อย่างมีประสิทธิภาพ รวมถึงการเตรียมความพร้อมสำหรับการประยุกต์ใช้ในงานด้านธุรกิจในอนาคต

- ข้อมูลที่ใช้ (Data) : [https://www.kaggle.com/datasets/akshaygaikwad448/pizza-delivery-data-with-enhanced-features](https://www.kaggle.com/datasets/akshaygaikwad448/pizza-delivery-data-with-enhanced-features)

## Problem Statement

ยุคปัจจุบันมีการสั่งอาหารผ่าน delivery เพิ่มขึ้นอย่างมาก และการขนส่งก็มีระยะเวลาที่ต่างกัน พิซซ่าคือหนึ่งในอาหารที่มีการสั่ง delivery มาก ทำให้อยากทราบปัจจัยที่ส่งผลต่อระยะเวลาในการขนส่ง และพฤติกรรมการบริโภคพิซซ๋าของผู้บริโภค

## Business Objectives

- ลดเวลาเฉลี่ยในการจัดส่งลงอย่างน้อย 10%
- พัฒนาโมเดลการทำนายเวลาจัดส่งที่แม่นยำกว่าเดิมอย่างน้อย 15%
- เพิ่มความพึงพอใจของลูกค้า
- ลดต้นทุนการดำเนินงาน

## Key Stakeholders

- ร้านพิซซ่า - รู้

- ผู้บริโภค - 
  


---

# Tool

Colab : ใช้สำหรับทำความสะอาดและเตรียมข้อมูล (Data Cleaning & Preprocessing), สร้างฟิลด์ใหม่

Excel : ตรวจสอบและสำรวจข้อมูลเบื้องต้น วิเคราะห์เบื้องต้นก่อนนำข้อมูลเข้าสู่เครื่องมือ

Tableau : วิเคราะห์และนำเสนอข้อมูลผ่านกราฟและแผนภาพ เพื่อแสดงแนวโน้มและความสัมพันธ์ของข้อมูลได้ชัดเจนยิ่งขึ้น

---
## 2.Data Preparation

### 2.1 Data Cleaning (ทำความสะอาดข้อมูล)
![image](https://github.com/user-attachments/assets/4879eb5f-8684-44d6-b569-f09dc31cd6cc)


### 2.2 Feature Engineering (สร้างฟิลด์ใหม่)
![image](https://github.com/user-attachments/assets/f166e331-800c-4c03-9d8c-e62329a57b99)


---

## 3.Exploratory Data Analysis

![image](https://github.com/user-attachments/assets/b6f95834-73b3-4b14-990b-571010c545df)
![image](https://github.com/user-attachments/assets/548779a1-a351-47f7-bfcc-c1ffe9e3ec96)
![image](https://github.com/user-attachments/assets/57361765-3d16-446f-b30e-63bfc85a9841)
![image](https://github.com/user-attachments/assets/f6001b51-1cbf-45ac-873a-a51baf508572)
![image](https://github.com/user-attachments/assets/aa9683a3-3ae1-435d-a520-67f3e7a500ff)
![image](https://github.com/user-attachments/assets/66855961-8b2e-40dd-84a8-8798538ff9bb)
![image](https://github.com/user-attachments/assets/b4c81d3a-b51c-4a55-b01e-ec3031275af3)


---

## 4. In-Depth Analysis

### 4.1 จำนวน Boxes Shipped ส่งผลต่อยอดขายหรือไม่

![image](https://github.com/user-attachments/assets/7ccb8fce-286b-43a2-bf98-3bc5c7d76dfa)

## สรุป 

กราฟแสดงความสัมพันธ์ระหว่างจำนวนกล่องที่จัดส่ง (Boxes Shipped) กับยอดขาย (Amount) พบว่ามีความสัมพันธ์เชิงบวก ซึ่งหมายความว่ายิ่งจัดส่งมาก ยอดขายก็มีแนวโน้มเพิ่มขึ้น อย่างไรก็ตาม ผลิตภัณฑ์บางประเภทมีความสัมพันธ์ติดลบเล็กน้อย แสดงว่าไม่จำเป็นต้องจัดส่งมากเพื่อให้ยอดขายสูง 

### 4.2 ยอดการขายเปลี่ยยนแปลงอย่างไรตามช่วงเวลา

![image](https://github.com/user-attachments/assets/bee0b27a-9c02-4556-b515-cb02965b4a85)

### 📌สรุปกราฟยอดขายรายเดือนแยกตามประเทศ📌

Australia: ยอดขายสูงต้นปี (ม.ค.) แล้วลดลงละค่อยสูงขึ้นช่วงกลางปี

Canada: ยอดขายสูงกลางปี (พ.ค.) แล้วยอดขายลดลงต่อเนื่อง

India: ยอดขายสูงช่วงกลางปี (มิ.ย.–ก.ค.)

New Zealand: ยอดขายสูงมากขึ้นตลอดทุกเดือน พีคสูงสุดที่พ.ค.

UK: ยอดขายสูงในก.ค. หลังจากลดลงช่วงต้นปี

USA: คล้าย Canada ยอดขายสูงช่วงพ.ค. แล้วลดลง

สรุป: พ.ค.–ก.ค. เป็นช่วงที่หลายประเทศมียอดขายสูง อาจเกี่ยวข้องกับเทศกาลต่างๆในเดือนนั้น

## 5. Insights & Recommendations

### 5.1 ยอดขายในแต่ละเทศกาล
![image](https://github.com/user-attachments/assets/fdc8fc1b-4383-497c-88f6-965676380b5e)

- จากกราฟแสดงให้เห็นว่าเทศกาลวันวาเลนไทน์ไม่ใช่เทศกาลที่มียอดการขายมากที่สุด เทศกาลที่มียอดการขายมากที่สุดคือเทศกาลวันอีสเตอร์

### 5.2 จำนวน Boxes Shipped ส่งผลต่อยอดขายหรือไม่

![image](https://github.com/user-attachments/assets/09fe5916-c24e-4d09-9633-dfb53cef6163)

- ความสัมพันธ์โดยรวมเป็นบวกจึงทำให้จำนวน Boxes Shipped ที่มากขึ้นส่งผลให้ยอดการขายมีจำนวนเพิ่มขึ้นซึ่งมีค่า Correlation ประมาณ 0.1-0.2 เป็นความสัมพันธ์ที่อ่อนซึ่งอาจมีปัจจัยอื่นที่มีผลต่อยอดของการขาย

### 5.3 ยอดขายเฉลี่ยระหว่างสินค้าประเภท Dark Chocolate และสินค้าประเภทอื่น

![image](https://github.com/user-attachments/assets/58d7a814-b637-436e-9fd5-15313d78c255)

- จากกราฟแสดงให้เห็นว่าสินค้าประเภท Dark Chocolate มียอดขายเฉลี่ยมากกว่าสินค้าประเภทอื่น

## Recommendations

- โฟกัสการขายที่เทศกาลอีสเตอร์เป็นหลักควรเพิ่มสต็อกสินค้า เพราะเป็นช่วงที่มียอดการขายมากที่สุด
- ควรทำโปรโมชั่นในช่วงเทศกาลวาเลนไทน์เพื่อเพิ่มยอดการขายในช่วงเทศกาลนี้ให้มากขึ้น เช่น ทำสินค้าสำหรับคู่รัก
- ใช้ Dark Chocolate เป็นตัวหลักในการขาย และโปรโมทคู่กับสินค้าอื่นเพื่อลดปัญหาสินค้าค้างในสต็อก
- ใช้ข้อมูลลูกค้าในการวางแผนการจัดส่ง เพื่อลดปัญหาการจัดส่งเยอะ แต่ยอดการขายน้อย และลดต้นทุนในการจัดส่ง

## 6. Visualization ใน Tableau

- https://public.tableau.com/app/profile/nonthawat.deekham/viz/ProjectDataAnalytic_17477715549080/In-DepthAnalysisQuestion?publish=yes
  
- https://public.tableau.com/app/profile/nonthawat.deekham/viz/ProjectDataAnalytic_17477715549080/sheet12?publish=yes
  
- https://public.tableau.com/app/profile/nonthawat.deekham/viz/ProjectDataAnalytic_17477715549080/Detail?publish=yes













