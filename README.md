<?php 
	include('includes/header.inc');
	include('php/Ccategorias.php');
	$categor= new CCategorias();
?>
<div id="banner">
	
</div>
<h3>Nuestras Categorias</h3>
<div id="cjCategoria">
	<?php 
		echo $categor->mostrar();
	?>
</div>
<?php 
	include('includes/footer.inc');
?>
		
