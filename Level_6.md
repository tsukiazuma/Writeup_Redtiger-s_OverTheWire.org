## Người thực hiện: Trần Ngọc Nam
## Thời gian thực hiện: 7/5/2022

- Dựa vào gợi ý <code>Get the first user in table level6_users with status 1</code>. Ta sẽ dùng <code>ORDER BY</code> để tìm số lượng cột.
- Sau khi thử, ta có số cột là 5.
  
  ![CHESSE](img/26.png)

- Tiếp theo, ta sẽ dùng union để tim các cột dễ bị tấn công.<code>union select 1,2,3,4,5 from level6_users#</code>
  
  ![CHESSE](img/27.png)

- Nhưng không có kết quả trả về. Sau khi tìm hiểu, ta biết được thử thách này dùng 2 truy vấn lồng nhau.
- 