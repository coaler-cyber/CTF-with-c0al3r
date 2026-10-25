# Description
Let's be fair, we all start with XOR, and we keep enjoying it.
# Write up
Đầu tiên kiểm tra source đề bài:
<img width="696" height="182" alt="image" src="https://github.com/user-attachments/assets/df47c373-3844-484a-8c2f-a9a33274a832" />
Challenge sử dụng phép XOR:
`chr(ord(a) ^ ord(b))`
Bến cạnh đó với hint ba byte đầu tiên là `0x00`
Ta có tính chất:
A XOR A = 0
Nên:
s1[0] = s2[0]
s1[1] = s2[1]
s1[2] = s2[2]
XOR ngược lại chuỗi ta có được flag
<img width="676" height="87" alt="image" src="https://github.com/user-attachments/assets/699ebe35-88c6-4667-939e-254e88fda515" />
