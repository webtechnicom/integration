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
stripe login --api-key pk_live_51GlK6hIV32DS3o2Yo0Pkhr9ejAVrC4gvJO7zCeCRcXN6ZOuS2K6roTR9R4khtOYM0nM7x1frTIORnmtgfodPzTBt00sY7fLvr5
Your pairing code is: humour-nifty-finer-magic
Press Enter to open up the browser (^C to quit)
stripe login
stripe login --project-name=rocket-rides
stripe login --interactive
