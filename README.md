# ynab-transaction-resurrector

Allows you to resurrect YNAB transactions that you rejected or deleted.

## How this works

This uses the YNAB API to read your transactions. It presents you with your transactions and allows you to select which ones you want to resurrect. The resurrection does not actually undelete your transactions but creates new ones. This is due to an API limitation.

- The new transactions that get created will need to be approved and are flagged with the color red.

- Since the old, deleted transactions aren't themselves resurrected, they'll continue to show up in the app if you refresh it.

## Hosted version

https://basvo.github.io/ynab-transaction-resurrector/

## Credits

Original credits to Alan Russian (https://github.com/alanrussian/ynab-transaction-resurrector)

I just fixed a small issue with Material UI and ran into the memo max length issue when restoring 100+ transactions I accidentally removed from YNAB.
