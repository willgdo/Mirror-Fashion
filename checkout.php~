<!DOCTYPE html>
<html> 
<head>
	<meta charset = "utf-8">
	<title>Checkout MIrror Fashion</title>	
	<meta name="viewport" content="width=device-width">	

	<link rel="stylesheet" href="bootstrap.css">
</head> 
<body>
	<div class="jumbotron">
		<div class="container">
			<h1>Ótima escolha!</h1>
			<p>Obrigado por compra na Mirror Fashion! Preencha seus dados para efetivar a compra.</p>
		</div>
	</div>
			
		<div class="container">
			<div class="row">
				<div class="col-sm-4">
					<div class="panel panel-success">
						<div class="panel-heading">
							<h2 class="panel-title">Sua compra</h2>
						</div>
						<div class="panel-body">
							<dl>
								<dt>Produto</dt>
								<dd><?= $_POST['nome'] ?></dd>

								<dt>Preço</dt>
								<dd id="preco"><?= $_POST['preco'] ?></dd>

								<dt>Cor</dt>
								<dd><?= $_POST['cor'] ?></dd>

								<dt>Tamanho</dt>
								<dd><?= $_POST['tamanho'] ?></dd>
							</dl>
							<div class="form-group">
								<label for="qt">Quantidades</label>
								<input id="qt" class="form-control" type="number" min="0" max="99" value="1">
							</div>
							<div class="form-group">
								<label for="total">Total</label>
								<output for="qt valor" id="total" class="form-control">
									<?= $_POST["preco"] ?>
								</output>
							</div>
						</div>
					</div>
				</div>	
				<form class="col-sm-8">
					<div class="row">
						<fieldset class="col-md-6">
							<legend>Dados Pessoais</legend>
								<div class="form-group">
									<label for="nome">Nome Completo</label>
									<input type="text" class="form-control" id="name" name="nome" required autofocus>
								</div>
								<div class="form-group">
									<label for="email">Email</label>
									<input type="email" class="form-control" id="email" name="email" placeholder="email@exemplo.com.br">
								</div>
								<div class="form-group">
									<label for="cpf">CPF</label>
									<input type="text" class="form-control" id="cpf" name="cpf" required placeholder="000.000.000-00">
								</div>
								<div class="checkbox">
									<label>
										<input type="checkbox" value="sim" name="spam" checked>Quero receber spam da Mirror Fashion
									</label>
								</div>
						</fieldset>
						<fieldset class="col-md-6">
							<legend>Cartão de Crédito</legend>
							<div class="form-group">
									<label for="numero-cartao">Número - CVV</label>
									<input type="text" class="form-control" id="numero-cartao" name="numero-cartao">
								</div> 
								<div class="form-group">
									<label for="bandeira-cartao">Bandeira</label>
									<select name="bandeira-cartao" id="bandeira-cartao" class="form-control">
										<option value="master">MasterCard</option>
										<option value="visa">VISA</option>
										<option value="amex">American Express</option>
									</select>								
								</div> 
								<div class="form-group">
									<label for="validade-cartao">Validade</label>
									<input type="month" class="form-control" id="validade-cartao" name="validade- cartao">								
								</div> 
						</fieldset>
					</div>
						<button type="submit" class="btn btn-primary">
						<span class="glyphicon glyphicon-thumbs-up"></span>
						Confirmar Pedido
					</button>
				</form>		
			</div>		
		</div>
	<script src="js/converteMoeda.js"></script>
	<script src="js/testaConversao.js"></script>

	<script src="js/total.js"></script>
</body>
</html>


