
## :one: Chuẩn bị
- Tạo mội trường python

 ```c
 $ python -m venv venv .\venv\Scripts\activate 
  ```
 :warning: Tạo file `.gitignore` và điền tên thư mục môi trường python vào file vừa tạo 
## :two: Tiến hành cài đặt
-  **Bước 1**: Cài Fastapi và Uvicorn bằng pip:
 ```c
 $ pip install fastapi pip install uvicorn 
  ``` 
  - **Bước 2**: Code một số tính request đơn giản tại file **main.py**.
  - **Bước 3**: Chạy server bằng lệnh sau:
  ```c
  $ uvicorn main:app --reload # Mini_server
  ```