# รางานวิชา สถาปัตยกรรมคอมพิวเตอร์ [CN210]
## สรุปเนื้อหาที่เรียนในรายวิชา 
- ทุกคำสั่งมีขนาดเท่ากันคือ 32 บิต
- มีคำสั่ง 3 รูปเเบบ ได้แก่ R-Format, I-Format และJ-Format
op( opcode ) คือการบ่งบอกว่า ใช้คำสั่งรูปเเบบไหน  
### R - Format

  โครงสร้าง | op  | rs | rt | rd  | shamt |func     
  จำนวนบิต  6,5,5,5,5,6  ตามลำดับ
  
    * ALU            func$rd,$rs,$st  
### I - Format
   โครงสร้าง | op | rs | rt | value or offset  
   จำนวนบิต  6,5,5,16  ตามลำดับ
   
    * ALUi           alui $rt,$rs,value              
    
### J - format

   โครงสร้าง | op | absolute address |
   จำนวนบิต 6,26 ตามลำดับ
   
     * Jump           j address
