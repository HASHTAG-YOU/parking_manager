# parking_manager
글로벌SW공학

필요 데이터 

주차장 객체(이름 미정)

id = 위치
int seat_info (0(아무런 정보 없음), 1 = 장애인석 2= 임산부석 3 = 경차, 4 = 전기차)
 0000 = 아무런 정보 없음
 1000 = 장애인석
 0100 = 임산부석
 0010 = 경차
 0001 = 전기차
 1100 = 장애인 & 임산부
 1110 = 장애인 & 임산부 & 경차
 1111 = 장애인 & 임산부 & 경차 & 전기차

차량 객체(이름 미정) parking = 주차된 차량 정보 => 이것 역시 객체(0 = 비어있음, if 내 차량과 같은 정보면 노란색, 다르면 회색 x)
or
꼭 차량 객체가 아니더라도, 단순히 차량 uid(차량 번호) 만 받아도 ㄱㅊ을듯

ㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡㅡ

차량 객체(이름 미정)

string car_num 차량 번호   
int user_info (0(아무런 정보 없음), 1 = 장애인석 2= 임산부석 3 = 경차, 4 = 전기차)
 0000 = 아무런 정보 없음
 1000 = 장애인석
 0100 = 임산부석
 0010 = 경차
 0001 = 전기차
 1100 = 장애인 & 임산부
 1110 = 장애인 & 임산부 & 경차
 1111 = 장애인 & 임산부 & 경차 & 전기차
string owner 차량 주인

string 주차 위치 : null = 주차 x, b01 = b01에 주차되어있음

val parking time : null = 주차 x, 특정 값= 주차 시작 시간
=> 211027 아직 백엔드에서 처리할지 프론트엔드에서 처리할지 결정 x, 구현 배제
