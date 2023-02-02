# BD-GOT

## Fixação de conteúdo:

[Acesse os dados aqui](https://drive.google.com/drive/folders/1vWOXld-1rxQsFj0_QhtEpaAvD0Fbwefx)

1- Quais personagens aparecem em mais de 60 episódios?
```
select character_name, episodes_appeared from characters_v4 where episodes_appeared>60
```

![image](https://user-images.githubusercontent.com/112867913/216460964-f01b2c79-614b-4a52-81ed-9f1b3f64589f.png)
![image](https://user-images.githubusercontent.com/112867913/216462112-e7d0acca-be9b-42b1-861d-a6141487438a.png)


2- Quantos personagens apareceram pela primeira vez em 2011?
```
SELECT COUNT(first_appearance) FROM characters_v4 WHERE first_appearance = '2011'
SELECT COUNT(first_appearance) FROM characters_v4
```
![image](https://user-images.githubusercontent.com/112867913/216464829-3414d19b-ea3d-4114-bfc9-1aaab2561a41.png)
![image](https://user-images.githubusercontent.com/112867913/216466236-e86731ab-0463-411d-a3d6-2db27ff3937e.png)

![image](https://user-images.githubusercontent.com/112867913/216470514-5796b964-1627-4ac4-b50c-fd9c630363e8.png)


