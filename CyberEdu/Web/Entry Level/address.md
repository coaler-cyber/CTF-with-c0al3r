# Description
What is your address?
# Write up
Bước đầu, tôi đọc source của target:
<img width="1647" height="765" alt="image" src="https://github.com/user-attachments/assets/44b58038-0945-4746-880c-57fa84bab29a" />
<img width="1657" height="288" alt="image" src="https://github.com/user-attachments/assets/4f92c565-c20c-4062-b47f-d9b786324f97" />
Thấy có một comment ở cuối source với nội dung `<!-- /admin.php -->`
Tôi tiến hành truy cập /admin.php
<img width="1652" height="687" alt="image" src="https://github.com/user-attachments/assets/fb52f9f4-092c-4460-811b-e3e0dd4125ac" />
<img width="1650" height="342" alt="image" src="https://github.com/user-attachments/assets/80b635ba-54fa-4016-8137-a561866aea38" />
Thì thấy báo lỗi `You are not a local!`
Sau khi thử các header thì đều không phải là `Host` mà là  `X-Forwarded-For`
<img width="722" height="257" alt="image" src="https://github.com/user-attachments/assets/8e226cf2-ec17-4e26-8f12-df53e3208e44" />
Và giờ ta đã thấy được flag.
