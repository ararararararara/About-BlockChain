# BlockChain
<img width="531" alt="1" src="https://user-images.githubusercontent.com/89236248/147848609-e23cb74d-577e-4f37-909b-6e54d0955106.png">
은행의 의존도를 벗어나고자 (탈중앙화) 비트코인 등장

<img width="358" alt="25" src="https://user-images.githubusercontent.com/89236248/147848616-64fe56f0-4a94-4ef5-99fb-55a6e152c928.png">
데이터 위변조를 효율적으로 막기 위해

<img width="500" alt="2" src="https://user-images.githubusercontent.com/89236248/147848621-46fbeb39-94d8-4635-943d-2c70e0570937.png">
블록체인은 P2P네트워크 구조로 이루어져 있다.

<img width="489" alt="3" src="https://user-images.githubusercontent.com/89236248/147848624-d6832034-dce6-4905-a374-168dca2e58b3.png">
클라이언트 서버와 달리 P2P형식으로 토렌트처럼 분산데이터 베이스 방식이다.
<img width="466" alt="4" src="https://user-images.githubusercontent.com/89236248/147848626-8d3de8d4-194e-458e-9b61-f5a52ef800ac.png">
모든 참여자(노드)들이 다 같은 데이터를 가지고 있음 => 탈중앙화
<img width="527" alt="5" src="https://user-images.githubusercontent.com/89236248/147848627-d711c6a4-e1e5-4256-adf7-6e508cbb4249.png">
블록체인은 블록들을 체인으로 연결된 형태....시간의 흐름에 따라 순차적으로 생성....이전블록은 더 전에 생성된것
<img width="516" alt="6" src="https://user-images.githubusercontent.com/89236248/147848630-20b60c69-91b8-4f9e-b64b-6e0058e662b8.png">
블록체인의 장점.... 모든 참여원들이 장부를 가지고 있기 때문에 해킹이 불가능

<img width="567" alt="7" src="https://user-images.githubusercontent.com/89236248/147848632-d68a7b45-1485-4207-8f2f-ab8d5d123138.png">
블록체인은 여러 기술에 활용 할 수 있다.
<img width="566" alt="8" src="https://user-images.githubusercontent.com/89236248/147848633-e29c0687-f6a0-4f9e-8508-8ab7fcf00c0f.png">
블록체인은 해쉬 함수를 사용한다.
<img width="560" alt="9" src="https://user-images.githubusercontent.com/89236248/147848634-f2f63be1-d766-4a2a-a327-230859af563d.png">
동작원리 : 블록의 해시값을 찾아야 새로운 블록을 추가 할 수 있음.. 목표한 해시값보다 작으면 충족
<img width="554" alt="10" src="https://user-images.githubusercontent.com/89236248/147848635-7fa19f67-3892-428d-bd20-0a4c52f39fc3.png">
제안 자격은 네트워크 마다 다른데  pow 는퍼즐의 답을 푼사람에게 보상을 주는 방식
<img width="863" alt="11" src="https://user-images.githubusercontent.com/89236248/147848636-1fa75aec-7f88-44ad-ab57-8708d4bd8888.png">
pos 는 가지고 있는 지분에 따라 보상을 주는 방식
<img width="844" alt="12" src="https://user-images.githubusercontent.com/89236248/147848655-9925ae45-cf52-469c-8cb0-096b3f5524b7.png">

<img width="537" alt="13" src="https://user-images.githubusercontent.com/89236248/147848643-644996a6-6ae5-40a7-a752-0a42004c7c53.png">
DPOS는 특정인원만 POS를 할수 있도록 위임한 것 .


<img width="832" alt="14" src="https://user-images.githubusercontent.com/89236248/147848644-ee5fddfd-7afb-4585-b8c0-f0d77e81b789.png">
<img width="872" alt="15" src="https://user-images.githubusercontent.com/89236248/147848645-87f93326-cea1-4d65-9450-59f10647f056.png">
Nonce : 블록헤더의 타겟보다 작게 나오는 Nonce를 구해야 함.
<img width="868" alt="16" src="https://user-images.githubusercontent.com/89236248/147848646-fadb64bd-4c40-492f-9492-e7bfdfefb7e0.png">
블록은 헤더 와 바디로 구성되어 있는데. 헤더는 바디를 설명하고 앞에 블록에 대한 정보를 저장한다.
<img width="380" alt="17" src="https://user-images.githubusercontent.com/89236248/147848647-563671ac-fc69-49a5-b069-d0a04783887b.png">
블록해시란 블록의 헤더정보를 모두 더해서 SHA256 값으로 변환한 값.

256=>256비트... 16진수로 표현하면 64자리로 표현됨
<img width="561" alt="18" src="https://user-images.githubusercontent.com/89236248/147848648-f6a20d25-57fe-461c-9397-f32ac7bfacc9.png">
헤더엔 해당 블록의 버전이 들어간다.


<img width="656" alt="19" src="https://user-images.githubusercontent.com/89236248/147848649-51b169ad-1933-4897-86fd-063247ffb43e.png">
이전 블록 해시는 이전 블록의 주소 값을 가르킨다.(포인터)
<img width="564" alt="20" src="https://user-images.githubusercontent.com/89236248/147848650-e5126a73-c34b-4b19-94f6-dcb82e3fcc73.png">
머클 루트란 : 바디에 저장된 거래 정보들을 해시 트리화 한 것

거래정보의 무결성을 검증...머클루트의 해시값을 생성하였기 때문에 블록의 무결성도 검증..
<img width="901" alt="21" src="https://user-images.githubusercontent.com/89236248/147848651-039fb8f8-1124-4cf7-9053-8363ca9a7e0e.png">
타임 : 블록의 생성시간 유닉스 기준일로 표시
<img width="878" alt="22" src="https://user-images.githubusercontent.com/89236248/147848652-1a3c2209-3040-4d2c-aee3-4ddccf677303.png">

<img width="885" alt="23" src="https://user-images.githubusercontent.com/89236248/147848653-8392c08b-29ed-4884-ac27-9217d356c65a.png">
<img width="880" alt="24" src="https://user-images.githubusercontent.com/89236248/147848654-f7d247a1-550a-4920-bc4d-ffc367009d40.png">
bits : 해시의 난이도 목표값

