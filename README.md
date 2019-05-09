# CnC
Aibril, Accuinsight, Cloud Z


# Hadoop 이란?

하둡 소프트웨어 라이브러리는 간단한 프로그래밍 모델을 사용하여 여러대의 컴퓨터 클러스터에서 대규모 데이터 세트를 분산 처리 할 수있게 해주는 자바기반의 오픈소스 프레임워크 이다.  

# 


kafka = 리얼타임?  
spark = 맵리듀스보다 속도가 빠르다.  
oozie = 명령 우선처리 관리  


# 과정

수집 -> 저장 -> 처리 및 정규화?  

수집 : apache flume  


source -> channel -> sink   
(데이터)   (버퍼)     (데이터 내보냄) 


# kafka

리얼타임 큐메시징 = 대용량 로그데이터를 가져다가 쓴다 = consumer

맵리듀스 = 데이터 파싱

# spark
메모리상에서 데이터 처리 = 속도가 빠름 (실시간성 처리에 좋은 오픈소스)



# 실습

1. 큐 -> 토픽관리 -> fruit, reulst
2. 콜렉터 -> 생성 


# 스트리밍 생성
kafka -> csv -> 



# 순서
kafka reader -> csv parser -> stringReplace filter -> clone fork -> sparkSQL
                                                                  -> kafka writer 
  
  
  
  
  

# Batch Pipeline
ETL - Extract Transform load
1. 
2. 
3. 



# Aibril 챗본

response = `Then respond with:`로 바로 이동

if assistant recognized = 컨디션을 다 체크하고 -> 다 체크됬으면 `Then respond with`로 이동.  (다 체크가 안됬으면 계속 이어서 실행)

