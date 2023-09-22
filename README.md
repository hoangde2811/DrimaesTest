# cài đặt
    * Em sử dụng Flutter 3.10.6, em có up thư mục flutter3.10.6 trên onedrive https://5n25b7-my.sharepoint.com/:u:/g/personal/hhde_5n25b7_onmicrosoft_com/ERRasYXSwtBOoNym6Gm0J5gB9trCCpey7QUTGJuectWxNg?e=dyyMat

    * Trước khi chạy app hãy chạy dùm em câu lệnh này : dart run flutter_native_splash:create --flavors development,staging,production

### Cài đặt biến môi trường.
     * Tất cả biến môi trường trong /lib/util/build_config.dart.
     * có 4 biến môi trường cơ bản: development, staging, production and release.

###Để chạy ứng dụng có thể chạy theo câu lệnh:

      * Trước khi thay đổi môi trường chạy thì phải thay đổi biến "flavor" của BuildConfig trong /lib/main.dart 
## development: flutter run -t lib/main.dart --debug --flavor development

## staging: flutter run -t lib/main.dart --debug --flavor staging

## preprod: flutter run -t lib/main.dart --debug --flavor production

### Thử nghiệm
    * Thử ngiệm trên máy ảo android với API30 và hình ảnh thử nghiệm trong assets/hinh_thu_nghiem


