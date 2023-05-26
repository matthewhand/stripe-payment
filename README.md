
<!DOCTYPE html>
<html>
<body>

<h2>Stripe Payment</h2>

<p>Click the "Donate Now" button below to make a donation:</p>

<form action="https://checkout.stripe.com/pay" method="POST">
  <script
    src="https://checkout.stripe.com/checkout.js" class="stripe-button"
    data-key="pk_test_TYooMQauvdEDq54NiTphI7jx"
    data-amount="999"
    data-name="Stripe.com"
    data-description="Example charge"
    data-image="https://stripe.com/img/documentation/checkout/marketplace.png"
    data-locale="auto"
    data-zip-code="true">
  </script>
</form>

</body>
</html>
