# FirstBlazor

## 1. CodeSpaces를 열어 주세요.
   ![image](https://github.com/user-attachments/assets/7c6afe65-1fdc-47e9-b987-236f99f82981)

  
Code > Codespaces > Create Codespaces on main 순으로 버튼을 클릭합니다.  
  
Codespaces 환경이 셋팅될 때까지 잠시 기다립니다.  
<br>  


## 2. .NET SDK 버전 확인
![image](https://github.com/user-attachments/assets/66ee0de9-63cd-4587-93ee-6376f892de7d)

위와 같은 터미널 창에 명령어를 입력하면 됩니다.  

먼저, 현재 설치된 .NET SDK의 버전을 확인합니다. 터미널(또는 명령 프롬프트)을 열고 아래 명령어를 입력하세요.

```dotnet --version```  
  
![image](https://github.com/user-attachments/assets/3b8f8100-4266-41a6-b3ed-b663daacbe2a)  

명령어를 입력해, .NET SDK가 설치되어 있음을 확인 가능합니다.  
<br>  


  
## 3.새로운 Blazor 프로젝트 생성
Blazor 프로젝트를 생성하려면 터미널에서 아래 명령어를 입력하세요. BlazorEx는 프로젝트 이름입니다. 다른 이름을 사용하고 싶다면 BlazorEx 대신 원하는 이름을 입력하면 됩니다.

```dotnet new blazor -o BlazorEx```
이 명령어는 BlazorEx라는 이름의 디렉토리를 생성하고, 그 안에 Blazor 프로젝트 파일들을 생성하는 명령어 입니다.
<br>  



## 4. 프로젝트 디렉토리로 이동
생성된 Blazor 프로젝트 디렉토리로 이동합니다. 아래 명령어를 사용하세요.
```cd BlazorEx```
이제 Blazor 프로젝트를 실행할 준비가 완료되었습니다.
<br>  



## 5. Blazor 프로젝트 실행
아래 명령어를 입력하여 Blazor 프로젝트를 실행합니다.
```dotnet run```
명령어가 성공적으로 실행되면, 터미널에 로컬 서버가 시작된다는 메시지가 나타납니다. 일반적으로 http://localhost:5000 또는 http://localhost:5001에서 애플리케이션을 확인할 수 있습니다.

브라우저에서 해당 URL로 이동하여 Blazor 애플리케이션을 미리보기 할 수 있습니다.



