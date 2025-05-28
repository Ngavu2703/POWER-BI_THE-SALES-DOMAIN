# POWER-BI_THE-SALES-DOMAIN <br>
Doanh nghiệp kinh doanh bán lẻ mặt hàng đa dạng, phân phối qua nhiều kênh online và offline trong khoảng thời gian từ 01/01/2016 đến 31/12/2018.<br>
Từ dataset, tôi thực hiện xây dựng dashboard bằng Power BI để đánh giá tổng quan, phân tích tìm ra cơ hội cải thiện cho doanh nghiệp.<br>
## I. INTRODUCTION <br>
Dataset gồm 4 bảng dữ liệu:<br>
Bảng Fact: Salesmanagement<br>
Thông tin các giao dịch của doanh nghiệp, gồm 9 trường thông tin và 72743 records.<br>
<img width="713" alt="t1" src="https://github.com/user-attachments/assets/3e934605-d908-4eef-ad2a-c7b8ea551d67" /><br>
Bảng Dimension: Region<br>
Thông tin về quốc gia và khu vực, gồm 2 trường và 14 records<br>
<img width="714" alt="t2" src="https://github.com/user-attachments/assets/01d17c0d-3e76-43dd-b9ac-a31637e6bdd8" /><br>
Bảng Dimension: SalesManagers<br>
Thông tin về quốc gia và SM quản lý khu vực, gồm 2 trường và 14 records <br>
<img width="715" alt="t3 1" src="https://github.com/user-attachments/assets/37f096b2-cd34-41be-8ebd-a0901d537c1d" /><br>
Bảng Dimension: Thông tin về ngày tháng, gồm 1 trường, 1461 records<br>
<img width="713" alt="t4" src="https://github.com/user-attachments/assets/40d4e8f3-f5b2-4934-8f17-2a2bd1b8fcdc" /><br>
II. DESIGN THINKING<br>
1. Empathize<br>
   <img width="749" alt="e1" src="https://github.com/user-attachments/assets/87391475-9dc2-4ba2-8079-1078ad5b67b8" /><br>
<img width="395" alt="e2 1" src="https://github.com/user-attachments/assets/d02dbf83-e945-4e28-b86b-6bcf4a975aea" /><br>

3. Define POV<br>
III. VISUALAZATION<br>
1. Overview sales<br>
   <img width="589" alt="o1" src="https://github.com/user-attachments/assets/89222bd5-d2e5-456b-af3b-9bb2cee8e4ac" /><br>

2. Revenue trends<br>
   <img width="586" alt="o2" src="https://github.com/user-attachments/assets/bee3b7a9-1d48-489b-99ef-c1b0119bb08f" /><br>

3. Product performance<br>
   <img width="592" alt="o3" src="https://github.com/user-attachments/assets/12d96d8b-f3ea-45b3-a1a5-8e0b497bb326" /><br>

4. Channel analysis<br>
   <img width="587" alt="o4" src="https://github.com/user-attachments/assets/04bc1e6c-6030-4680-8aaa-fc11c7c0b586" /><br>

5. Sales manager<br>
  <img width="590" alt="o5" src="https://github.com/user-attachments/assets/869b79f9-40ca-4788-a658-97f345463a41" /><br>

6. Regional performance<br>
<img width="597" alt="o6" src="https://github.com/user-attachments/assets/65863dcc-ce79-4e17-b0f8-ae0360b687bd" /><br>

IV. INSIGHT AND RECOMMEND<br>
1.Overview sales<br>
-Ta thấy:<br>
+Doanh thu, chi phí và lợi nhuận gộp đều tăng đều qua từng năm (2016 - 2018).<br>
+Giá bán trung bình (Avg Selling Price) tăng mạnh từ 2016 đến 2017 (tăng 12,61), sau đó giảm nhẹ năm 2018 (giảm 2,52).<br>
+Tổng sản phẩm (Total Quantity) tăng từ ~4 triệu lên ~5 triệu cho thấy sự mở rộng sản xuất và tiêu thụ sản phẩm.<br>
-Dựa vào doanh thu theo dòng sản phẩm, ta thấy Video Games là sản phẩm chiến lược luôn có doanh thu cao nhất qua các năm, xu hướng tăng ổn định. Dòng sản phẩm Mobile có tiềm năng lớn. <br>
-Dựa vào phân tích theo khu vực địa lý: Doanh thu đến chủ yếu từ Bắc Mỹ, Châu Âu và một phần Châu Á. Không có doanh thu đáng kể tại Úc, Châu Phi, và Đông Nam Á.<br>
2.Revenue trends<br>
-Doanh thu tăng đều qua từng năm, tăng trưởng YoY giảm nhẹ từ 2017 đến 2018.<br>
-Doanh thu sản phẩm theo quý qua các năm ta thấy:<br>
+Qúy 1: Video Games (luôn nằm top doanh thu cao nhất)<br>
+Qúy 2: Video Games và Mobile<br>
+Qúy 3: Mobile, Computer<br>
+Qúy 4: Video Games, Mobile, Home và Kitchen → Mua sắm cuối năm, lễ hội, đồ dùng gia đình. Chiến lược sales cuối năm cần đẩy mạnh mẽ.<br>
-Ta thấy: Video Game luôn là sản phẩm có doanh thu cao nhất. Video Games là ngành mũi nhọn, cần được ưu tiên đầu tư và mở rộng. Qúy 2 và Qúy 3 là mùa bán hàng mạnh – cần tập trung marketing, ra mắt sản phẩm chính trong thời gian này. Qúy 4 có tiềm năng cao nhưng không ổn định, do đó nên tận dụng dịp cuối năm như lễ hội, khuyến mãi để đẩy doanh thu bằng các chương trình giảm giá, khuyến mại hấp dẫn.<br>
3.Product<br>
-Phân tích Doanh Thu Theo Dòng Sản Phẩm (Product Line)<br>
+ Video Games: Là dòng sản phẩm mang lại doanh thu cao nhất trong cả ba năm liên tiếp, từ khoảng 104,88 triệu năm 2016 lên đến 168,85 triệu vào năm 2018. Tăng trưởng mạnh và ổn định, đóng vai trò chủ lực.<br>
+ Mobile: Đứng thứ hai sau Video Games về doanh thu. Tăng từ khoảng 85,55 triệu lên 128,98 triệu (2018). Tăng trưởng ổn định, là mảng tiềm năng và đáng duy trì đầu tư.<br>
+ Computer: Tăng từ 65,65 triệu lên 80,77 triệu. Tăng nhẹ, nhưng đang bị các dòng sản phẩm khác vượt mặt về tốc độ phát triển.<br>
+ Home và Kitchen: Mức tăng trưởng nhanh nhất về tỷ lệ: từ 22,11 triệu lên đến 43,45 triệu (2018). Tiềm năng mở rộng, tăng cường sản xuất.<br>
+ Books: Doanh thu giảm rõ rệt qua từng năm: từ 4,55 triệu xuống 2,37 triệu (2018). Doanh thu giảm liên tục, cần xem xét lại chiến lược hoặc loại bỏ khỏi danh mục nếu không tạo lợi nhuận.<br>
-Nhận thấy: <br>
+Video Games và Mobile là hai product line chủ lực, chiếm trên 70% doanh thu mỗi năm.<br>
+Home và Kitchen có tăng trưởng nhanh theo tỷ lệ, đây là cơ hội mở rộng.<br>
+Books đang suy giảm liên tục, cần xem xét loại bỏ.<br>
4. Channel<br>
-Doanh thu từ kênh Web (online) là khoảng 890,27 triệu chiếm ~83% tổng doanh thu.<br>
-Lợi nhuận gộp từ Web là ~0,38 tỷ, vượt xa các kênh khác như Sales Visit, Telephone, Email, Fax.<br>
-Kênh Web xuất hiện ở hầu hết các khu vực địa lý: Bắc Mỹ, Châu Âu, Châu Á, Châu Đại Dương, Châu Phi.<br>
-Nhận thấy: Web: Đóng góp doanh thu và lợi nhuận cao nhất, cần tập trung và triển. Tuy nhiên cũng cân nhắc mở rộng những kênh tiềm năng khác như Sales visit, Telephone.<br>
5. Sales Manager<br>
-Emma Smith phụ trách khu vực United States là nhân viên xuất sắc nhất liên tục trong 3 năm, vượt trội về doanh thu, lợi nhuận và sản lượng.<br>
-Pablo Ramirez (phụ trách Japan) và Sophia Evans (Canada) thường xuyên nằm trong top 3, nhưng cách biệt so với Emma khá xa.<br>
-Chiến lược:<br>
+ Cần khai thác và nhân rộng mô hình nhân viên xuất sắc như Emma Smith.<br>
+ Nâng cao hiệu suất nhóm và tạo hệ thống khen thưởng.<br>
+ Rà soát phân chia khu vực/danh mục sản phẩm của các sales manager.<br>
6. Region<br>
-Europe: Là vùng có doanh thu cao nhất (398,8 triệu), chiếm phần lớn thị phần, có số lượng bán ra cao nhất (~5 triệu sản phẩm), gía bán trung bình sản phẩm 84,63. <br>
-North America: Đứng thứ 2 với 304.9 triệu, số lượng gần 4 triệu sản phẩm. gía bán trung bình sản phẩm (77,6).<br>
-Asia: Vị trí thứ 3, với tổng doanh thu 228,3 triệu. Mức giá trung bình ổn định (80,5).<br>
-Latin America: Mặc dù có doanh thu chỉ hơn 99,14 triệu nhưng lại có giá trị trung bình/đơn vị cao nhất (87.7), cho thấy đây là thị trường có biên lợi nhuận tốt.<br>
-Oceania: Thị trường nhỏ nhất với doanh thu 37,5 triệu. Giá trung bình thấp nhất (72,3).<br>
-Nhận thấy:
+ Châu Âu là thị trường chủ lực cần tiếp tục duy trì đầu tư và tối ưu hóa lợi nhuận qua các chiến lược bán cao cấp.<br>
+ Bắc Mỹ có quy mô lớn nhưng giá trị đơn hàng còn thấp, cần tập trung nâng cao doanh thu trung bình thông qua đa dạng hóa sản phẩm.<br>
+ Châu Á là thị trường đang phát triển giàu tiềm năng, nên được mở rộng mạnh mẽ với các sản phẩm và chiến lược phù hợp địa phương.<br>
+ Latin America và Oceania tuy có doanh thu thấp nhưng mang đặc điểm lợi nhuận cao hoặc linh hoạt, phù hợp để khai thác thị trường ngách và thử nghiệm mô hình mới.<br>
