# CodeIgniter4 Framework - Skeleton Application

Bản Skeleton phục vụ triển khai ứng dụng web bằng `CodeIgniter4 Framework`. Được đóng gói lại thành packages nhằm mục đích triển khai ứng dụng nhanh chóng

## Install

Chạy command sau để tiến hành cài đặt ứng dụng `nguyenanhung/codeigniter4-skeleton` và triển khai 1 dự án mới

```shell
composer create-project nguyenanhung/codeigniter4-skeleton [my-app-name]
```

Thay thế `[my-app-name]` bằng thư mục dự án mới cần triển khai, ví dụ: `my-website`

```shell
composer create-project nguyenanhung/codeigniter4-skeleton my-website
```

## Start Application
Triển khai ứng dụng nhanh với Docker được build sẵn

1. Build docker
```shell
docker-compose build
```
2. Khởi chạy ứng dụng
```shell
docker-compose up -d
```
3. Add url to hosts file
```shell
sudo vi /etc/hosts
127.0.0.1 app.codeigniter4.io
127.0.0.1 opcache.codeigniter4.io
```
4. Open Service in URL
```shell
http://app.codeigniter4.io/
```
5. Screenshot Page

![https://i.imgur.com/lno3ugO.jpg](https://i.imgur.com/lno3ugO.jpg)


## CHANGELOG

Xem chi tiết tại: 

## Liên hệ

| Name        | Email                | Skype            | Facebook      |
| ----------- | -------------------- | ---------------- | ------------- |
| Hung Nguyen | dev@nguyenanhung.com | nguyenanhung5891 | @nguyenanhung |

