# 버전 내역
남은 미션

    # 미션 3 gps음영1(공사장 장애물 회피)
    # 미션 4 동적장애물(주차)
    # 미션 6 gps음영2(장애물)

끝

    # 미션 0 시작점
    # 미션 1 차간간격1
    # 미션 2 정적장애물
    # 미션 5 끼어들기2
    # 미션 7 신호등
    # 미션 8 END지점 찾기

할 일

    slam 끄는거
    최적화
    파라미터들 mission노드 안으로 이동
    check_finish 미션 8번 받아서 작동하게 수정

0823
    미션 노드 해당 미션 시작점 가까이가면 그번호로 바뀜 중복가능

0824
    # 미션 4 동적장애물
    # 미션 41 주차
    두개가 다르면 안됨
    미션 8 마무리 했음

    키는법 : kurrier.launch 키고 옆에 kurrierLidar.launch 키면 됨
    kurrier.launch 이거 열어서 output="screen" 이 옵션 달아주면 디버깅 편함
    kurrierLidar.launch 얘가 SLAM 실행시킴

    