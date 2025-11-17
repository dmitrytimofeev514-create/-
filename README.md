# -<!DOCTYPE html>
<html lang="ru">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
Памятные Места Нерюктяинского Наслега
<link rel="stylesheet" href="styles.css">
</head>
<body>
<header Экскурсия по памятным местам Нерюктяинского наслега>
<h1>Приветствую, в нашем сайте, мы предостовляем информацию о Нерюктяинском наслеге креативно!</h1>
</header>
<main>
<p>Это Экскурсовод Людвик.</p>
<button id="themeButton">Начать Экскурсию по Нерюктяинскому наслегу</button>
</main>
</body>
</html>
// script.js
document.getElementById('themeButton').addEventListener('click', () => {
document.body.classList.toggle('dark-theme');
});

// Дополнительные стили для темной темы
const style = document.createElement('style');
style.textContent = `
dark-theme {
background-color: #333;
color: #f4f4f9;
}
dark-theme header {
background-color: #3700b3;
}
dark-theme button {
background-color: #bb86fc;
}
`;
document.head.appendChild(style);
