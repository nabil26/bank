<!DOCTYPE html>
<html>

<head>
	<meta charset="utf-8" />
	<title>Al-Amanah Banking</title>
	<link rel="stylesheet" href="http://code.jquery.com/mobile/1.1.0/jquery.mobile-1.1.0.min.css" />
	<script src="http://code.jquery.com/jquery-1.7.1.min.js"></script>
	<script src="http://code.jquery.com/mobile/1.1.0/jquery.mobile-
	1.1.0.min.js"></script>
	<meta name="viewport" content="width=device-width, initial-scale;e=1">
</head>
	
<body>
	
	<div data-role="page" id="main" data-theme="e">
		
		<div data-role="header" data-theme="e">
			<img src="alamanahlogo.png" style="display: block; margin: 0 auto"/>
		</div>
		
		<div data-role="content">
			<a href=#login data-role="button" data-rel="dialog" data-transition="flow" data-icon="arrow-r" data-iconpos="left">Login</a>
			<a href=#Agreement data-role="button" data-transition="flow" data-icon="arrow-r" data-iconpos="left">Registration</a>
			<a href=#Exchangerates data-role="button" data-transition="flow" data-icon="arrow-r" data-iconpos="left">Exchange Rates</a>
			<a href="ATMPage.html" data-role="button" data-transition="flow" data-icon="arrow-r" data-iconpos="left">Branches</a>
			<a href=#contact data-role="button" data-transition="flow" data-icon="arrow-r" data-iconpos="left">Contact Us</a>
		</div>
		
		<div data-role="footer" data-theme="e">
		<h3> </h3>
		</div>
		
	</div>
	
	<div data-role="page" id="login" data-theme="e">
		
		<div data-role="header" data-theme="e">
			<img src="alamanahlogo.png" style="display: block; margin: 0 auto"/>
			<h1>Login Page</h1>
		</div>
		
		<div data-role="content">
			<div data-role="fieldcontain">
				<label for="name">Username:</label>
				<input type="text" name="name" id="name" placeholder="Enter your username here" value=""  />
				<label for="name">Password:</label>
				<input type="password" name="name" id="name" placeholder="Enter your password here" value=""  />
				
				<div class="ui-grid-a">
					<div class= "ui-block-a">
						<p> </p>
					</div>
					<div class= "ui-block-b">
						<label><input type="checkbox" name="checkbox" data-inline="true" data-theme="b" data-mini="true"/>Remember Me</label>
					</div>
				</div>
						
				<div>
					<a href="TokenPage.html" data-role="button" data-theme="b" data-mini="true">Login</a>
					<a href="ForgotIDPage.html" data-role="button" data-theme="b" data-mini="true">Forgot My ID!</a>
				</div>	
					
			</div>
			
		</div>
	</div>
	
	<div data-role="page" id="Agreement" data-theme="e">
		<img src="alamanahlogo.png" style="display: block; margin: 0 auto"/>
		
		<div data-role="content">
		<p>Application of Agreement</p>
		<p>This Agreement shall constitute an agreement between the Customer and BIBD and shall apply not only 
		in relation to those Account(s) and services currently requested or applied for by or for the Customer 
		but also to any and all other Accounts currently maintained by the Customer with BIBD and all Services 
		currently utilised by or for the Customer and all Accounts which may be subsequently opened or established 
		and to other Services which have been or would be utilised by the Customer from time to time.</p>
		<p>In the event of any conflict or inconsistency between any of the provisions of this Agreement 
		and any of the provisions of any previous agreement between BIBD and the Customer with respect to 
		any Account or Services, the provisions of this Agreement shall prevail and supersede any previous 
		agreement governing the same.</p>
		<p>Notwithstanding anything to the contrary herein, the terms of this Agreement shall not affect or 
		diminish in any way the rights of BIBD referred to or set out in the Website, including but not limited 
		to any and all exclusions, disclaimers and limitations of any liabilities of BIBD referred to or set out in the Website.</p>
		</div>
		<div class="ui-grid-a">
			<div class= "ui-block-a">
				<a href="MainPage.html" data-role="button" data-theme="a">Disagree</a>	
			</div>
			<div class= "ui-block-b">
				<a href="RegistrationPage.html" data-role="button" data-theme="b">Agree</a>
			</div>
		</div>
	</div>
	
	<div data-role="page" id="Exchangerates" data-theme="e">
		<img src="alamanahlogo.png" style="display: block; margin: 0 auto"/>
		
		<div data-role="content">
			<div data-role="collapsible" data-iconpos="right" data-theme="b">
				<h3>US DOLLARS</h3>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Buying TT</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2634</p>
						</div>
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Selling TT</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2841</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Buying Notes</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2300</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Selling Notes</p>
						</div>
						<div class= "ui-block-c">
							<p>1.3200</p>
						</div>	
					</div>
			</div>
			<div data-role="collapsible" data-iconpos="right" data-theme="b">
				<h3>POUND STERLING</h3>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Buying TT</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2634</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Selling TT</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2841</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Buying Notes</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2300</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Selling Notes</p>
						</div>
						<div class= "ui-block-c">
							<p>1.3200</p>
						</div>	
					</div>
			</div>
			<div data-role="collapsible" data-iconpos="right" data-theme="b">
				<h3>MALAYSIAN RINGGIT</h3>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Buying TT</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2634</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Selling TT</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2841</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Buying Notes</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2300</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Selling Notes</p>
						</div>
						<div class= "ui-block-c">
							<p>1.3200</p>
						</div>	
					</div>
			</div>
			<div data-role="collapsible" data-iconpos="right" data-theme="b">
				<h3>EURO</h3>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Buying TT</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2634</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Selling TT</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2841</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Buying Notes</p>
						</div>
						<div class= "ui-block-c">
							<p>1.2300</p>
						</div>	
					</div>
					<div class="ui-grid-a">
						<div class= "ui-block-a">
							<p>Selling Notes</p>
						</div>
						<div class= "ui-block-c">
							<p>1.3200</p>
						</div>	
					</div>
			</div>
		</div>
	</div>
	
	<div data-role="page" id="contact" data-theme="e">
		<img src="alamanahlogo.png" style="display: block; margin: 0 auto"/>
		
		<div data-role="content">
			<p>Al-Amanah Call Center Hotline</p>
				<a href="tel:+6732234567" data-role="button">
				2234567</a>
			<p>Al-Amanah Branch Operator Line</p>
				<a href="tel:+6732765432" data-role="button">
				2765432</a>
		</div>
	</div>
</body>
</html>
