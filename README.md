# Cult of the Lamb

## URL for the full instructions and guides https://wheels35.github.io/CultoftheLamb/

This is a collection of basic instructions for editing your unencrypted save game file.  
You can unencrypt your save file with (https://pentalex.github.io/COTL-SaveDecryptor/) written by [Pentalex](https://pentalex.github.io/) - Github [here](https://github.com/Pentalex/COTL-SaveDecryptor) if you want to validate it yourself.

I suggest Notepad++ and the JSTool plugin. Once you open your file you can run do Plugins > JSTool > JSFormat to get a cleaner looking JSON.
>* Before doing any of the following steps PLEASE BACKUP YOUR SAVE!

If after doing any of the updates you have a green exclamation point that you cannot get rid of due to removing what it was pointing to: i.e. changing a doctrine do the following as well:

There is a section called **"Alerts"** and it lists each of the possible alerts you havent seen or checked off. In our case the Doctrine alerts. Make sure the section called **\_alerts** directly below the type you need to remove is empty like the example below, and make sure **"Total"** is set to 0 as well. This should remove your dangling alerts.

---
    "Alerts": {
        "Doctrine": {
            "_alerts": [
            ],
            "_singleAlerts": [],
            "Total": 0
---

### Quick Links
- [Unlocked Doctrine Modifying](https://github.com/Wheels35/CultoftheLamb/blob/main/doctrine_numbers.md)
- [Tarot Card IDs](https://github.com/Wheels35/CultoftheLamb/blob/main/tarot_cards.md)
- [Item IDs for Inventory Editing](https://github.com/Wheels35/CultoftheLamb/blob/main/item_list.md)
- [Divine Inspiration List](https://github.com/Wheels35/CultoftheLamb/blob/main/DivineInspirationTree.md)
- [Cooking Recipes](https://github.com/Wheels35/CultoftheLamb/blob/main/cooking_recipes.md)
