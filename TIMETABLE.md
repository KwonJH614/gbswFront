``` 
<!DOCTYPE html>
<html lang="ko">
<head>
	<meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
	<style>
		body {
		 text-align: center;
		 }
		 td {
			 border: solid 1px black;
			 padding: 5px;  
		 }
		 th {
			 border: solid 1px black;
			 background-color :#cdb4db;
		 }
			table {
			 border: solid 1px;
			 border-collapse: collapse;
		 }
			table, tr, td {
			 width: 500px;
			 height: 50px;
		 }
 </style>
</head>
<body>
  <table>
    <caption>1학년 1반 시간표</caption>
      <thead>
        <tr>
        <th style="background-color: white;"></th>
        <th>월</th>
        <th>화</th>
        <th>수</th>
        <th>목</th>
        <th>금</th>
        </tr>
      </thead>
		<tbody>
				<tr>
				<td>1</td>
				<td>자율</td>
				<td rowspan="2" style="background-color:  #ffc8dd;">미술</td>
				<td>수학</td>
				<td>사회</td>
				<td>수학</td>
			</tr>
			<tr>
				<td>2</td>
				<td>진로</td>
				<td>국어</td>
				<td rowspan="2" style="background-color: #ffafcc;">응개</td>
				<td>과학</td>
			</tr>
			<tr>
				<td>3</td>
				<td>영어</td>
				<td>과학</td>
				<td>사회</td>
				<td rowspan="2" style="background-color: #bde0fe;">응개</td>
			</tr>
			<tr>
				<td>4</td>
				<td>사회</td>
				<td>체육</td>
				<td>체육</td>
				<td>영어</td>
			</tr>
			<tr>
				<td>5</td>
				<td>수학</td>
				<td>국어</td>
				<td>영어</td>
				<td rowspan="3" style="background-color: #a2d2ff;">자바</td>
				<td>동아리</td>
			</tr>
			<tr>
				<td>6</td>
				<td>과학</td>
				<td rowspan="2" style="background-color: #8ecae6;">자바</td>
				<td>응개</td>
			</tr>
			<tr>
				<td>7</td>
				<td>국어</td>
			</tr>
		<tbody>
  </table>
</body>
</html>
```