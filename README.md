<div align="center">

## Features of gb_banking

</div>

- **Multiple bank accounts** for your character.
- Manual **ESX paycheck** account change.
- **Debit cards** with possibility to change **dc number and PIN code**.
- **Credit cards** with possibility to change **cc number and PIN code**. - **TO DO**
- You can pay using **not yours debit card**.
- Money transfer on **account number**.
- Your account **login and password**.
- Account **4 digit backup code**.
- Exploit protection.
- **?** Dynamic identifier change

<div align="center">

## Requirements

</div>

- [es_extended](https://github.com/esx-framework/es_extended/tree/v1-final)
- [mysql-async](https://github.com/brouznouf/fivem-mysql-async)
- [esx_identity](https://github.com/esx-framework/esx_identity)

<div align="center">

## Installation

</div>

- Put `gb_banking` folder into your `resources` folder.
- Add `ensure gb_banking` in your `server.cfg` file.
- Import `gb_banking.sql` into your database.
- Delete your server data `cache` folder.
<br>
<div align="center">

If you want to make **ESX paycheck** work with main accounts

</div>

- Navigate to `installation/es_extended/server` folder.
- Copy `paycheck.lua`.
- Paste it into `es_extended/server` folder and replace.
<br>
<div align="center">

If you want to make **esx_shops** work with debit cards

</div>

- Navigate to `installation/esx_shops` folder.
- Replace and add events from `server.lua` into your shop server script.
- Add function and replace fragment of code from `client.lua` in your shop client script.

<div align="center">

## FAQ

</div>

- How can i change the language?<br />
In the **config.lua** file.

- Is it compatibile with ESX?<br />
Yes script is **ESX only**.

- Where can i get help?<br />
By openning [github issue](https://github.com/Nyxonn/gb_banking/issues).
