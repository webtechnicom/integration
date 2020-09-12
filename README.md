# stripe
repository
git@github.com:webtechnicom/integration.git
Ready! You're now waiting to receive API request logs (^C to quit)
stripe payment_intents create --amount=100 --currency=usd
stripe payment_intents create --amount=100 --currency=usd --stripe-version 2019-03-14
stripe post /v1/payment_intents \
    -d amount=2000 \
    -d currency=usd \
    -d "payment_method_types[]=card"
