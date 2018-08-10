# Как забрать токены

Вы можете воспользоваться сервисом MyEtherWallet.

перейдите на [страницу отправки](https://www.myetherwallet.com/#send-transaction)

![Unlock wallet](https://github.com/belukov/instr/blob/master/images/mew_unlock.png)

Выберите "Private key" в блоке "How would you like to access your wallet?". В появившее справа поле ввода вставьте полученный приватный ключ. и нажмите "Unlock"

Для того чтобы воспользоваться токенами, нужно показать сервису токен:

![Add token](https://github.com/belukov/instr/blob/master/images/mew_add_token.png)

Справа, в блоке "Token Balances" нажмите "Add custom token". Заполните поля фррмы

* Token Contract Address - 0x27695E09149AdC738A978e9A678F99E4c39e9eb9
* Token Symbol - KICK
* Decimals - 8

И нажмите "Save". Вы должны увидеть баланс токенов: 

![Token balance](https://github.com/belukov/instr/blob/master/images/mew_token_balance.png)

Теперь можно их отправить. Для этого в основной форме страницы:
* укажите адрес получателя, 
* выберите KICK вместо ETH,
* под полем "Amount to send" нажмите "Send entire balance",
* в поле "Gas limit" введите 200000


![Transaction params](https://github.com/belukov/instr/blob/master/images/mew_transaction_params.png)

И нажмите "Generate transaction", затем "Send transaction"


