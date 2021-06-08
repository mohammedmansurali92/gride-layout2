# gride-layout2
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Bootstrap 4 Example</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
  <style>
  	.grid-container{
  		display: grid;
  		grid-template-columns: auto auto auto auto;
  		/*grid-template-rows: 120px;*/
  		/*grid-column-gap: 10px;
  		grid-row-gap: 10px;*/
  		 grid-gap: 20px 10px;
  		background-color: cadetblue;
  		justify-content: left;
  	}
  	.grid-container>div{
  		background-color:chocolate;
  		border:1px solid black;
  		text-align: center;
  		padding: 5px;
  	}
  	.item1{
  		/*grid-column-start:1;
  		grid-column-end: 3;*/
  		grid-column: 1/ span 3;
  		/*grid-row-start:1;
  		grid-row-end: 4;*/
  		grid-row:1/ 4;

  	}
  </style>
  <title>Grid Layout</title>
</head>
<body> 
	<div class="grid-container">
	<div class="item1"><img src="C:\Users\hp\Desktop\img_42.jpg.lnk"></div>
	<div><img src="C:\Users\hp\Desktop\img_42.jpg.lnk"></div>
	<div>3</div>
	<div>4</div>
	<div>5</div>
	<div>6</div>
	<div>7</div>
	<div>8</div>
	<div>9</div>
	<div>10</div>
	<div>11</div>
	<div>12</div>
	<div>13</div>
	<div>14</div>
	<div>15</div>
	<div>16</div>
   </div>


 <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>
</body>
</html> 
