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
		.calendar td.orange {
			background-color: orange;
		}
	</style>
	<script>
		function updateCalendar() {
			let today = new Date();
			let year = today.getFullYear();
			let month = today.getMonth();
			let day = today.getDate();
			let daysInMonth = new Date(year, month + 1, 0).getDate();
			let firstDayOfMonth = new Date(year, month, 1).getDay();
			let calendarTable = document.getElementById("calendarTable");
			let calendarCells = calendarTable.getElementsByTagName("td");
			let calendarHeader = document.getElementById("calendarHeader");
			let monthName = calendarHeader.getElementsByTagName("h2")[0];
			let date = calendarHeader.getElementsByTagName("p")[0];
			let dayOfWeek = ["Sun", "Mon", "Tue", "Wed", "Thu", "Fri", "Sat"];
			let monthNames = ["January", "February", "March", "April", "May", "June", "July", "August", "September", "October", "November", "December"];
			monthName.innerHTML = monthNames[month];
			date.innerHTML = today.toDateString();
			for (let i = 0; i < calendarCells.length; i++) {
				calendarCells[i].innerHTML = "";
				calendarCells[i].classList.remove("orange");
			}
			for (let i = 0; i < daysInMonth; i++) {
				let cellIndex = firstDayOfMonth + i;
				calendarCells[cellIndex].innerHTML = i + 1;
				if (i + 1 === day) {
					calendarCells[cellIndex].classList.add("today");
				}
				if (i % 7 === 5) {
					calendarCells[cellIndex].classList.add("orange");
				}
			}
		}
		window.onload = function() {
			updateCalendar();
			setInterval(updateCalendar, 86400000);
		}
	</script>
</head>
<body>
	<h1>Darkspeed Gaming</h1>
	<div class="container">
		<div class="box">
			<img src="https://source.unsplash.com/random/300x200?sig=1" alt="Random Image 1">
			<a href="#" target="_blank">Link to Something</a>
		</div>
		<div class="box">
			<img src="https://source.unsplash.com/random/300x200?sig=2" alt="Random Image 2">
			<a href="#" target="_blank">Link to Something</a>
		</div>
		<div class="box">
			<img src="https
