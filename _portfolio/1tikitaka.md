---
caption: #what displays in the portfolio grid:
  title: TIKITAKA
  subtitle: chatting application
  thumbnail: assets/img/portfolio/05-thumbnail.jpg

#what displays when the item is clicked:
title: TIKITAKA
subtitle: chatting application 사이트
image: assets/img/portfolio/05-thumbnail.jpg
alt: ehlfks

---

react,spring boot, redis를 사용한 채팅 애플리케이션 입니다. 서버의 확장가능성, 안정성을 위하여 redis를 사용하였으며
Real time Messaging으로 인하여 빈번하게 변경되는 데이터를 자동으로 렌더링 해주는 리액트를 프론트엔드부분으로 사용하였습니다.
관리되는 데이터가 안정적이면서 확장성에 용이하며 Multi Thread환경으로 대용량 데이터 병렬처리에도 능숙한 Spring을 사용하였습니다.

구현한 파트는 채팅 비즈니스 로직, 1:1채팅, 실시간 알림 파트이며
websocket을 사용하여 redis에서 보내는 메세지를 실시간으로 받을 수 있도록 구현하였습니다.


{:.list-inline} 
- **Date**: 2021.11.15 ~ 2021.12.31
- **Category**: 채팅
- **구현 파트** : 채팅 비즈니스 로직, 1:1채팅, 실시간 알림
- **database & server** : MariaDB, Tomcat Apach server, gcp
- **skills** : react,spring boot,react
- **깃허브**
  + REACT :<a href="https://github.com/naeunkim1227/tikitaka-react>**Click!** </a> 
  + SPRING :<a href="https://github.com/naeunkim1227/tikitaka-spring>**Click!** </a>
