<!DOCTYPE html>
<html lang="en">
<head>
<title>Fitness Club</title>
<meta charset="utf-8">
<link rel="stylesheet" type="text/css" media="screen"
	href="css/reset.css">
<link rel="stylesheet" type="text/css" media="screen"
	href="css/style.css">
<link rel="stylesheet" type="text/css" media="screen"
	href="css/grid_12.css">
<link rel="stylesheet" type="text/css" media="screen"
	href="css/slider.css">


<script type="text/javascript"
	src="https://ajax.googleapis.com/ajax/libs/jquery/1.6.2/jquery.min.js"></script>
<script type="text/javascript"
	src="https://ajax.aspnetcdn.com/ajax/jquery.validate/1.8.1/jquery.validate.min.js"></script>
<script type="text/javascript" src="https://js.stripe.com/v1/"></script>
<script type="text/javascript">
          Stripe.setPublishableKey('pk_test_eHUjzDkkytD3OqupLk22OcLH');
            $(document).ready(function() {
                function addInputNames() {
                    // Not ideal, but jQuery's validate plugin requires fields to have names
                    // so we add them at the last possible minute, in case any javascript 
                    // exceptions have caused other parts of the script to fail.
                    $(".card-number").attr("name", "card-number")
                    $(".card-cvc").attr("name", "card-cvc")
                    $(".card-expiry-year").attr("name", "card-expiry-year")
                }
 
                function removeInputNames() {
                    $(".card-number").removeAttr("name")
                    $(".card-cvc").removeAttr("name")
                    $(".card-expiry-year").removeAttr("name")
                }
 
                function submit(form) {
                    // remove the input field names for security
                    // we do this *before* anything else which might throw an exception
                    removeInputNames(); // THIS IS IMPORTANT!
 
                    // given a valid form, submit the payment details to stripe
                    $(form['submit-button']).attr("disabled", "disabled")
 
                    Stripe.createToken({
                        number: $('.card-number').val(),
                        cvc: $('.card-cvc').val(),
                        exp_month: $('.card-expiry-month').val(), 
                        exp_year: $('.card-expiry-year').val()
                    }, function(status, response) {
                        if (response.error) {
                            // re-enable the submit button
                            $(form['submit-button']).removeAttr("disabled")
        
                            // show the error
                            $(".payment-errors").html(response.error.message);
 
                            // we add these names back in so we can revalidate properly
                            addInputNames();
                        } else {
                            // token contains id, last4, and card type
                            var token = response['id'];
 
                            // insert the stripe token
                            var input = $("<input name='stripeToken' value='" + token + "' style='display:none;' />");
                            form.appendChild(input[0])
 
                            // and submit
                            form.submit();
                        }
                    });
                    
                    return false;
                }
                
                // add custom rules for credit card validating
                jQuery.validator.addMethod("cardNumber", Stripe.validateCardNumber, "Please enter a valid card number");
                jQuery.validator.addMethod("cardCVC", Stripe.validateCVC, "Please enter a valid security code");
                jQuery.validator.addMethod("cardExpiry", function() {
                    return Stripe.validateExpiry($(".card-expiry-month").val(), 
                                                 $(".card-expiry-year").val())
                }, "Please enter a valid expiration");
 
                // We use the jQuery validate plugin to validate required params on submit
                $("#example-form").validate({
                    submitHandler: submit,
                    rules: {
                        "card-cvc" : {
                            cardCVC: true,
                            required: true
                        },
                        "card-number" : {
                            cardNumber: true,
                            required: true
                        },
                        "card-expiry-year" : "cardExpiry" // we don't validate month separately
                    }
                });
 
                // adding the input field names is the last step, in case an earlier step errors                
                addInputNames();
            });
        </script>
<script src="js/jquery-1.7.min.js"></script>
<script src="js/jquery.easing.1.3.js"></script>
<script src="js/tms-0.3.js"></script>
<script src="js/tms_presets.js"></script>
<script src="js/cufon-yui.js"></script>
<script src="js/Asap_400.font.js"></script>
<script src="js/Coolvetica_400.font.js"></script>
<script src="js/Kozuka_M_500.font.js"></script>
<script src="js/cufon-replace.js"></script>
<script src="js/FF-cash.js"></script>

<script>
$(window).load(function(){
	$('.slider')._TMS({
	prevBu:'.prev',
	nextBu:'.next',
	pauseOnHover:true,
	pagNums:false,
	duration:800,
	easing:'easeOutQuad',
	preset:'Fade',
	slideshow:7000,
	pagination:'.pagination',
	waitBannerAnimation:false,
	banners:'fade'
	})
}) 	
</script>
<!--[if lt IE 9]>
<script src="js/html5.js"></script>
<link rel="stylesheet" type="text/css" media="screen" href="css/ie.css">
<![endif]-->

</head>
<body>
	<div class="main">
		<div class="bg-img"></div>
		<!--==============================header=================================-->
		<header>
			<h1>
				<a href="index.html">M&C <strong>GYM.</strong></a>
			</h1>
			<nav>
				<div class="social-icons">
					<a href="#" class="icon-2"></a> <a href="#" class="icon-1"></a>
				</div>
				<ul class="menu">
					<li><a href="ProfileMembership.html">BuyMembership</a></li>

				</ul>
			</nav>
		</header>
		<!--==============================content================================-->
		<section id="content">
			<div class="container_12">
				<div class="grid_12">
					<div class="slider">
						<ul class="items">
							<li><img src="images/slider-1.jpg" alt="">
								<div class="banner">
									<p class="font-1">
										Special<span>Program</span>
									</p>
									<p class="font-2">Lorem ipsum dolor sit amet, consetetur
										sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut
										labore et dolore magna.</p>
									<a href="#">Read More</a>
								</div></li>
							<li><img src="images/slider-2.jpg" alt="">
								<div class="banner">
									<p class="font-1">
										Get Free<span>Training</span>
									</p>
									<p class="font-2">Liquyam erat, sed diam voluptua. At vero
										eos et accusam et justo duo dolores et ea rebum. Stet clita
										kasd gubergren.</p>
									<a href="#">Read More</a>
								</div></li>
							<li><img src="images/slider-3.jpg" alt="">
								<div class="banner">
									<p class="font-1">
										Join<span>our team</span>
									</p>
									<p class="font-2">Liquyam erat, sed diam voluptua. At vero
										eos et accusam et justo duo dolores et ea rebum. Stet clita
										kasd gubergren.</p>
									<a href="#">Read More</a>
								</div></li>
						</ul>
						<div class="pagination">
							<ul>
								<li><a href="#"></a></li>
								<li><a href="#"></a></li>
								<li><a href="#"></a></li>
							</ul>
						</div>
					</div>
				</div>
				<div class="grid_12 top-1">
					<div class="box-shadow">
						<div class="wrap block-2">
							<div class="col-1">
								<h2 class="p3">
									<span class="color-1">One Month </span> Membership
								</h2>
								<div class="wrap box-1">
									<img src="images/page1-img1.jpg" alt=""
										class="img-border img-indent">

			<form action="PaymentController" method="post" id="example-form" style="display: none;">

										<script src="https://checkout.stripe.com/checkout.js"
												class="stripe-button"
												data-key="pk_test_Oh74K4gFQ22xHXTclBsYLClD"
												data-image="images/128x128.jpg" 
												data-name="M&C GYM"
												data-description="One Month Membership 100 Euro" 
												data-currency="EUR"
												data-amount="10000">
  </script>
  									<p hidden><input type="text" name="onemonth" value="100"/> </p>
										</form>
										
								
							<span class="payment-errors"></span>
							
							

							<!-- 
            The easiest way to indicate that the form requires JavaScript is to show
            the form with JavaScript (otherwise it will not render). You can add a
            helpful message in a noscript to indicate that users should enable JS.
        -->
							<script>if (window.Stripe) $("#example-form").show()</script>
							<noscript>
								<p>JavaScript is required for the registration form.</p>
							</noscript>
							<div class="extra-wrap"></div>
						</div>
					</div>
					<div class="col-2">
						<h2 class="p3">
							<span class="color-1">Buy</span> Membership
						</h2>
						<ul class="list-1">
							<li><a href="#">Buy One Month Membership</a></li>
							<li><a href="#">Buy Three Months Membership</a></li>
							<li><a href="#">Buy One Year Membership</a></li>

						</ul>

					</div>
				</div>
			</div>
	</div>
	</div>
	<div class="clear"></div>
	</div>
	</section>
	<!--==============================footer=================================-->
	<footer>
		<p>© 2014 M&C GYM</p>

	</footer>
	</div>
	<script>Cufon.now();</script>
</body>
</html>
