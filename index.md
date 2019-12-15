<!DOCTYPE html>
<html>
<head>
	<title>SketchUp Designs Using Bootstrap</title>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css">
  	<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  	<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
 	<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js"></script>
	
</head>
<body>
	<div class="row bg-light border rounded my-3 p-3">
		<div class="col-sm-6 border rounded border-primary my-3 p-3">
			<h3 class="display-3 text-center text-primary">Welcome</h3>
			<div class="container border rounded my-3 p-3 border-primary">
				<form action="#" class="was-validated">
					<div class="form-group">
						<label for="email">Email Address:</label>
						<input type="email" name="email" class="form-control" required placeholder="Enter Email">
						 <div class="valid-feedback">Valid.</div>
  					  <div class="invalid-feedback">Please fill out this field.</div>
					</div>
					<div class="form-group">
						<label for="pwd">Password:</label>
						<input type="password" name="password" required class="form-control"placeholder="Enter password">
						<div class="valid-feedback">Valid.</div>
    					<div class="invalid-feedback">Please fill out this field.</div> 
					</div>
					  
					  

					<button type="submit" class="btn btn-primary">Sign In</button>
					 <h5 class="text-justify text-primary"><a href="">Forgot Password?</a></h5>
					 <h5 class="text-justify text-primary "><a href="">Signup</a></h5>

				</form>
			</div>

		</div>


		<div class="col-sm-6 border rounded border-primary my-3 p-3">
			  <div class="pos-f-t">
				  <div class="collapse" id="navbarToggleExternalContent">
				    <div class="bg-dark p-4">
				      <h4 class="text-white">Collapsed content</h4>
				      <span class="text-muted">Dashboard.</span>
				    </div>
				  </div>
				  
				  <!-- Toggable Navigation Bar-->
				  <nav class="navbar navbar-dark bg-dark">
				    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarToggleExternalContent" aria-controls="navbarToggleExternalContent" aria-expanded="false" aria-label="Toggle navigation">
				      <span class="navbar-toggler-icon"></span>
				    </button>

				    <!-- Logout Button-->
				    <a class="navbar-brand" href="#"><img src="img/img_avatar1.png" class="img-fluid img-thumbnail" style="width:40px">Logout</a>


				  </nav>
				</div>
				<div class="row my-3 p-3">
					<div class="col-sm-6 my-3 p-3">
					<div class="container border rounded bg-light my-3 p-3">
						<h3 class="text-primary text-center">NGN ******<h3><pre></pre>
						<h3 class="text-primary display-3 text-center"><span class="badge badge-danger my-3 p-3 justify-content-center">Expenses</span></h3>

					</div>
					</div>
					<div class="col-sm-6 my-3 p-3">
						<div class="container border rounded bg-light my-3 p-3">
							<h3 class="text-primary text-center">NGN ******<h3><pre></pre>
							<h3 class="text-primary display-3 text-center"><span class="badge badge-success my-3 p-3 justify-content-center">Income</span></h3>

						</div>
					</div>
				</div>

				<div class="row my-3 p-3">
					<div class="col-sm-12 my-3 p-3 justify-content-center">
						<div class="progress" style="height: 100px">
  				<div class="progress-bar-striped progress-bar-animated text-white text-center bg-success" style="width:70%"><h5><pre></pre>70% Financial Target Realized</h5></div>

  						</div>
					</div>

				</div>

				
				</div>

	</div>
 	<div class="row">
					<div class="col-sm-12 my-3 p-3 justify-content-center">
						<footer class="text-center text-white border bg-dark rounded" style="height: 50px"><pre></pre>
							Collaboratively Built @2019
						</footer>
  		 
  					</div>
	</div>


	
	





</body>
</html>