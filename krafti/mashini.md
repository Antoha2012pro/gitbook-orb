---
icon: car
---

# Машини

## Non Vehicle Items

### Vehicle Relocator

![](<../.gitbook/assets/df1961c2 8810 440f 9f81 8dff503ec173>)

The **Vehicle Relocator** is an item used to pick up a vehicle as an item, as specified in its [vehicle settings](broken-reference).

The behavior of the Relocator is influenced by the following gamerules:

* [**dropCarItemToInventory**](broken-reference) – Determines if the vehicle item is placed directly into the player's inventory.
* [**allowRelocatorWhileRiding**](broken-reference) – Specifies whether the Relocator can be used while the player is riding a vehicle.

Obtaining the Vehicle Relocator

{% code title="Command" %}
```mcfunction
/function tce:give/relocator
```
{% endcode %}

OR

![](<../.gitbook/assets/6d414c01 5370 4650 9840 135bdef4eaa9>)

***

### Spray Can

![spray\_can\_rgb](<../.gitbook/assets/d12c79b1 fff9 4719 8549 ea8aa96ece3b>) ![spray\_can\_tooltip](<../.gitbook/assets/5fc579ea 8011 4ddd a36c fa2b6cd585c5>)

The **Spray Can** is an item used to dye individual part of the vehicle, as specified in its [vehicle settings](broken-reference).

![](<../.gitbook/assets/4cf5ddab b27e 4c43 b03c 3864747e365d>)

This item can be dyed to _any_ color using a crafting table similar to leather armor (see https://minecraft.wiki/w/Dye#Dyeing\_armor).

Obtaining the Spray Can

{% code title="Command" %}
```mcfunction
/function tce:give/spray_can
```
{% endcode %}

OR

![](<../.gitbook/assets/0f226256 5c29 4670 8f41 6142b9ec7a10>)\
![](<../.gitbook/assets/e34f2901 20f5 4115 a34e f1df1d9b995f>)

## Vehicle Items (by brands)

### Chestler

![](<../.gitbook/assets/367b1140 8193 4b32 ad6e 9ee6c361aff1>)

Chestler is a fictional brand for luxury, vintage style vehicles.

#### LR

![](<../.gitbook/assets/102a7eae cdcc 4a71 8df1 b8e471b5e899>)

|  Vehicle Info |                 |
| :-----------: | :-------------: |
|      Type     | Display Entites |
|    Added in   |    0.1-indev    |
|     Brand     |     Chestler    |
|      Type     |   Convertible   |
| Dyeable Parts |        -        |
|   Top Speed   |     180km/h     |
|  No. of Seats |        3        |

Originally known as "Chestler-V6" and was changed in `0.6-indev`\
Created by [melonapple](https://www.youtube.com/channel/UCybUc1Wnr938-cnUk85hHFA), a TCE Team member, mainly using [Axiom](https://axiom.moulberry.com/). It is the **first** proper car created and ridable using TCE.

{% code title="Item" %}
```mcfunction
/function tce:give/chestler-lr
```
{% endcode %}

{% code title="Summon" %}
```mcfunction
/function tce:summon/chestler-lr
```
{% endcode %}

#### LR (New)

![](<../.gitbook/assets/1c3e50f4 0bed 4289 93b4 e94162284a63>)

|  Vehicle Info |                  |
| :-----------: | :--------------: |
|      Type     |   Resource Pack  |
|    Added in   |       1.2.1      |
|     Brand     |     Chestler     |
|      Type     |    Convertible   |
| Dyeable Parts | 5 (Body, Wheels) |
|   Top Speed   |      180km/h     |
|  No. of Seats |         4        |

Created by [melonapple](https://www.youtube.com/channel/UCybUc1Wnr938-cnUk85hHFA) using [BlockBench](https://www.blockbench.net/).

{% code title="Item" %}
```mcfunction
/function tce:give/chestler-lr_rs
```
{% endcode %}

{% code title="Summon" %}
```mcfunction
/function tce:summon/chestler-lr_rs
```
{% endcode %}

### Kangtumes

Kangtumes is a fictional brand for vintage, old style vehicles.

#### 90s

![](<../.gitbook/assets/739a43ba 033a 40d6 84b7 e6b92889227c>)

|  Vehicle Info |                 |
| :-----------: | :-------------: |
|      Type     | Display Entites |
|    Added in   |    0.5-indev    |
|     Brand     |    Kangtumes    |
|      Type     |  Single-Seater  |
| Dyeable Parts |        -        |
|   Top Speed   |     100km/h     |
|  No. of Seats |        1        |

Created by [Shillinggg](https://www.youtube.com/@shillinggg), a TCE Team member, mainly using [Axiom](https://axiom.moulberry.com/).

{% code title="Item" %}
```mcfunction
/function tce:give/kangtumes-90s
```
{% endcode %}

{% code title="Summon" %}
```mcfunction
/function tce:summon/kangtumes-90s
```
{% endcode %}

### TMC

![](<../.gitbook/assets/15bf7cfb 377c 4803 af95 b38cb599257d>)

TMC is a fictional brand for generic, utilitarian style vehicles.

#### Pickup (Double Cab)

![](<../.gitbook/assets/a1fe6866 1462 4616 b8b2 6aae9812c3c2>)

|  Vehicle Info |                  |
| :-----------: | :--------------: |
|      Type     |   Resource Pack  |
|    Added in   |     0.6-indev    |
|     Brand     |        TMC       |
|      Type     |      Pickup      |
| Dyeable Parts | 5 (Body, Wheels) |
|   Top Speed   |      155km/h     |
|  No. of Seats |         6        |

Originally known as "Chestler Pickup" and was changed in `1.0.2-indev`\
Created by [melonapple](https://www.youtube.com/channel/UCybUc1Wnr938-cnUk85hHFA) using [BlockBench](https://www.blockbench.net/). It is the first car created using resource pack.

{% code title="Item" %}
```mcfunction
/function tce:give/tmc-pickup_4door
```
{% endcode %}

{% code title="Summon" %}
```mcfunction
/function tce:summon/tmc-pickup_4door
```
{% endcode %}

#### Pickup

![](<../.gitbook/assets/a40db322 30e7 450c a6b7 076f93b244eb>)

|  Vehicle Info |                  |
| :-----------: | :--------------: |
|      Type     |   Resource Pack  |
|    Added in   |       1.2.1      |
|     Brand     |        TMC       |
|      Type     |      Pickup      |
| Dyeable Parts | 5 (Body, Wheels) |
|   Top Speed   |      155km/h     |
|  No. of Seats |         7        |

Created by [melonapple](https://www.youtube.com/channel/UCybUc1Wnr938-cnUk85hHFA) using [BlockBench](https://www.blockbench.net/).

{% code title="Item" %}
```mcfunction
/function tce:give/tmc-pickup
```
{% endcode %}

{% code title="Summon" %}
```mcfunction
/function tce:summon/tmc-pickup
```
{% endcode %}

#### Clarion

![](<../.gitbook/assets/b161dac3 afb6 462f a0c1 3e3bd7d84b57>)

|  Vehicle Info |                  |
| :-----------: | :--------------: |
|      Type     |   Resource Pack  |
|    Added in   |    1.0.5-indev   |
|     Brand     |        TMC       |
|      Type     |       Sedan      |
| Dyeable Parts | 5 (Body, Wheels) |
|   Top Speed   |      160km/h     |
|  No. of Seats |         4        |

Created by [melonapple](https://www.youtube.com/channel/UCybUc1Wnr938-cnUk85hHFA) using [BlockBench](https://www.blockbench.net/).

{% code title="Item" %}
```mcfunction
/function tce:give/tmc-clarion
```
{% endcode %}

{% code title="Summon" %}
```mcfunction
/function tce:summon/tmc-clarion
```
{% endcode %}

#### Transbox

![](<../.gitbook/assets/e5532b62 10d9 4fab a9ef e6e864819b6d>)

|  Vehicle Info |                  |
| :-----------: | :--------------: |
|      Type     |   Resource Pack  |
|    Added in   |       1.2.1      |
|     Brand     |        TMC       |
|      Type     |        Van       |
| Dyeable Parts | 5 (Body, Wheels) |
|   Top Speed   |      145km/h     |
|  No. of Seats |         6        |

Created by [melonapple](https://www.youtube.com/channel/UCybUc1Wnr938-cnUk85hHFA) using [BlockBench](https://www.blockbench.net/).

{% code title="Item" %}
```mcfunction
/function tce:give/tmc-transbox
```
{% endcode %}

{% code title="Summon" %}
```mcfunction
/function tce:summon/tmc-transbox
```
{% endcode %}

And more coming soon...
