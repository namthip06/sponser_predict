# Sponsor Prediction
[Open in colap](https://colab.research.google.com/drive/1FIGjyhumlPi2tGhXjdmYPoSsAFTcz4qL?usp=sharing)

จัดทำโดย นางสาวน้ำทิพย์ ชอบธรรม คณะวิศวกรรม สาขาคอมพิวเตอร์ 66010424
โดยชิ้นงานนี้จัดทำขึ้นเพื่อเป็นผลงานประกอบการสมัคร LAB SAIG มีวัตถุประสงค์เพียง**เพื่อการศึกษาเท่านั้น**

โดยโมเดลนี้สร้างขึ้นโดยการใช้ Natural Language Processing เพื่อทำ Text Classification แยกระหว่างข้อความรีวิวที่ได้รับสปอนเซอร์(รีวิวติดแท็กโปรโมต, โฆษณา)และข้อความที่ไม่ได้รับสปอนเซอร์ 
*โดยผลที่ได้เป็นเพียงการแยกระหว่างข้อความที่ได้รับการสนับสนุน และข้อความที่ไม่ได้รับการสนันสนุนเท่านั้น ไม่ใช่การแยกระหว่างรีวิวจริงรีวิวปลอมแตกอย่างใด* 
ข้อมูลที่นำมาสอนโมเดลคือข้อความทวิตรีวิวสินค้าจำนวน 200 ข้อความ จากนั้นจึงนำมาสอนโดยการทำ Supervised Learning แปะป้ายแยกระหว่าง spon และ nospon จากนั้นเราจำนวนข้อมูลตัวอักษรไปทำ NLP และเทรนโมเดลโดยการใช้ Logistic Regression ผ่าน sklearn

## Examples
![ผล](https://github.com/namthip06/sponser_predict/assets/116744483/41cae875-2f48-4abe-95cc-0683e6272863)

## Usage
text

## Development process
![วิธี](https://github.com/namthip06/sponser_predict/assets/116744483/2a1ef3c0-9e9a-4417-9248-46a8e2b33452)

## Implementation Roadmap
image

## Acknowledgement and References
text
