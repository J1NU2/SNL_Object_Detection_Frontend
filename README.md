# 😊 SNL_Object_Detection

사물인식 머신러닝을 이용한 SNL 연예인 닮은 꼴 찾기

<br/>

# 📃 프로젝트 정보

### 1. 제작기간

> 2022.05.18 ~ 2022.05.25

### 2. 참여 인원

> |                    Name                    |  Position   |
> | :----------------------------------------: | :---------: |
> | [김성호](https://github.com/Kim-sung-ho) | Back, Front |
> |   [김주훈](https://github.com/joohuun)    | Back, Front |
> |     [박진우](https://github.com/J1NU2)     | Back, Front |
> |    [최희원](https://github.com/wonbbnote)     | Back, Front |

### 3. 역할 분담

> - 김성호 : 이미지 업로드 기능, 이미지 등록 및 결과 페이지
> - 김주훈 : 이미지 업로드 기능, AI 사물 인식 기능(CNN Modeling)
> - 박진우 : 회원가입 및 로그인
> - 최희원 : 이미지 등록 및 이미지 결과 저장 기능

<br/>

# 📚 기술 스택

### Frontend

> HTML  
> CSS  
> Javascript

<br/>

# 🔑 핵심기능

### 1. 닮은 꼴 연예인 찾기

> 사용자가 이미지를 등록하면 CNN 기반 학습 모델이 실행되고  
> 이미지와 닮은 꼴의 SNL 연예인의 이름이 출력되면서 결과값이 DB에 저장됩니다.  
> [코드 보러가기](https://github.com/J1NU2/SNL_Object_Detection_Backend/blob/5b361eb3305054dbfdaaf6bc11290f733b8823fe/main/result.py#L53)

### 2. Flask Blueprint를 이용한 API 모듈화

> 여러 명이 개발 시 편의성을 위해 Backend 파트를 분류하여 개발을 진행했습니다.  
> [코드 보러가기](https://github.com/J1NU2/SNL_Object_Detection_Backend/blob/5b361eb3305054dbfdaaf6bc11290f733b8823fe/main/__init__.py#L1)

<br/>

# 📕 기타 자료

### 1. 기획문서

> [SNL_Object_Detection - Notion](https://www.notion.so/cd8693be56434d59964d8086955e0fdf)

### 2. CNN 기반 연예인 분류 AI 학습 모델

> [CNN-based-Celebrity-Classification-AI-Service-Using-Transfer-Learning - Github](https://github.com/ndb796/CNN-based-Celebrity-Classification-AI-Service-Using-Transfer-Learning)

### 3. 발표영상

<table>
  <tbody>
    <tr>
      <td>
        <p align="center"> 22.05.25 발표 </p>
        <a href="https://drive.google.com/file/d/1XfmgB4r66NJXfAwXzh3Niu33xkS_y2O-/view" title="SNL_Object_Detection 발표">
          <img align="center" src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/42901488-607e-46c8-8b80-fea410b5afeb/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220823%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220823T092648Z&X-Amz-Expires=86400&X-Amz-Signature=ce9af9a621f197d69b031c8e7f135f3f18ab0373ec1e1949c1ad75fd0fa57796&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" width="300" >
        </a>
      </td>
    </tr>
  </tbody>
</table>
