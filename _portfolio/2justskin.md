---
caption: #what displays in the portfolio grid:
  title: JUST SKIN
  subtitle: 화장품 쇼핑몰 사이트
  thumbnail: assets/img/portfolio/02-thumbnail.png
  
#what displays when the item is clicked:
title: JUST SKIN
subtitle: 화장품 쇼핑몰 사이트
image: assets/img/portfolio/02-thumbnail.png #main image, can be a link or a file in assets/img/portfolio
alt: image alt text

---

**mvc2**패턴 구조로 생성한 스킨케어 쇼핑몰 사이트입니다. 팀프로젝트에서 마이페이지 파트를 구현하였습니다. 
주요 기능으로는 **java dateformat함수를 이용한 주문한 화장품 유통기한 등록/ 확인**할 수 있도록 하였습니다. 
open한 화장품은 사용기간 확인하기 섹션에서 확인할 수 있으며, 버튼도 open완료로 변경하였습니다. 동일한 화장품을 1개 이상 구매하였을 경우, 테이블을 따로 생성하여 등록할 수 있도록 **sql trigger**이벤트를 사용해 보았습니다.  화장품 유통기한은 프로그레스바를 이용하여 동적인 효과를 주었습니다. 사용 완료한 화장품은 사용완료 버튼을 통해 삭제할 수 있도록 구현했습니다. 
**포인트,주문 내역 특정기간별, 선택한 기간별 조회**는 1,3,6개월 별 기간조회, 사용자가 선택하여 기간을 조회 할 수 있도록 하였습니다. 



{:.list-inline} 
- Date: 2021.06.10 ~ 2021.07.13
- Category: 쇼핑몰 
- 구현 파트 : 마이페이지 (화장품 유통기한 등록/확인하기, 찜목록, 주문 내역 기간별 조회 및 상세 조회 , 포인트 기간별 조회, 쿠폰 조회 ,회원정보 수정, 삭제)
- 개발환경 : Eclipse
- database & server : MYSQL, Tomcat Apach server , JDK
- 사용언어 : JAVA, JSP Servlet,html/css,javascript,jquery, ajax
- structure : mvc2 패턴을 이용한 쇼핑몰 구현
- 도메인 : http://itwillbs4.cafe24.com/ShoppingMall/Main.me
- 깃허브 : https://github.com/naeunkim1227/ShoppingMall





