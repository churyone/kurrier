# 버전 내역
할 일

    최적화

남은 미션

    # 미션 4 동적장애물 && 주차

끝

    # 미션 0 시작점
    # 미션 1 차간간격1
    # 미션 2 정적장애물
    # 미션 3 gps음영1(공사장 장애물 회피)
    # 미션 5 끼어들기2
    # 미션 6 gps음영2(장애물)
    # 미션 7 신호등
    # 미션 8 END지점 찾기

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

0825

    슬램 시작시 3초 정지후 슬램 키고 시작점 저장하고 다시 3초 대기 후 이동시작
    슬램 끄는거 완료
    키는법 : kurrier.launch 이거만 키면됨
    SaveFile 압축 풀어서 모라이 런처 폴더 안에 모라이 런처 데이터 안에 SaveFile 폴더 대체 하면 됨