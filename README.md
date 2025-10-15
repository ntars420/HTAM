# 3D-Scanning
1. We first tried using a 3D scanner, and the first problem we found was that it requires a LiDAR device, which not all phones or tablets have.
2. After finding the right device, we scanned objects in our dorm room, but instead of getting a single object as we wanted, the scan captured the entire room.
3. So we borrowed a 3D scanner from our teacher. We used Revopoint paired with a dual-axis turntable.
  ![revopoint](https://github.com/user-attachments/assets/8aa4f8a3-3732-496b-8aa4-4ecc84384476)
![dual-axis turntable](https://github.com/user-attachments/assets/58c0925b-9080-492b-ab69-0a1b2fd0dfd7)
![advanced mode](https://github.com/user-attachments/assets/a01277ca-e79c-4530-bd30-5d2ca139c9c7)

5. At first, we scanned a pen, but since it was lying flat, it was hard to separate it from the tray.
6. Then we tried scanning a thermos cup, but it was too big, so we had to rotate the 3D scanner 90 degrees to capture it.
   ![638cc8ca1772eb9513280d6b9388dbcd](https://github.com/user-attachments/assets/956dbf62-c4f2-4e07-8448-fa11b36f3026)

7. We also found that the 3D scanner couldn’t clearly recognize the strap of the thermos, and it ended up generating multiple straps.
  <img width="1280" height="611" alt="failure case" src="https://github.com/user-attachments/assets/2235eb43-139d-4d75-bd34-5c8be4ab416b" />

8. Finally, we removed the strap and got a relatively good 3D model. However, the top and bottom that weren’t scanned were left open, turning it into an unsealed cavity, and we weren’t able to fix this problem.
<img width="1280" height="611" alt="image" src="https://github.com/user-attachments/assets/2dec5a8a-3658-4066-ae89-e6bcdf51c87f" />

p.s.Later, we needed to 3D print it, so I used a meshmixer to fill this hole. The stl file of our scanned model can be viewed in the file
