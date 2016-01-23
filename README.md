# hook
adds a hook after a payment

# prerequisites

setup `basic` ledger

# description

hook is a typical pattern in programming languages and can happen:

* before a credit
* after a credit (more usual)

# implementation

in bash the implementation is quite simple

run the hook before or after the insert command

hook can be combined as a conjunction to produce interesting workflows and smart contracts

# example

    AMOUNT=5
    credit insert $WORKBOT $AMOUT '' $WEBID 
    notify-send -t 1000 "You got paid! $AMOUNT"

