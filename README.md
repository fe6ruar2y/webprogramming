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
표의 내용이 같아서 셀을 합치고 싶을 땐 colspan과 rowspan을 사용하면 된다.   ex) tr rowspan="2
</br>
셀 병합을 한 후에 표를 작성할 때는 그 셀을 중복적으로 쓰지 않아도 된다.

### 3. radio 태그 주의사항
radio는 하나만 선택할 때, checkbox는 여러개 선택할 때 사용
</br>
radio 태그 사용 시 : input type="radio"  name="feb" value="1"
</br>
radio 태그에서 name 을 같이 쓰는 경우가 있는데 이때 하나만 선택되게 하려고 하려면 name의 이름이 다 같아야한다!
