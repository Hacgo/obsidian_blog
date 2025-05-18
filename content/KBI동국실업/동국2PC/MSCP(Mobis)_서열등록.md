---
share_link: https://share.note.sx/jjb77ooc#vDtK25NSN6X3iMR51IybGRWWnMDV27tLGgOCupMyAPc
share_updated: 2025-03-25T14:26:47+09:00
---
## ※시나리오 정보
1. 사용코드
	- Account.py
	  (계정정보를 수집하는 코드)
	- UpCount.py
	  (오전에 2회 입력되는 것을 방지하는 카운트 수정 코드)
	- CountCell(MSCP).py
	  (데이터가 비어있는지 유무를 체크하는 코드)
	- Cut_OldExcel.py
	  (오래된 자료를 제거하는 코드)
---

2. 시나리오 설명
	 *오전에 올라오는 MSCP(모비스)의 2시간 소요계획, 일별소요계획 자료를 다운로드 받아서 ERP에 서열을 업로드하는 시나리오 입니다.*
	[1-1] ![[Pasted image 20241231153240.png]]
	단) 자료가 올라온게 없는 경우 또는 2시간/일별소요계획 둘중 하나의 자료가 없을경우 시나리오는 종료됩니다.
		또한 모든 엑셀은 C:\Argos\RPA\ERP업로드(모비스)\일별 or 2시간 안에 파일이 저장이됩니다.
	[1-2]![[Pasted image 20241231155314.png]]
	[1-3]![[Pasted image 20241231160143.png]]