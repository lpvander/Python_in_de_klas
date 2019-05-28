<img src="/Users/lisa/Python_in_de_klas/Module-Aardrijkskunde/Les 1/Logo cs-certificate.jpg"
style="zoom:20%" align="right">

### Module Aardrijskunde Les 3 Werkblad a

### XxxDatatypes omzettenXxx

Aan het einde van de les kun jij:

- Xxx
- Xxx

In deze lessen ga jij xxxxxxxxxxxxxx

**Even opfrissen!**
Vorige week hebben we geleerd hoe we de data van een aardbeving kunnen inlezen in python, en hoe we deze ingelezen data in stukjes kunnen hakken, zodat we bijvoorbeeld iets kunnen printen over alléén de magnitude. 

Onderstaand plaatje is een stukje van de data over aardbevingen die in de target_url te vinden is. 

<img src="/Users/lisa/Python_in_de_klas/Module-Aardrijkskunde/Les 1/data.png"
style="zoom:70%">

```python
target_url = 'aardbevingen_data.csv' # Dit is 'zogenaamd' de code die aangeeft waar dit bestand terug te vinden is.
```

1) Welke van deze codes leest op de juiste manier de data uit de target_url in en slaat deze op in een variabele genaamd data? Schrijf de goede code over in je schrift!

```python
- data = readlines(target_url)

- data = target_url

- data = readlines
        
- target_url = readlines(data)
```

2) Hoe zorgen we nu dat we alleen de tiende regel inlezen en dit opslaan in een variabele genaamd regel_10? Schrijf de juiste code in je schrift.

3) We willen de aardbeving inlezen die plaatsvond op 29 januari 1965 en deze opslaan in een variabele genaamd aardbeving_29_januari. Schrijf de juiste code waarmee je deze aardbeving kunt inlezen in je schrift.

![image-20190520175640059](/Users/lisa/Python_in_de_klas/Module-Aardrijkskunde/Les 2/data_regel_0_ingelezen.png)

5) Maak de code hieronder af zodat de data in opgehakte stukjes in een lijst komt te staan.

```python
regel_1 = data[0]

lijst_van_opgehakte_regel_1 = regel_1.split(... ... ...) #vul de missende tekens in op de stippellijnen.
```

6) Hieronder staan vijf codes waarmee een stukje data over de eerste aardbeving uit de afbeelding op de eerste pagina wordt geprint. Er wordt gebruik gemaakt van de variabelen regel_1 en lijst_van_opgehakte_regel_1 die je in opdracht 5 gemaakt hebt. Wat printen deze codes uit? Let op, er staan ook foute codes tussen! 

Schrijf de uitvoer in je schrift.

```python
1. print(lijst_van_opgehakte_regel_1[0])               
```

```python
2. print(regel_1[6])   
```

```python
3. magnitude = lijst_van_opgehakte_regel_1[7]
print(magnitude)
```

```python
4. depth = lijst_van_opgehakte_regel_1[5]
print(depth)
```

```python
5. print(lijst_van_opgehakte_regel_1[6]
```

------

Einde werkblad! Ben je klaar, leg dan je schrift bovenaan op je tafel 

------

