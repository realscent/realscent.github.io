---
title: "Vworld_API발급 및 적용"
date: 2024-10-27 02:24:00 +0900
categories: [Manual]
tags: [Vworld]
---


# -API Key

1.  특정 데이터를 사용하기위해 신청하는 Key  
    
2.  Vworld 의 API 발급  

	● https://www.vworld.kr/dev/v4api.do](https://www.vworld.kr/dev/v4api.do **[회원가입 -> 인증키발급]** 
      
    ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdsdSrrwkyKJPrkjzQNcO7kKkiljkatzi5YvqBV4J4LffBP5okwTByVYY4zbjlyNx7lTRhs3C0U_v6C1aPlCFtRA3m6H7GigyPGCRpVCWcbeFTxdiHVvbbmc6432tYBYKOk1IGCAqCFCboSMe3gyVOdJSYq?key=IfK6sJ0osQwjEhInWtvrwg)  
      
    
3.  동의- 서비스 정보는 임의로 작성  
      
    ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfnCm6niKRaC2QFOOR8EHQP5HonQ-Ae0FuA4bDiKWOYFitPsQxeZU0Hybwfvk84nwSFx2fPsPl5my_awF1VPisfTdUgAhtgkulVvmDkqFSQCRM48ppy6uPVOFgx6SDtfg1J4qmXif9agrA-GvyRSi9_cNXQ?key=IfK6sJ0osQwjEhInWtvrwg)  
      
      
      
    
4.  발급받은 API인증키 확인 및 활용
    

![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXdOGaJk5EasqiPJmVNIbOF-Q5F2Vif_Ej2N3jwrDWWd-0N4DTED_jEUlrcThmNsOfTTQ9llL3rlG5ejOASqFTQLUNxzheOilj2Ww7zkLL-QrOPcjEEl3RVrAZp0Ym6fy7YCSMKLvmFg9f3g-2ubpf1PpjEq?key=IfK6sJ0osQwjEhInWtvrwg)  
# -XYZ Tile  

1.  탐색기에서 **[XYZ Tiles 우클릭-새 연결… ]**
      
    ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXczNIJ1ZcprNQV62e8G7VRW-q57lthzlYqk8KOmszJDY-3ZIwMBC9qFUKZpGnZAOg-mHI51i7lwAEKVeYa6nPzyymPlTqRQv2kIf3OJK9bnjDCuaB_QRtPbCibMzp5hdKBkQLZ9rPRH6Dw0FM3KOypTxRbw?key=IfK6sJ0osQwjEhInWtvrwg)  
      
    
2.  이름, URL작성 (사용하고자하는 맵의 URL검색), 최저/최고 확대축소(레벨)  
    http://api.vworld.kr/req/wmts/1.0.0/발급받은API키입력/Satellite/{z}/{y}/{x}.jpeg  
    ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXe0jLhEEanP3IU4AmjKib4VhbeIT71thD1nwU8pDTwNoyO557HfnuELHVszKz9cA7CC1OaMKKf_rXBtLz4P_wdAdo-ronsLe7U5lD38-t4f7BDdFngjrwwKrr6tkzFgzPtVNklfEazZ3G3Lj3SzEbidMJo?key=IfK6sJ0osQwjEhInWtvrwg)  
      
      
    
3.  XYZ Tiles 레이어 생성완료
