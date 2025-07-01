+---------------------------+                    +------------------------------------+
|        Người dùng         |                    |           Quản trị viên            |
+---------------------------+                    +------------------------------------+
          |                                                 |
          |--(Đăng ký tài khoản)                            |--(Thêm tài khoản)
          |                                                 |--(Sửa tài khoản)
          |                                                 |--(Xóa tài khoản)
          |                                                 |
          |                                                 |--(Thêm nhân vật)
          |                                                 |--(Sửa nhân vật)
          |                                                 |--(Xóa nhân vật)
          |                                                 |
          |                                                 |--(Thêm quái vật)
          |                                                 |--(Sửa quái vật)
          |                                                 |--(Xóa quái vật)
          |
          |--(Đăng nhập)
               |
               +--<<include>>-->(Chọn nhân vật)
                                   |
                                   +--<<include>>-->(Chơi game)
                                                      |
                                                      +--<<include>>-->(Tấn công quái vật)
                                                      |
                                                      +--<<include>>-->(Xem thông tin nhân vật)
                                                      |
                                                      +--<<include>>-->(Xem thông tin tài khoản)
