# Hundarnas Hotell - Hemsida

Hej Darci och Grace! Här förklarar vi hur ni ändrar saker på er hemsida.

## Hur ni ändrar priser

1. Öppna filen `index.html` (i en textredigerare, t.ex. TextEdit eller VS Code)
2. Sök efter "Priser" — då hittar ni den här biten:

```html
<div class="price-row">
  <span>Promenad</span>
  <span class="kr">30 kr</span>
</div>
```

3. Byt ut siffran (t.ex. `30 kr` till `50 kr`) och spara filen
4. Det finns tre priser: Promenad, Hundpassning 1 timme, och Hundpassning 1 dag

## Hur ni ändrar text

Sök efter texten ni vill ändra i `index.html`. T.ex. om ni vill ändra "Vi tar vilken hund som helst" — sök efter den meningen, skriv om den, och spara.

Tips: Ändra bara texten mellan `>` och `<`, inte de konstiga taggarna runtomkring!

## Hur ni lägger upp ändringarna

Efter att ni sparat filen, kör dessa kommandon i terminalen:

```
cd ~/hundarnas-hotell
git add .
git commit -m "Ändrade priser"
git push
```

Vänta ca 1 minut, sen syns ändringen på hemsidan!

## Länk till hemsidan

https://lingabton.github.io/hundarnas-hotell/

## QR-kod

Filen `qr-kod.png` i den här mappen är en QR-kod som leder till hemsidan. Skriv ut den och klistra på era flygblad!
