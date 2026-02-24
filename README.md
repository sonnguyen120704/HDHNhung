Week 2:
# Biên dịch và cài đặt U-Boot cho BeagleBone Black

## Mục tiêu
Biên dịch thành công U-Boot cho bo mạch BeagleBone Black trên máy PC Ubuntu bằng phương pháp cross-compile.

## Môi trường
- Host OS: Ubuntu
- Target: BeagleBone Black (AM335x)
- Toolchain: arm-linux-gnueabihf-gcc
- Source: https://github.com/beagleboard/u-boot

## Các bước thực hiện
1. Cài đặt toolchain và các gói cần thiết
2. Clone mã nguồn U-Boot
3. Cấu hình U-Boot cho BeagleBone Black
4. Biên dịch U-Boot bằng cross-compiler

## Kết quả
- Biên dịch thành công U-Boot
- Tạo ra các file:
  - `MLO`
  - `u-boot.img`

## Minh chứng
![Build U-Boot](build_uboot.png)

## Kết luận
Quá trình biên dịch U-Boot cho BeagleBone Black trên Ubuntu hoàn tất và sẵn sàng để sử dụng cho bước boot hệ thống.
