# KURRIER

실행

    roslaunch kurrier kurrier.launch

미션
    # 미션 0 시작점
    # 미션 1 차간간격1
    # 미션 2 정적장애물
    # 미션 3 gps음영1(공사장 장애물 회피)
    # 미션 3 gps음영1에서 우회전 후 조금 직진 한 포인트(여기부터 래티스 시작)
    # 미션 4 주차
    # 미션 5 끼어들기2
    # 미션 51 차간간격2        
    # 미션 6 gps음영2(장애물)
    # 미션 61 gps 음영구간 끝나는 곳
    # 미션 7 신호등
    # 미션 71 신호등 사거리 정지선 지점에 멈출수있게 그지점 3미터 전 지점
    # 미션 8 END지점 찾기

할 일
    
    cityhall_path 다시 따기
    
        두번째 슬램 구간 경로 살짝 왼쪽으로 붙어서 주행해서 다시 따기
        차간간격 할 때 앞 차가 카메라 가운데에 나오게
        주차구간에서는 주차장 가운데로 지나가게

    주차
    
    lattice
    
0823

    미션 노드 해당 미션 시작점 가까이가면 그번호로 바뀜 중복가능

0824

    미션 8 마무리

0825

    슬램 시작시 3초 정지후 슬램 키고 시작점 저장하고 다시 3초 대기 후 이동시작
    슬램 끄는거 완료
    SaveFile 압축 풀어서 모라이 런처 폴더 안에 모라이 런처 데이터 안에 SaveFile 폴더 대체 하면 됨

0826

    신호등 완료
    동적장애물 완료
    slam 위치 오차 해결


0828

    주차
    래티스 튜닝
    전부 합치기
