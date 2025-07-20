# Aviutl2 양성소 한국지점
*Aviutl2는 Windows10 이상의 환경에서 동작합니다.*
- 함께 한글 패치가 완료된 AviUtl2를 세팅해 봅시다.
  <img width="1919" height="1020" alt="image" src="https://github.com/user-attachments/assets/64235015-c625-466f-b35e-965f895b4394" />

## 1. 💾 Aviutl2 다운로드
[Aviutl 공식 배포소](https://spring-fragrance.mints.ne.jp/aviutl/)에서 `AviUtl2betaX_setup.exe`를 다운로드받고, 실행합니다.
<img width="1071" height="387" alt="image" src="https://github.com/user-attachments/assets/e8fd7cee-4d2a-4302-8a9f-926ba3cdd89b" />

## 2. 필요한 플러그인들 설치
### 2-1. x264guiEx 설치
**유튜브, 니코동, 트위터 등등의 플랫폼에 맞추어 동영상을 인코딩할 수 있게 해 주는 플러그인**입니다. 꼭 필요하니 꼭 받읍시다.
[x264guiEx 공식 깃헙](https://github.com/rigaya/x264guiEx/releases/latest)에서 **AviUtl2_x264guiEx_x.xx_install.exe**를 다운받고, 실행합니다.
<img width="1272" height="715" alt="image" src="https://github.com/user-attachments/assets/cf4feb0e-d47a-4edf-98c1-d65905294394" />

### 2-2. 스크립트 설치와 한국어 패치
- 우리가 곧 설치하게 될 한국어 패치에는, Satsuki님의 Aviutl1용 스크립트들(제가 Aviutl2에서 정상 작동하는 것들만 추려서 넣어 두었습니다) 일부, [nea-c님의 Aviutl2용 스크립트들](https://github.com/nea-c/AviUtl-Scripts)의 번역이 함께 동봉되어 있습니다.
  **따라서, 우린 한국어 패치를 하며 스크립트도 함께 설치해 볼 것입니다.**

1. [이 버튼](https://github.com/EX3exp/Aviutl2-Korean-Support/releases/latest/download/Aviutl2-Korean-Support.zip)을 눌러 `Aviutl2-Korean-Support.zip`을 다운로드받습니다.
2. `Aviutl2-Korean-Support.zip`을 적절한 곳에 압축 해제합니다. 추후 이 내용물들을 **데이터 폴더**에 옮길 것입니다.
   <img width="588" height="318" alt="image" src="https://github.com/user-attachments/assets/f90f2e84-4901-4cce-86ff-684c9e53fa24" />

4. Aviutl2를 한 번도 실행한 적이 없다면, Aviutl2를 실행해 주세요. (실행 후 바로 꺼도 괜찮습니다.)
   후술할 **데이터 폴더**는 **Aviutl2의 최초 실행 시에** 생겨나기 때문입니다.
   
5. C드라이브로 가서 보기-> 표시를 클릭합니다.
   **숨김 항목**에 체크 표시해 주세요.
   그러면 반투명하게 생긴 `ProgramData`라는 폴더가 보입니다! 들어갑시다.
   
   <img width="354" height="301" alt="image" src="https://github.com/user-attachments/assets/0419c9ca-f434-46c2-86fb-59fea7413339" />
   <img width="237" height="42" alt="image" src="https://github.com/user-attachments/assets/f3e59ae2-50ff-48b1-a395-ed4270fe8d34" />

6. **`ProgramData/AviUtl2`에 `style.conf`파일을 넣어 주세요.**
   한국어에 맞게 미세하게 조정된 설정 파일입니다. (설정 파일들의 주석들도 번역되어 있습니다.)
   
   <img width="763" height="563" alt="image" src="https://github.com/user-attachments/assets/f646e8a6-c183-4c6e-b815-97be92f3093d" />

7.  **`Script`폴더 안에 `Aviutl2-Korean-Support/Script`에 있던 내용물들을 넣어 주세요.**
   `Script`폴더 내부는 이렇게 생겨야 합니다.
  <img width="846" height="672" alt="image" src="https://github.com/user-attachments/assets/30d40511-b3c1-4d54-b249-27c8d92fc931" />

8.  **`Language`폴더 안에 `한국어.aul2`를 넣어 주세요.**
   <img width="638" height="252" alt="image" src="https://github.com/user-attachments/assets/17621eef-8f72-4661-be74-150e41b28d86" />
   
9. Aviutl2를 실행합니다.
   Setting/Language에서 한국어를 선택해 주세요. 
   <img width="889" height="379" alt="image" src="https://github.com/user-attachments/assets/e2524301-719a-485a-a234-c9488cd783b0" />
   <img width="469" height="170" alt="image" src="https://github.com/user-attachments/assets/bef7a317-c1b2-4b40-9ad9-e9afe215957b" />


10. 한국어 패치 및 Aviutl2의 기초 세팅이 끝났습니다!
<img width="1918" height="1020" alt="image" src="https://github.com/user-attachments/assets/7a60883d-4695-475b-b768-9a95bfdd2353" />
