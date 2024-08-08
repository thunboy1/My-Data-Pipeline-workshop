# Automated Data Pipeline with Airflow workshop
ใน Workshop นี้ เราจะทำ Data Pipeline โดยใช้ Apache Airflow บน Google Cloud โดยจะใช้ข้อมูลชุดเดียวกันกับ [Workshop-Data Collection](https://github.com/thunboy1/My-Data-Collection-Workshop.git) ซึ่งรายละเอียดของ Data Pipeline ที่จะทำมีดังนี้
1) Extract ข้อมูล product, customer, transaction จาก Database แล้วนำมา merge กัน จากนั้นนำไป Load ไว้ใน Google Cloud Storage
2) Extract ข้อมูล conversion rate จาก API จากนั้น Transform และ Load ไว้ใน Google Cloud Storage
3) นำข้อมูล transaction มา merge กับ conversion rate และ Load ไว้ใน Google Cloud Storage
4) Upload ไฟล์ output ไปที่ GoogleBigQuery