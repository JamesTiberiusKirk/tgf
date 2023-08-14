# Telegram Framework (tgf)
This is an opinionated wrapper framework for [telegram-bot-api](https://github.com/go-telegram-bot-api/telegram-bot-api).
With the goal of building telegram bots with [journeys](#journeys) in mind 

## Journeys
A journey in this case is a term borrowed from the web world where a user could start a journey of navigating through a certain set of pages (e.g. clicks buy -> checkout -> address form page -> banking info form page -> thank you for purchase)
So in this case we are building journeys for telegram commands where you can chain handlers together in an array and have the user navigate from handler to handler.


## TODOs:
- [ ]Support for webhooks
- [ ]Add support for global middleware
    - [ ]Pre handler call
    - [ ]Post handler call
    - [ ]Pre journey
    - [ ]Post journey

## Example bots
- [ShoppingListBot](https://github.com/JamesTiberiusKirk/ShoppingListBot)
