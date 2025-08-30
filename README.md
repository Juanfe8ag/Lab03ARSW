## Primera parte: ejercicio introductorio al manejo de Spring y la configuración basada en anotaciones.

Para esta primera parte se hace una introducción a la inyección de dependencias con SpringBoot. Para ello se usan dos etiquetas (@Autowired y @Service).

Para ello usamos las etiquetas @Service para GrammarChecker y para EnglishSpellChecker, puesto que seran nuestros Beans y se usa @Autowired en el atributo de la clase GrammarChecker llamado sc. Asi, usando el Main va a usar el bean de GrammarChecker y, por ende, creara sus atributos, ahi es donde se creara EncglishSpellChecker. Al
crearlo se verá asi:

![Screenshot 2025-08-30 084140.png](img%2FScreenshot%202025-08-30%20084140.png)

Y para cuando se cambia la etiqueta @Service de EnglishSpellChecker a SpanishSpellChecker el resultado cambia asi:

![Screenshot 2025-08-30 084410.png](img%2FScreenshot%202025-08-30%20084410.png)