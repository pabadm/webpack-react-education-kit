# webpack-react-education-kit
Иконки должны находиться в папке src, а все шрифты в папке public. Внутри папки public может быть папка Fonts или другая, а внутри папки src папка Icons, Images или другая. 
Главное, чтобы родительская папка была именно та, что я написал.

Сделал так, потому что существуют шрифты с форматом svg. Так они с иконками не конфликтуют и при билде используют разные папки.

Что-бы юзать иконку, нужно написать (import iconName from 'pathToIcon'), и уже в атрибут кидать iconName.
Шрифты можно прописать в файле Fonts.css и заимпортить его в index.css
