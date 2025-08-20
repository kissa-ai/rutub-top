# rutub-top
<!DOCTYPE html>
<html>
<head>
    <title>TurboWarp Rutube Widget</title>
    <style>
        body { 
            font-family: Arial, sans-serif; 
            max-width: 600px; 
            margin: 20px auto;
            padding: 20px;
            line-height: 1.6;
        }
        code { 
            background: #f4f4f4; 
            padding: 15px; 
            display: block;
            border-radius: 5px;
            overflow-x: auto;
            white-space: pre-wrap;
        }
        .btn {
            background: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            margin: 10px 0;
        }
        .btn:hover {
            background: #45a049;
        }
    </style>
</head>
<body>
    <h1>🎯 TurboWarp Rutube Widget</h1>
    <p>Простой виджет для проверки подписчиков канала Rutube прямо в TurboWarp</p>
    
    <h2>📋 Как использовать:</h2>
    <ol>
        <li>Откройте <a href="https://turbowarp.org/" target="_blank">TurboWarp</a> в браузере</li>
        <li>Нажмите <strong>F12</strong> (откроется консоль разработчика)</li>
        <li>Вставьте этот код в консоль:</li>
    </ol>

    <code id="codeBlock">
// Код загружается...
    </code>

    <button class="btn" onclick="copyCode()">📋 Скопировать код</button>

    <script>
        // Весь код виджета
        const widgetCode = // Создаем круглый UI-блок
const widget = document.createElement('div');
widget.style.position = 'fixed';
widget.style.bottom = '20px';
widget.style.right = '20px';
widget.style.width = '50px';
widget.style.height = '50px';
widget.style.borderRadius = '50%';
widget.style.background = '#4CAF50';
widget.style.color = 'white';
widget.style.display = 'flex';
widget.style.alignItems = 'center';
widget.style.justifyContent = 'center';
widget.style.cursor = 'pointer';
widget.style.zIndex = '9999';
widget.style.boxShadow = '0 2px 10px rgba(0,0,0,0.2)';
widget.innerHTML = '🔍';
document.body.appendChild(widget);

// Форма для ввода ссылки
const form = document.createElement('div');
form.style.position = 'fixed';
form.style.bottom = '80px';
form.style.right = '20px';
form.style.padding = '15px';
form.style.background = 'white';
form.style.borderRadius = '10px';
form.style.boxShadow = '0 2px 10px rgba(0,0,0,0.2)';
form.style.zIndex = '9998';
form.style.display = 'none';
form.innerHTML = \\
  <input 
    type="text" 
    id="rutubeUrl" 
    placeholder="https://rutube.ru/channel/..." 
    style="width: 200px; padding: 8px; border: 1px solid #ddd; border-radius: 4px;"
  >
  <button id="fetchSubs" style="margin-top: 10px; padding: 8px 15px; background: #4CAF50; color: white; border: none; border-radius: 4px; cursor: pointer;">
    Проверить
  </button>
  <div id="result" style="margin-top: 10px; font-size: 14px;"></div>
\\;
document.body.appendChild(form);

// Открытие/закрытие формы
widget.addEventListener('click', () => {
  form.style.display = form.style.display === 'none' ? 'block' : 'none';
});

// Запрос подписчиков
document.getElementById('fetchSubs').addEventListener('click', async () => {
  const url = document.getElementById('rutubeUrl').value;
  const resultDiv = document.getElementById('result');
  
  if (!url.includes('rutube.ru/channel/')) {
    resultDiv.textContent = '❌ Введите корректную ссылку на канал';
    return;
  }

  resultDiv.textContent = '⌛️ Загрузка...';

  try {
    const response = await fetch(\\https://corsproxy.io/?\\${encodeURIComponent(url)}\\);
    const html = await response.text();
    const parser = new DOMParser();
    const doc = parser.parseFromString(html, 'text/html');
    
    // Ищем подписчиков
    const subsElement = doc.querySelector('.video-channel-subscribers-count') || 
                       doc.querySelector('.metadata-subscribers');
    const subsText = subsElement ? subsElement.textContent.trim() : 'Не найдено';
    
    resultDiv.textContent = \\Подписчики: \\${subsText}\\;
  } catch (error) {
    resultDiv.textContent = \\❌ Ошибка: \\${error.message}\\;
  }
});;
