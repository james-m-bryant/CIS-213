<!doctype html>
<html>
<head>
<meta charset="UTF-8">
<title>Selector Basics</title>
<link href ="http://fonts.googleapis.com/css?family=Varela+Round" rel= "stylesheet">
<style>
	
	body {
		background-color: rgb(50,122,167);
		padding: 0 20px 20px 20px;
		margin: 0;
	}
	
	p {
		color: rgba(255, 255, 255,.6);
		font-size: 1em;
		font-family: "Varela Round", Arial, Helvetica, sans-serif;
	}
	
	h1, h2, h3 {
		color: rbg(255,255,255);
		font-family: Arial, "Palatino Linotype", Times, serif;
		border-bottom: 2px solid rgb(87, 185, 178);
		padding-top: 10px;
		padding-bottom: 5px;
	}
	
	h1 {
		font-size: 2em;
	}
	
	h1+p {
		color: rgb(255,255,255);
		font-size: 1.2em;
		line-height: 140%
	}
	
	#logo {
		font-family: Baskerville, Palatino, sans-serif;
		font-size: 2em;
		color: rgba(255.255.255,0.8);
		font-style: italic;
		text-align: center;
		margin-bottom: 30px;
		background-color: rgb(191,91,116);
		border-radius: 0 0 10px 10px;
		padding: 10px;
	}
	
	.note {
		color: black;
		border: 2px solid white;
		background-color: rgb(69, 189, 102);
		margin-top: 25px;
		margin-bottom: 35px;
		padding: 20px;
	}
	
	.note strong{
		color: #FC6512;
	}
	
	article{
		max-width: 760px;
		margin 0 auto;
	}
	
	table{
		color: white;
		padding: 40px 40px 40px 325px;

	}
	
	tr:nth-child(odd){
			
			background-color: orange;
		}
	
	tr:nth-child(even){
			background-color: black;
		}
	
	tr:first-of-type, td:first-of-type {
			color: yellow;
			background-color: red;
		}

	
</style>
</head>
<body>
	
<table>
	<tr>
		<th></th>
		<th>A</th>
		<th>B</th>
		<th>C</th>
		<th>D</th>
		<th>E</th>
	</tr>
	<tr>
		<td>1</td>
		<td>1A</td>
		<td>1B</td>
		<td>1C</td>
		<td>1D</td>
		<td>1E</td>
	</tr>
	<tr>
		<td>2</td>
		<td>2A</td>
		<td>2B</td>
		<td>2C</td>
		<td>2D</td>
		<td>2E</td>
	</tr>
	<tr>
		<td>3</td>
		<td>3A</td>
		<td>3B</td>
		<td>3C</td>
		<td>3D</td>
		<td>3E</td>
	</tr>
	<tr>
		<td>4</td>
		<td>4A</td>
		<td>4B</td>
		<td>4C</td>
		<td>4D</td>
		<td>4E</td>
	</tr>
	<tr>
		<td>5</td>
		<td>5A</td>
		<td>5B</td>
		<td>5C</td>
		<td>5D</td>
		<td>5E</td>
	</tr>
</table>
	
<br>
	
<article>
<div id="logo">
  CSS: The Missing Manual
</div>
<h1>The Amazing World of CSS</h1>
<p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. </p>
<p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?</p>
<p class="note"><strong>NOTE:</strong> Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? </p>
<h2>Who Knew CSS Had Such Power?</h2>
<p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?</p>
<p class="note"><strong>NOTE:</strong> Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? </p>
<h3>Not Me!</h3>
<p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?</p>
<h3>Me Neither!</h3>
<p>Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium doloremque laudantium, totam rem aperiam, eaque ipsa quae ab illo inventore veritatis et quasi architecto beatae vitae dicta sunt explicabo. Nemo enim ipsam voluptatem quia voluptas sit aspernatur aut odit aut fugit, sed quia consequuntur magni dolores eos qui ratione voluptatem sequi nesciunt. Neque porro quisquam est, qui dolorem ipsum quia dolor sit amet, consectetur, adipisci velit, sed quia non numquam eius modi tempora incidunt ut labore et dolore magnam aliquam quaerat voluptatem. Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil molestiae consequatur, vel illum qui dolorem eum fugiat quo voluptas nulla pariatur?</p>
</article>
</body>
</html>
