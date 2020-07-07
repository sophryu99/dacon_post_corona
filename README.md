# dacon_post_corona
포스트 코로나 [데이터 시각화 경진대회](https://dacon.io/competitions/official/235618/overview/) 

**이 깃헙 페이지에서 직접 파일 수정하지 않기!!**



## 파일당 Column 설명

**adstrd_master :** 
adstrd_code 행정동코드
adstrd_nm 행정동명
brtc_nm 시도명
signgu_nm 시군구명



**fpopl : 행정동별 유동인구 데이터**
base_ymd : 기준년월일
tmzon_se_code : 24시간대 구분코드
sexdstn_se_code : 성별구분코드(M남성 F여성)
agrde_se_code : 5세단위 연령대 구분코드(age_00:0세~9세, age_70 : 70세이상)
adstrd_code :  행정동코드
popltn_cascnt : 인구수



**card : **
receipt_dttm : 카드회사가 카드사용내역을 접수한 일자 
adstrd_code : 가맹점 위치 기준 행정동 코드
adstrd_nm : 가맹점 위치 기준 행정동명
mrhst_induty_cl_code : 가맹점 업종코드
mrhst_induty_cl_nm : 가맹점 업종명
selng_cascnt : 매출발생건수
salamt : 매출발생금액



**delivery** : 
SERIAL_NUMBER : 순번
PROCESS_DT : 처리일시
DLVR_RQESTER_ID : 배달요청업체 ID
DLVR_RQESTER_STTUS_VALUE : 배달요청상태값 (1:완료, 2:취소, 3:사고, 4:문의)
DLVR_RCEPT_CMPNY_ID : 배달접수회사 ID
DLVR_STORE_ID : 배달상점ID
DLVR_STORE_INDUTY_NM :배달상점 업종이름
DLVR_STORE_LEGALDONG _CODE : 배달상점 주소 법정동코드
DLVR_STORE_SIDO : 배달상점 주소 법정동 시도명
DLVR_STORE_SIGUNGU : 배달상점 주소 법정동 시군구명
DLVR_STORE_DONG : 배달상점 주소 법정동 읍면동명
DLVR_STORE_RI : 배달상점 주소 법정동 리명
DLVR_STORE_ADSTRD_CODE : 배달상점 주소 행정동 코드
DLVR_STORE_RDNMADR_CODE : 배달상점주소 도로명주소 코드
DLVR_DSTN_LEGALDONG_CODE : 배달목적지 주소 법정동코드
DLVR_DSTN_SIDO : 배달목적지 주소 법정동 시도명
DLVR_DSTN_SIGUNGU : 배달목적지 주소 법정동 시군구명
DLVR_DSTN_DONG : 배달목적지 주소 법정동 읍면동명
DLVR_DSTN_RI : 배달목적지 주소 법정동 리명
DLVR_DSTN_ADSTRD_CODE : 배달목적지 주소 행정동 코드
DLVR_DSTN_RDNMADR : 배달목적지주소 도로명주소 코드
DLVR_MAN_ID : 배달기사 ID
DLVR_AMOUNT : 배달비용
CALL_RLAY_FEE_AMOUNT : 호출중계수수료금액
GOODS_AMOUNT : 배달상품금액
SETLE_KND_VALUE : 결제종류번호 (1:카드, 2:선불, 3:현금)
SETLE_CARD_CN : 결제카드종류
DLVR_RCEPT_TIME : 배달접수시간
DLVR_CARALC_TIME : 배달배차시간
DLVR_COMPT_TIME : 배달완료시간
DLVR_CANCL_TIME : 배달취소시간

#### <u>협업 가이드라인</u>

1. 각각 로컬 repository 생성하기 (git clone "https://github.com/sophryu99/dacon_post_corona.git")

2. `git checkout -b "브랜치_이름"`으로 각각 브랜치 생성하기 
- 선용: sy_dev
- 세화: sh_dev
- 현아: hn_dev
- 정민: jm_dev



3. 작업할 때 각각 브랜치에서 작업하기!! (**매우 중요**)
- `git branch` 로 브랜치 확인
- master 말고 자기 브랜치로 switch 된거 확인하고 거기에서 작업!!



4. 브랜치에서 내용 수정했을 시 각자 브랜치에서 (master 브랜치로 merge 하는 법) :
1. `git add .`
2. `git commit -m "메세지 입력"`
3. `git push origin 브랜치_이름`
4. `git checkout master` (마스터 브랜치로 이동)
5. `git merge 브랜치 이름`



