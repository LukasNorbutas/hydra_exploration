The data contains parsed scrapes of a Russian cryptomarket called Hydra. Hydra is a person-to-person illegal drug marketplace on the "Dark Web" (accessible via TOR browser). The basic layout resembles eBay or any other online marketplace.

The scrape (mirror of the website) was conducted by myself in 2017 for another project.
The parsed datafiles used in this notebook contain:
<br>
<br>
1) Item pages - pages of **12,378 drug items** on the marketplace, each containing: ID, name, description, seller, shipping locations of each item.
2) Buyer profiles - profile pages of **101,965 buyer profiles**, each containing nickname, number of transactions and date of registration.
3) Feedback messages - **574,274 buyer feedback messages** left for each item/seller after a transaction. It contains buyer nickname (author of message), seller nickname (from whom the author bought an item), item ID, date of message, buyer's location
4) (omitted in this notebook) Price of items - Prices for different weights of (most) items. 
<br>

![](https://github.com/LukasNorbutas/hydra_exploration/blob/master/screenshot.png?raw=true)
