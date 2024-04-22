# FileUploader
## 프로그램 설명 
```
해당 프로그램은 db, server에 파일을 자유롭게 업로드하고 다운받을 수 있도록한다.
db는 ORACLEDB, server의 os는 linux이다. 
해당 프로그램은 사용자 친화성을 높이기 위해 free hml template을 사용했음을 밝힌다. 
```
## 주요 코드
```
해당 프로그램은 oracle db, server와 연동하여 파일을 업로드 하고 다운 받는다. 
서버 배포를 위해 tomcat8.5를 사용했으며 eclipse Dynamic Web Project를 활용해 프로그램을 개발하였다. 
```
아래는 주요 코드이다. 
### Oracle
 
![image](https://github.com/auspicious0/FileUploader/assets/108572025/d5c70876-da17-4adc-9cbc-1033199933c7)

```
doPost를 활요해 서버에 업로드가 성공했을 땐 download 페이지로 가 upload 된 것을 확인할 수 있도록 하였다. 
```
![image](https://github.com/auspicious0/FileUploader/assets/108572025/a5a1dc49-0e44-42e7-bad4-f3614f5ac896)


 ![image](https://github.com/auspicious0/FileUploader/assets/108572025/7cf19e2a-1513-4f33-8bc8-6eda81c622e6)
```
 를 활용해 삽입 하였다.
```

 ![image](https://github.com/auspicious0/FileUploader/assets/108572025/2a1cd7e7-7d74-4cbd-a960-b3737b0bd85a)
```
check box로 체크된 항목을 download하기 위해 다음과 같은 과정을 거치었다.
```
 ![image](https://github.com/auspicious0/FileUploader/assets/108572025/f2e97979-e6ce-48bc-a0ac-267fa87e01e8)
```
또한 Blob를 활용해 파일을 다운받을 수 있도록 하였다. 
```

### server
```
server의 업로드는 ssh를 활용하였다. 따라서 아래 jar 파일을 사용하였다.
 ```
 ![image](https://github.com/auspicious0/FileUploader/assets/108572025/a3b49e78-52d1-4fe9-948d-632c70ed5f0a)

![image](https://github.com/auspicious0/FileUploader/assets/108572025/01f976ab-9d0b-44db-a819-fc00a6ecdb69)
```
다운로드도 그와 유사하기에 그냥 넘어가도록 한다.
```
## 실행화면

 ![image](https://github.com/auspicious0/FileUploader/assets/108572025/7c27ea50-7755-4f5a-ad6e-824bd8e27472)

 ![image](https://github.com/auspicious0/FileUploader/assets/108572025/8f37f1e5-c9a0-4c46-a968-50109d09b715)
![image](https://github.com/auspicious0/FileUploader/assets/108572025/60361976-5523-41f8-993f-c0396fa716cb)

 ![image](https://github.com/auspicious0/FileUploader/assets/108572025/b9bc27c6-894e-4ef7-ac62-920402bd6f3c)

 
