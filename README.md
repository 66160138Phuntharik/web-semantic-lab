# web-semantic-lab
โปรเจคนี้เป็นส่วนหนึ่งของวิชา Web Frontend Development 

## รายละเอียด 
- การใช้ Semantic HTML 
- Form Validation 
- ARIA Labels 
## git command used in this lab 
- git config --global user.name "66160138Phuntharik" 
- git config --global user.email "66160138@go.buu.ac.th"
- git clone https://github.com/66160138Phuntharik/web-semantic-lab.git
- git add README.md
- git commit -m "comment"
- git push
- git checkout -b development 
- git add . 
- git commit -m "สร้างโครงสร้างโปรเจคเริ่มต้น"
- git checkout -b feature/home-page
- git add .
- git commit -m "สร้างโครงสร้างเริ่มต้นของโปรเจค"
- git add . 
- git commit -m "เพิ่ม header และ nav ในหน้าหลัก"   
- git add .
- git commit -m "เพิ่มส่วน main และ article ในหน้าหลัก"  
- git add .
- git commit -m "เพิ่ม aside และ footer ในหน้าหลัก"
- git checkout -b feature/contact
- git add .
- git commit -m "สร้างโครงสร้างพื้นฐานหน้าติดต่อ"
- git add .
- git commit -m "เพิ่มฟอร์มพื้นฐานในหน้าติดต่อ"
- git add .
- git commit -m "เพิ่ม validation ในฟอร์มติดต่อ" 
- git add .
- git commit -m "เพิ่ม ARIA labels ในฟอร์ม"
- git add .
- git commit -m "เพิ่ม ARIA landmarks ในการนําทาง" 
- git checkout development
- git add .
- git commit -m "เพิ่ม aside และ footer ในหน้าหลัก"  
- git add .
- git commit -m "เพิ่ม ARIA landmarks ในการนําทาง"
- git merge feature/home-page
- git merge feature/contact
- git add .
- git commit -m "เพิ่ม ARIA landmarks ในการนําทาง"
- git merge .\contact.html
- git add .\contact.html
- git commit -m "เพิ่ม ARIA landmarks ในการนําทาง"
- git merge feature/contact
- git push origin development