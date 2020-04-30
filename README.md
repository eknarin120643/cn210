# รางานวิชา สถาปัตยกรรมคอมพิวเตอร์ [CN210]
## สรุปเนื้อหาที่เรียนในรายวิชา 
- ทุกคำสั่งมีขนาดเท่ากันคือ 32 บิต
- มีคำสั่ง 3 รูปเเบบ ได้แก่ R-Format, I-Format และJ-Format
op( opcode ) คือการบ่งบอกว่า ใช้คำสั่งรูปเเบบไหน  
### R - Format

    * โครงสร้าง | op  | rs | rt | rd  | shamt |func     
    * บิต  6,5,5,5,5,6  ตามลำดับ
  
    * ALU            func$rd,$rs,$st  

### I - Format
    * โครงสร้าง | op | rs | rt | value or offset  
    * บิต  6,5,5,16  ตามลำดับ
   
    * ALUi           alui $rt,$rs,value              
    
### J - format

    * โครงสร้าง | op | absolute address |
    * บิต 6,26 ตามลำดับ
   
     * Jump           j address
 
 ![br](https://i.stack.imgur.com/rdoQ1.png)

### อธิบาย CLIP  1 
คลิปนี้ อธิบายการทำงานของ j-format 
โดยการทำงานเริ่ม จากิฟไปทางขวา2 เเละตัด6บิทเเรกออก เปลี่ยนไปเป็น op ของjump 000010
[<br>**homework Clip-1**](https://www.youtube.com/watch?v=riAvroydGXE)

### อธิบาย CLIP  2

### อธิบาย CLIP  2

### อธิบาย CLIP  4

### อธิบาย CLIP  5

### อธิบาย CLIP  6

### อธิบาย CLIP  7
    
