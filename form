
<DOCTYPE html>
	<html lang="en-us">
	<head>
	<title>upload image</title>
	<meta charset="utf-8">
	<style>
	.container{
		padding:20px;	
	}
	.status p{
		font-size: 16px;
		padding: 10px;
		border: 1px dashed;
		margin-bottom: 10px;
	}
	.gallery{
		width: 100%;
		text-align: center; 
	}
	hs{
		color: #545353;
		font-size: 10px;
		text-transform: uppercase;
		background: #edeaea;
		padding: 7px 5px 4px 5px;
		margin-top: 20px;
	}
	</style>
	</head>
	<body>
		<div class="container">
			<div class="status">
				<?php echo !empty($statusMsg)?$statusMsg:''; ?>
			</div>
			<form action="upload.php" method="post" enctype="multipart/form-data">
    			<label>Select Image file to upoload</label> 
    			<input type="file" name="name">
    			<input type="submit" name="submit" value="Upload">
			</form>

			<?php if (!empty($uploadedFileName)){ ?>
				<h5>Watermaarked Image</h5>
				<div class="gallery"></div>
				
				<img src="<?php 'uploads/'.$targetFilePath; ?>" alt="">
					</div>
					<?php	}  ?>

		</div>
	</body>
	</html>
