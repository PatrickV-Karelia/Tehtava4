# AppLogger

Kaksi eri projektia. Toinen on classlib-tyyppinen moduuli AppLogger, ja toinen on konsolisovellus App, joka käyttää hyväkseen ensimmäisen moduulin palvelua (Logger.Log). 
Projektit ovat linkitetty toisiinsa siten, että App käyttää AppLoggeria.
Apploggeriin on asennettu Humanizer-kirjasto nuget-hakemistosta.

Sovelluksen suoritus onnistuu PowerShellissä valitsemalla App -kansion ja siellä komennolla dotnet run.