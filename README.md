# 웹플 정리
### 1. 표 삽입 (tr, td, th)
표를 생성할 때는 table 태그 사용하고 가로로 한 줄씩 내용을 써내려감
<table>
<tr>
<td>1행 1열</td>
<td>1행 2열</td>
</tr>
<tr>
<td>2행 1열</td>
<td>2행 2열</td>
</tr>
</table>

th 태그는 표의 제목을 뜻하므로 굵게 표시된다.
<table>
<tr>
<th>제목</th>
<td>내용</td>
</tr>
</table>
제목은 th 태그로 작성한 것!

### 2. 표에서 셀 병합하기
표의 내용이 같아서 셀을 합치고 싶을 땐 colspan과 rowspan을 사용하면 된다.   ex) tr rowspan="2"

