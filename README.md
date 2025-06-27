dpos_tetris
블록체인과 위임지분증명을 활용한 게임 메모리 변조 탐지가 구현된 멀티 테트리스 게임 *
기존 OSS-Team-8-Tetris 프로젝트를 기반으로 블록체인과 위임지분증명(DPoS) 기술을 접목하여 게임 메모리 변조를 탐지하는 기능을 추가했습니다.

주요 특징
기존 테트리스 게임 기능
Swing 기반 GUI 환경
Graphics 패키지를 활용한 블록과 게임 화면 구현
Hold와 Next 기능
방향키 기반 게임 조작
멀티플레이어 지원 (채팅, 상대방 화면 확인 가능)
새로 추가된 보안 기능
블록체인 시스템
게임 데이터의 무결성 및 투명성 보장
플레이어들의 게임 상태를 블록 형태로 저장
실시간 데이터 검증 시스템
위임지분증명(DPoS) 구현
현재 점수가 낮은 플레이어를 대표자로 선출
대표자의 데이터를 기준으로 다른 플레이어들의 데이터 비교
메모리 변조 시도 탐지 및 방지
시스템 구성
하부 시스템
User Interface (TetrisBoard)

게임 보드 및 전체 UI
홀드/넥스트 블록 패널
채팅 시스템
Game Logic

TetrisController: 블록 움직임 및 회전 제어
TetrisBlock: 블록 모양 구분
Block: 개별 블록 속성 정의
Network Communication

Serverframe: 서버 설정 및 관리
Clientframe: 클라이언트 설정 및 관리
ClientHandler: 클라이언트-서버 통신 처리
Blockchain Module

Blockchain: 블록체인 구조 관리
BC: 블록 데이터 관리 및 해시 계산
품질 지표
메모리 변조 탐지 성공률 향상
기존 시스템 대비 17.64% 메모리 사용량 증가
향후 발전 방향
실시간 메모리 변조 탐지 시스템 개발
다양한 무결성 알고리즘 적용 검토
참고
원본 프로젝트: https://github.com/jhe1014/OSS-Team-8-Tetris
