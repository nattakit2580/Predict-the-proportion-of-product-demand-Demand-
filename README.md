# Predict-the-proportion-of-product-demand-Demand-
ทำนายสัดส่วนความต้องการของผลิตภัณฑ์ (%Demand) ผ่านกระบวนการทางวิทยาศาสตร์ข้อมูล

1. คัดเลือกข้อมูลที่สนใจศึกษา คือสินค้าที่ถูกใช้กับรถประเภท SUV
2. สำรวจข้อมูล โดยใช้ line chart ดูลักษณะ trend ของสินค้าแต่ละประเภท
3. จัดการ missing value
4. transformation data ที่ถูกเก็บแบบตัวอักษรให้เป็นตัวเลข (Normalization)
(ควรทำ feature engineering ตรงไหนบ้าง)
5. ทำ feature selection
(ต้องปรับเรียบข้อมูลหรือไม่)
6. แบ่งชุดข้อมูล train / test
7. สร้าง data modeling เปรียบเทียบวิธี 
      - random forest
   - ANN
   -RNN
   -ARIMA  
8. วัดประสิทธิภาพ เปรียบเทียบแต่ละโมเดลด้วย MSE, RMSE และ R-Squared 
