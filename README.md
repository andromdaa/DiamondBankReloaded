# DiamondBankReloaded
A remake of https://www.spigotmc.org/resources/the-diamond-bank.72020/ for later Spigot versions, and open source.

This README is a modification of the one from https://www.spigotmc.org/resources/the-diamond-bank.72020/, all credit to the author


Overview:
The Diamond Bank provides a simple diamond based economy compatible with Vault in Spigot. Players balances consist of both a bank balance and physical diamonds.

Benefits:

Easy to use and very little configuration
Pay for items with diamond you have in your bank and if not enough pay with the diamond on your person.

Features:

Players can deposit diamond on-hand into their diamond bank account.
Players can withdraw diamond from their diamond bank account to their inventory.
Diamond gems are the base denomination, Diamond blocks are 9x just like in game.
Admins can add, remove or set diamond for players.
Vault compatible for online and offline transactions.
Stores diamond bank balances directly in persistent player data

Commands:
/bank - check your balance
/bank balance - check your balance
/bank deposit - deposit diamond in hand
/bank deposit all - deposit all diamond in inventory
/bank pay <player> <amount> - pay an amount of diamond to a player
/bank withdraw <amount> - withdraw amount of diamond
/bank withdraw all - withdraw all your diamond
/bank transfer <player> <amount> - transfer to player amount of diamond
/bank add <player> <amount> - add amount of diamond to player balance
/bank remove <player> <amount> - remove amount of diamond from player balance
/bank set <player> <amount> - set player's balance
/bank baltop - list the top bank balances
/bank balance <player> - get a player's balance
/bank reload - reloads the configuration


Permissions:
diamondbank.balance - enables using the bank balance command (default: true)
diamondbank.deposit - enables using the bank deposit (default: true)
diamondbank.withdraw - enables using the bank withdraw command (default: true)
diamondbank.transfer - enables using the bank transfer or bank pay command (default: true)
diamondbank.pay - enables using the bank transfer or bank pay command (default: true)
diamondbank.add - enables using the bank add command (default: op)
diamondbank.remove - enables using the bank remove command (default: op)
diamondbank.set - enables using the bank set command (default: op)
diamondbank.baltop - enables using the bank baltop command (default: op)
diamondbank.balance.others - enables using the bank balance <player> command (default: op)
diamondbank.reload - enables using the bank reload command (default: op)

Known Issues:
Players that do /withdraw all on a large bank balance might cause lag.
