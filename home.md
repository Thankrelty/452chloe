<!DOCTYPE html>
<html>
<head>
	<title></title>
	<style>
		body {/*整体控制;*/
			margin: 0;
			padding: 0;
			font-family: Arial, sans-serif;
			background-color: #f2f2f2;
		}
        header {
		background-color: #dd4b39;/*背景颜色*/
		color: #fff;
		padding: 20px;
		text-align: center;
	}

	nav {/*导航部分*/
		background-color: #eee;
		padding: 10px;
		text-align: center;
	}

	nav ul {
		list-style-type: none;
		margin: 0;
		padding: 0;
	}

	nav ul li {
		display: inline-block;
		margin-right: 10px;
	}

	nav ul li a {
		color: #333;
		display: block;
		padding: 10px 15px;
		text-decoration: none;
	}

	nav ul li a:hover {
		background-color: #fff; 
		color: #dd4b39;
	}
		.container {
			width: 80%;
			margin: 0 auto;
			padding: 20px;
			background-color: #fff;
			box-shadow: 0px 0px 10px rgba(0,0,0,0.3);
			text-align: center;
		}
		
		
		h1 {/*标题部分*/
			color: #100505cc;
			font-size: 36px;
			margin-bottom: 20px;
		}
		p {
			color: #555;
			font-size: 18px;
			margin-bottom: 20px;
		}
		table {/*表格部分*/
			border-collapse: collapse;
			width: 100%;
		}
		td, th {
			border: 1px solid black;
			padding: 20px;
			text-align: center;
		}
		footer
		{
			text-align: center;
		}
		
		
	
	</style>
</head>
<body>
   
        
	<div class="container">
		
		<h1>header</h1>
        <nav>
            <ul>
            <li><a href="home.html">1</a></li>
            <li><a href="2.html">2</a></li>
            <li><a href="3.html">3</a></li>
            
            </ul>
            </nav>
		<h2>self introduction</h2>
		<table>
			
			<tr>
				<img src="./img/tg.jpg" alt="" width="200px" height="200px">

				<td> I'm Chloe, and my Chinese name is Du Yinlu. I am a graduate student. I worked as a Java programmer in a large enterprise. I have a lot of hobbies, a lot of fields and a wide range of knowledge, and I am particularly interested in ICT-related things. I have a lot of client feeds, know CSS, html, etc<br>
					Hobbies and interests：

					I like to watch science and technology exhibitions, watch current affairs news, like astronomy and geography, and like to read</td>
				
			</tr>
		</table>
		<table>
			<tr>
				<th>Accomplishment</th>
				<th>Time</th>
				<th>level</th>
				<th>Place</th>
			</tr>
			<tr>
				<td>pass the English A-level exam</td>
				<td>2022.12</td>
				<td>country</td>
				<td>NBCC</td>
			</tr>
			<tr>
				<td>License</td>
				<td>2022.6</td>
				<td>country</td>
				<td>Wen Zhou</td>
			</tr>
			<tr>
				<td>Computer level</td>
				<td>2022.2</td>
				<td>country</td>
				<td>nbcc</td>
			</tr>
		</table>
	</div>
	<footer><p>1</p></footer>

</body>
</html>
