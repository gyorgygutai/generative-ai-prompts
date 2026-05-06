---
{"dg-publish":true,"permalink":"/food-photography/food-names-in-english/","dg-note-properties":{}}
---

## Prompt

```button
name Copy Prompt
type command
action Templater: Insert Copy Prompt
```

```button
name Send to Draw Things
type command
action Templater: Insert Send to Draw Things
```

```prompt
Here's every dish with English translation:  

**Előételek és levesek — Starters & Soups**  
* Harcsa haltepertő — Crispy catfish fillet  
* Süllő haltepertő — Crispy pike-perch fillet  
* Kacsazúza ravioli — Duck gizzard ravioli  
* Halászlé harcsával 4,5 dl — Hungarian fisherman's soup with catfish (large)  
* Halászlé harcsával 2,5 dl — Hungarian fisherman's soup with catfish (small)  
* Vasárnapi húsleves — Sunday chicken broth  
* Szezonális leves — Seasonal soup  
**50's Burgerek — 50's Burgers**  
* Tisza-tó 50 éves hamburger tál — Lake Tisza 50th anniversary fish burger plate  
* Hortobágyi Nemzeti Park 50 éves hamburger tál — Hortobágy National Park 50th anniversary Angus burger plate  
**Főételek — Main Courses**  
* Harcsapaprikás — Catfish paprikash  
* Süllő filé roston vajtökkel — Grilled pike-perch fillet with butternut squash  
* Bőrén sült csirkemell filé, zöldborsós rizottó — Crispy skin chicken breast, green pea risotto  
* Kacsacomb, káposztás cvekedli — Duck leg, sauerkraut noodles  
* Borjúpaprikás – kovászos kenyér tunkolós — Veal paprikash with sourdough bread  
* Rántott csirkecomb filé — Breaded chicken thigh fillet  
* Marhapofa — Braised beef cheek  
* Túrós csusza — Cottage cheese pasta  
* Heti ajánlat: Cordon bleu, burgonyapüré — Weekly special: Cordon bleu, mashed potato  
* Heti ajánlat: Bolognai — Weekly special: Bolognese  
**Desszertek — Desserts**  
* La Túrógombóc — Cottage cheese dumplings  
* Apa szilvása — Father's plum cake  
**Gyerek — Kids**  
* Rántott vagy pirított pipihús falatok — Breaded or pan-fried chicken bites  
**Vega, vegán — Vegetarian, Vegan**  
* Szezonális leves vega/vegán verzióban — Seasonal soup vegan version  
* Vajtök „főzelék" — Butternut squash stew  
  
  
Honest split — based on training data likelihood, not tested:  

**Will recognize confidently:**  
* Ravioli  
* Risotto  
* Cordon bleu  
* Bolognese  
* Burger (both)  
* Duck leg  
* Breaded chicken  
* Beef cheek  
* Sourdough bread  

**Will recognize the dish type but miss the Hungarian specifics:**  
* Paprikash (csirkepaprikás is internationally known, harcsa/borjú versions less so — will generate generic paprikash)  
* Fisherman's soup — "Hungarian fish soup" might work, but Tiszafüredi specifics lost  
* Cottage cheese dumplings (túrógombóc) — dumplings yes, the specific form probably not  
* Butternut squash stew — will generate something plausible but wrong  

**Will likely hallucinate or fail:**  
* Haltepertő — no concept of this specific Hungarian crispy fish preparation  
* Túrós csusza — cottage cheese pasta is obscure enough to get weird results  
* Káposztás cvekedli — cvekedli is too Hungarian-specific  
* Pásztortahonya — completely unknown outside Hungary  
* Lúdgége tészta — goose neck pasta shape, zero international training data  
**Strategy for the unrecognizable ones:** describe them compositionally in the prompt rather than by name. "Crispy fried catfish strips, pickled red onion, tomato salsa, toast" will work better than "harcsa haltepertő."  
Want me to write prompt templates for each dish?  
```

### Attachments