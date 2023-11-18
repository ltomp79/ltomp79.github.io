<!DOCTYPE html>
<html>
<head>
	<title>Darkspeed Gaming</title>
	<style>
		body {
			background-color: #E1D9D1;
			color: #00008B;
			font-family: Arial, sans-serif;
		}
		h1 {
			color: #00008B;
			text-align: center;
		}
		.container {
			display: flex;
			flex-wrap: wrap;
			justify-content: center;
			align-items: center;
			margin: 0 auto;
			max-width: 1200px;
		}
		.box {
			background-color: #00008B;
			border-radius: 5px;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
			margin: 10px;
			padding: 20px;
			text-align: center;
			width: 300px;
		}
		.box img {
			border-radius: 5px;
			margin-bottom: 10px;
			max-width: 100%;
		}
		.calendar {
			background-color: #ffffff;
			border-radius: 5px;
			box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
			margin: 10px;
			padding: 20px;
			text-align: center;
			width: 300px;
		}
		.calendar table {
			border-collapse: collapse;
			margin: 0 auto;
			width: 100%;
		}
		.calendar th {
			background-color: #00008B;
			color: #ffffff;
			font-weight: bold;
			padding: 10px;
			text-align: center;
		}
		.calendar td {
			background-color: #ffffff;
			border: 1px solid #00008B;
			padding: 10px;
			text-align: center;
		}
		.calendar td.today {
			background-color: #00008B;
			color: #ffffff;
			font-weight: bold;
		}
	</style>
</head>
<body>
	<h1>Darkspeed Gaming</h1>
	@@ -80,49 +120,4 @@
			<a href="#" target="_blank">Link to Something</a>
		</div>
		<div class="box">
			<img src="https://source.unsplash.com/random/300x200?sig=3" alt="Random Image 3">
			<a href="#" target="_blank">Link to Something</a>
		</div>
		<div class="box">
			<img src="https://source.unsplash.com/random/300x200?sig=4" alt="Random Image 4">
			<a href="#" target="_blank">Link to Something</a>
		</div>
		<div class="box">
			<img src="https://source.unsplash.com/random/300x200?sig=5" alt="Random Image 5">
			<a href="#" target="_blank">Link to Something</a>
		</div>
		<div class="box">
			<img src="https://source.unsplash.com/random/300x200?sig=6" alt="Random Image 6">
			<a href="#" target="_blank">Link to Something</a>
		</div>
		<div class="calendar">
			<h2>Calendar</h2>
			<table>
				<thead>
					<tr>
						<th>Sun</th>
						<th>Mon</th>
						<th>Tue</th>
						<th>Wed</th>
						<th>Thu</th>
						<th>Fri</th>
						<th>Sat</th>
					</tr>
				</thead>
				<tbody>
					<tr>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
						<td></td>
						<td>1</td>
						<td>2</td>
					</tr>
					<tr>
						<td>3</td>
						<td>4</td>
						<td>5</td>
						<td>6</td>
						<td>7</td>
						<td>8</td>
