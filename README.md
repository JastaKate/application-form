# Application form :bookmark_tabs:

![Форма ](https://user-images.githubusercontent.com/106038032/172047496-1f5498e7-32d0-4c47-939b-b49dcf7afcce.gif)


The form was created to receive data about a new user registering on the site 

<b>Input</b> elements of type <b>radio</b> is used to select gender and age:

    <input type="radio" name="form_sex" value="1" id="form_sex1">
    <label for="form_sex1">Мужской</label>
    <input type="radio" name="form_sex" value="2" id="form_sex2">
    <label for="form_sex2">Женский </label>

You can use the tag <b>select</b> to select the city where you live:
    
    <select name="form_select">
    <option value="1">Москва</option>
    <option value="2">Санкт-Петербург</option>
    
The <b>multiple</b> attribute allows you to select multiple items from the list. Grouping using the <b>optgroup</b> tag. With their help, you can choose several areas of your professional activity:    

    <select multiple="" size="7" name="form_select">
    <optgroup label="Журналистика">
    <option value="1">Бизнес</option>
    <option value="2">Экология</option>
    
Using the <b>textarea</b> tag, we create a field for entering additional information that the user wants to enter. Using the <b>textarea disabled</b> attribute, we make the input field inactive:

    <textarea disabled="" name="form_bigtext" rows="5">Условия соглашения</textarea>


# Форма:bookmark_tabs:
Форма была создана для получения данных о новом пользователе, регистрирующемся на сайте 

Атрибут type тега <b>input</b> со значением <b>radio</b> используется для выбора пола и возраста:

    <input type="radio" name="form_sex" value="1" id="form_sex1">
    <label for="form_sex1">Мужской</label>
    <input type="radio" name="form_sex" value="2" id="form_sex2">
    <label for="form_sex2">Женский </label>

Вы можете использовать тег <b>select</b>, чтобы выбрать город, в котором вы живете:

    <select name="form_select">
    <option value="1">Москва</option>
    <option value="2">Санкт-Петербург</option>
    
Атрибут <b>multiple</b> позволяет выбрать несколько пунктов из списка. Группировка с помощью тега <b>optgroup</b>. С их помощью вы можете выбрать несколько областей своей профессиональной деятельности:

    <select multiple="" size="7" name="form_select">
    <optgroup label="Журналистика">
    <option value="1">Бизнес</option>
    <option value="2">Экология</option>
    

С помощью тега <b>textarea</b> создаем поле для ввода дополнительной информации, которую захочет ввести пользователь. С помощью атрибута <b>textarea disabled</b> делаем поле ввода неактивным:

    <textarea disabled="" name="form_bigtext" rows="5">Условия соглашения</textarea>
    
    

