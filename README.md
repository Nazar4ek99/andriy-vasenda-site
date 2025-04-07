# andriy-vasenda-site
Цей сайт про ведучого весіля
<!DOCTYPE html>
<html lang="uk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Андрій Васенда — Християнський ведучий та співак</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600&family=Roboto&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f9f9f9;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: linear-gradient(rgba(0,0,0,0.5), rgba(0,0,0,0.6)), url('https://example.com/microphone-image.jpg') center/cover no-repeat;
      color: white;
      text-align: center;
      padding: 80px 20px;
      animation: fadeIn 1s ease-in-out;
    }
    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 3rem;
      margin-bottom: 20px;
    }
    header p {
      font-size: 1.2rem;
      font-style: italic;
      margin-top: 10px;
    }
    .content {
      max-width: 900px;
      margin: 40px auto;
      padding: 0 20px;
      text-align: center;
    }
    .price-box {
      display: flex;
      justify-content: center;
      gap: 20px;
      flex-wrap: wrap;
      margin: 40px 0;
      animation: slideUp 1s ease-out;
    }
    .card {
      background-color: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0,0,0,0.1);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      width: 260px;
      opacity: 0;
      animation: fadeInUp 1s forwards;
    }
    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 8px 25px rgba(0,0,0,0.15);
    }
    .card h2 {
      font-size: 1.5rem;
      margin-bottom: 10px;
    }
    .card p {
      font-size: 1.2rem;
      margin-bottom: 20px;
    }
    .card a {
      text-decoration: none;
      background-color: #ff4d4d;
      color: white;
      padding: 10px 20px;
      border-radius: 30px;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }
    .card a:hover {
      background-color: #e60000;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9rem;
      color: #666;
    }

    /* Анімації */
    @keyframes fadeIn {
      from {
        opacity: 0;
      }
      to {
        opacity: 1;
      }
    }

    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes slideUp {
      from {
        transform: translateY(20px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }

    /* Плавне прокручування */
    a {
      text-decoration: none;
      color: #ff4d4d;
    }

    /* Форма */
    form {
      max-width: 600px;
      margin: 40px auto;
      background-color: #fff;
      padding: 30px;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.1);
    }
    form input, form textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border-radius: 8px;
      border: 1px solid #ddd;
    }
    form button {
      padding: 10px 20px;
      background-color: #ff4d4d;
      border: none;
      color: white;
      font-weight: bold;
      border-radius: 30px;
      cursor: pointer;
    }
    form button:hover {
      background-color: #e60000;
    }

    /* Анімація для кнопок */
    .btn {
      display: inline-block;
      padding: 12px 24px;
      font-size: 1rem;
      background-color: #ff4d4d;
      color: white;
      border-radius: 30px;
      transition: all 0.3s ease;
      text-transform: uppercase;
    }
    .btn:hover {
      background-color: #e60000;
      transform: scale(1.1);
    }

    /* Модальне вікно */
    .modal {
      display: none;
      position: fixed;
      z-index: 1;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      background-color: rgba(0, 0, 0, 0.7);
    }
    .modal-content {
      background-color: #fff;
      margin: 15% auto;
      padding: 20px;
      width: 50%;
      border-radius: 12px;
      box-shadow: 0 4px 20px rgba(0, 0, 0, 0.2);
    }
    .modal-header {
      font-size: 1.5rem;
      margin-bottom: 10px;
    }
    .modal-close {
      color: #aaa;
      font-size: 2rem;
      font-weight: bold;
      cursor: pointer;
    }
    .modal-close:hover,
    .modal-close:focus {
      color: black;
      text-decoration: none;
      cursor: pointer;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 2rem;
      }
      .card {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Андрій Васенда</h1>
    <p>"Музика — це душа, що говорить, навіть коли мовчить серце."</p>
  </header>

  <div class="content">
    <h2>Про Андрія Васенду</h2>
    <p>Андрій Васенда — не просто ведучий і співак. Він — людина, яка несе світло через музику та слова. Його творчість ґрунтується на глибокій віри, яка надає йому сили та натхнення. Кожен його виступ — це не просто пісня чи ведення заходу, а й духовний досвід, через який він ділиться частинкою свого серця та духу.</p>

    <h2>Що надихає Андрія?</h2>
    <p>Андрій не просто виконує пісні — він передає в них своє бачення світу, надію і віру, що все можливо за допомогою Божої благодаті. Його творчість є натхненною не лише досвідом власного життя, але й глибокими біблійними істинами. Це мандрівка через музику, яка дозволяє відчути присутність Бога у кожному моменті.</p>

    <h2>Авторський альбом</h2>
    <p>Музичний альбом Андрія — це збірка пісень, що торкаються найглибших куточків душі. Кожна композиція пропонує слухачу шлях до роздумів, прощення та внутрішнього миру. Це музика, що говорить мовою серця, без слів, та несе послання надії для кожного.</p>

    <h2>Ціни на послуги</h2>
    <div class="price-box">
      <div class="card">
        <h2>Спів</h2>
        <p>350$</p>
        <a href="https://instagram.com/vasenda_andriy" target="_blank">Замовити</a>
      </div>
      <div class="card">
        <h2>Ведучий + Спів</h2>
        <p>500$</p>
        <a href="https://instagram.com/vasenda_andriy" target="_blank">Замовити</a>
      </div>
    </div>

    <h2>Залиште заявку</h2>
    <button class="btn" onclick="openModal()">Залишити заявку</button>

    <!-- Модальне вікно -->
    <div id="myModal" class="modal">
      <div class="modal-content">
        <div class="modal-header">
          <span class="modal-close" onclick="closeModal()">&times;</span>
          <h2>Форма замовлення</h2>
        </div>
        <form id="orderForm">
          <input type="text" placeholder="Ваше ім'я" required>
          <input type="email" placeholder="Ваш email" required>
          <textarea placeholder="Ваше повідомлення" required></textarea>
          <button type="submit">Надіслати заявку</button>
        </form>
      </div>
    </div>
  </div>

  <footer>
    © 2025 Андрій Васенда | Instagram: <a href="https://instagram.com/vasenda_andriy" target="_blank">@vasenda_andriy</a> | Тел: +380 96 813 41 75
  </footer>

  <script>
    // Відкриття модального вікна
    function openModal() {
      document.getElementById('myModal').style.display = 'block';
    }

    // Закриття модального вікна
    function closeModal() {
      document.getElementById('myModal').style.display = 'none';
    }

    // Валідація форми
    document.getElementById('orderForm').addEventListener('submit', function(event) {
      event.preventDefault();
      alert('Ваша заявка надіслана!');
      closeModal();
    });

    
  </script>
</body>
</html>
