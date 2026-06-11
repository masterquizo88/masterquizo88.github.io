<!DOCTYPE html>
<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Викторина KondiZ</title>
  <style>
    *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

    body {
      font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
      background: #FDF8F2;
      min-height: 100vh;
      display: flex;
      align-items: flex-start;
      justify-content: center;
      padding: 2rem 1rem;
      color: #2C2C2A;
    }

    .card {
      background: #fff;
      border-radius: 16px;
      box-shadow: 0 4px 24px rgba(0,0,0,0.08);
      padding: 2rem 2rem 2.5rem;
      max-width: 620px;
      width: 100%;
    }

    .header {
      display: flex;
      align-items: center;
      gap: 12px;
      margin-bottom: 1.75rem;
      padding-bottom: 1.25rem;
      border-bottom: 1px solid #F0EBE0;
    }

    .header-logo {
      width: 44px;
      height: 44px;
      background: #BA7517;
      border-radius: 12px;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 22px;
    }

    .header-text h1 {
      font-size: 18px;
      font-weight: 600;
      color: #2C2C2A;
    }

    .header-text p {
      font-size: 13px;
      color: #888780;
      margin-top: 2px;
    }

    .progress-row {
      display: flex;
      align-items: center;
      justify-content: space-between;
      margin-bottom: 8px;
    }

    .q-counter {
      font-size: 12px;
      color: #888780;
      letter-spacing: 0.04em;
      text-transform: uppercase;
      font-weight: 500;
    }

    .score-badge {
      font-size: 12px;
      color: #854F0B;
      background: #FAEEDA;
      padding: 3px 10px;
      border-radius: 999px;
      font-weight: 500;
    }

    .progress-bar {
      height: 5px;
      background: #F0EBE0;
      border-radius: 3px;
      margin-bottom: 1.5rem;
      overflow: hidden;
    }

    .progress-fill {
      height: 100%;
      background: linear-gradient(90deg, #EF9F27, #BA7517);
      border-radius: 3px;
      transition: width 0.4s ease;
    }

    .q-text {
      font-size: 17px;
      font-weight: 500;
      color: #2C2C2A;
      margin-bottom: 1.25rem;
      line-height: 1.55;
    }

    .options-grid {
      display: flex;
      flex-direction: column;
      gap: 10px;
      margin-bottom: 1rem;
    }

    .opt-btn {
      background: #fff;
      border: 1.5px solid #E8E2D8;
      border-radius: 12px;
      padding: 13px 16px;
      text-align: left;
      font-size: 15px;
      color: #2C2C2A;
      cursor: pointer;
      transition: background 0.15s, border-color 0.15s, transform 0.1s;
      display: flex;
      align-items: center;
      gap: 12px;
      width: 100%;
    }

    .opt-btn:hover:not(:disabled) {
      background: #FDF8F2;
      border-color: #BA7517;
      transform: translateX(2px);
    }

    .opt-btn.correct {
      background: #EAF3DE;
      border-color: #3B6D11;
      color: #27500A;
    }

    .opt-btn.wrong {
      background: #FCEBEB;
      border-color: #A32D2D;
      color: #501313;
    }

    .opt-btn:disabled { cursor: default; transform: none; }

    .letter-badge {
      width: 26px;
      height: 26px;
      border-radius: 50%;
      background: #F5EFE5;
      color: #854F0B;
      font-size: 12px;
      font-weight: 600;
      display: flex;
      align-items: center;
      justify-content: center;
      flex-shrink: 0;
      transition: background 0.15s;
    }

    .opt-btn.correct .letter-badge { background: #C0DD97; color: #27500A; }
    .opt-btn.wrong .letter-badge { background: #F7C1C1; color: #501313; }

    .feedback {
      margin-top: 0.75rem;
      font-size: 14px;
      color: #5F5E5A;
      padding: 11px 14px;
      border-radius: 10px;
      background: #FDF8F2;
      border-left: 3px solid #EF9F27;
      line-height: 1.55;
      display: none;
    }

    .next-btn {
      margin-top: 1.25rem;
      padding: 13px 28px;
      background: #BA7517;
      color: #FAEEDA;
      border: none;
      border-radius: 10px;
      font-size: 15px;
      font-weight: 500;
      cursor: pointer;
      transition: background 0.15s, transform 0.1s;
      display: none;
    }

    .next-btn:hover { background: #854F0B; transform: translateY(-1px); }
    .next-btn:active { transform: translateY(0); }

    /* Result screen */
    .result-screen {
      text-align: center;
      padding: 1rem 0 0.5rem;
    }

    .result-emoji { font-size: 56px; margin-bottom: 1rem; }

    .result-score-big {
      font-size: 56px;
      font-weight: 700;
      color: #BA7517;
      line-height: 1;
      margin-bottom: 4px;
    }

    .result-out-of {
      font-size: 14px;
      color: #888780;
      margin-bottom: 1.5rem;
    }

    .result-msg {
      font-size: 17px;
      font-weight: 500;
      color: #2C2C2A;
      margin-bottom: 1.75rem;
      line-height: 1.5;
    }

    .stats-row {
      display: flex;
      gap: 12px;
      justify-content: center;
      margin-bottom: 2rem;
    }

    .stat-chip {
      font-size: 13px;
      padding: 7px 16px;
      border-radius: 999px;
      font-weight: 500;
    }

    .stat-chip.ok { background: #EAF3DE; color: #27500A; }
    .stat-chip.bad { background: #FCEBEB; color: #501313; }

    .retry-btn {
      padding: 13px 36px;
      background: #BA7517;
      color: #FAEEDA;
      border: none;
      border-radius: 10px;
      font-size: 15px;
      font-weight: 500;
      cursor: pointer;
      transition: background 0.15s;
    }

    .retry-btn:hover { background: #854F0B; }

    @media (max-width: 480px) {
      body { padding: 1rem 0.75rem; }
      .card { padding: 1.5rem 1.25rem 2rem; }
      .result-score-big { font-size: 44px; }
    }
  </style>
</head>
<body>
<div class="card">
  <div class="header">
    <div class="header-logo">🍪</div>
    <div class="header-text">
      <h1>Викторина KondiZ</h1>
      <p>Проверь свои знания о фабрике</p>
    </div>
  </div>
  <div id="quiz-body"></div>
</div>

<script>
const questions = [
  {
    q: "В каком году была зарегистрирована фабрика KondiZ?",
    opts: ["2010", "2013", "2015", "2017"],
    correct: 1,
    hint: "Предприятие зарегистрировано в марте 2013 года, а первая линия запущена в декабре 2013 — начале 2014 года."
  },
  {
    q: "В каком городе расположена фабрика KondiZ?",
    opts: ["Алматы", "Астана", "Семей", "Шымкент"],
    correct: 2,
    hint: "Фабрика находится по адресу: Республика Казахстан, Абайская область, г. Семей, ул. Сорокина, д. 39."
  },
  {
    q: "Какова годовая производственная мощность фабрики?",
    opts: ["5 000 тонн", "10 000 тонн", "22 000 тонн", "50 000 тонн"],
    correct: 2,
    hint: "Производственная мощность фабрики достигает 22 000 тонн мучных кондитерских изделий в год."
  },
  {
    q: "Сколько наименований продукции выпускает KondiZ?",
    opts: ["Около 30", "Около 50", "Около 75", "Более 100"],
    correct: 3,
    hint: "На сегодняшний день фабрика выпускает более 100 наименований изделий."
  },
  {
    q: "Какой сертификат подтверждает соответствие продукции религиозным стандартам?",
    opts: ["Kosher", "Халал", "Vegan", "Bio"],
    correct: 1,
    hint: "Вся продукция KondiZ официально сертифицирована по стандартам Халал."
  },
  {
    q: "Какие международные стандарты качества внедрены на фабрике?",
    opts: ["ISO 9001 и ISO 14001", "ISO 9001 и ISO 22000", "ISO 45001 и ISO 22000", "HACCP и GMP"],
    correct: 1,
    hint: "Фабрика сертифицирована по международным системам менеджмента качества и безопасности пищевых продуктов ISO 9001 и ISO 22000."
  },
  {
    q: "Сколько сотрудников работает на предприятии?",
    opts: ["Около 50", "Около 100", "Более 200", "Более 500"],
    correct: 2,
    hint: "На предприятии работает более 200 высококвалифицированных сотрудников."
  },
  {
    q: "Какой вид дополнительной продукции производит KondiZ помимо печенья?",
    opts: ["Соки", "Макаронные изделия", "Шоколад", "Мороженое"],
    correct: 1,
    hint: "На мощностях компании также налажено производство макаронных изделий, которые отмечаются за хорошее соотношение цены и качества."
  },
  {
    q: "Серия «Рыбки» относится к какому виду продукции?",
    opts: ["Затяжное печенье", "Сахарное печенье", "Крекеры", "Сдобно-отсадное печенье"],
    correct: 2,
    hint: "«Рыбки» — это популярная серия крекеров (классические и с какао)."
  },
  {
    q: "На какой улице расположена фабрика KondiZ в г. Семей?",
    opts: ["ул. Ленина", "ул. Абая", "ул. Сорокина", "ул. Гагарина"],
    correct: 2,
    hint: "Полный адрес: 071400, Казахстан, Абайская область, г. Семей, ул. Сорокина, 39."
  }
];

let current = 0, score = 0, answered = false;
const letters = ['А', 'Б', 'В', 'Г'];

function render() {
  const body = document.getElementById('quiz-body');
  if (current >= questions.length) { renderResult(body); return; }

  const q = questions[current];
  const pct = (current / questions.length) * 100;

  body.innerHTML = `
    <div class="progress-row">
      <span class="q-counter">Вопрос ${current + 1} из ${questions.length}</span>
      <span class="score-badge">✓ ${score} верно</span>
    </div>
    <div class="progress-bar"><div class="progress-fill" id="pf" style="width:${pct}%"></div></div>
    <div class="q-text">${q.q}</div>
    <div class="options-grid" id="opts">
      ${q.opts.map((o, i) => `
        <button class="opt-btn" data-i="${i}" onclick="pick(${i})">
          <span class="letter-badge">${letters[i]}</span>
          <span>${o}</span>
        </button>`).join('')}
    </div>
    <div id="fb" class="feedback"></div>
    <button id="nb" class="next-btn" onclick="next()">
      ${current + 1 < questions.length ? 'Следующий вопрос →' : 'Посмотреть результат →'}
    </button>`;
}

function pick(i) {
  if (answered) return;
  answered = true;
  const q = questions[current];
  const btns = document.querySelectorAll('.opt-btn');
  btns.forEach(b => b.disabled = true);

  if (i === q.correct) {
    score++;
    btns[i].classList.add('correct');
    btns[i].querySelector('.letter-badge').textContent = '✓';
  } else {
    btns[i].classList.add('wrong');
    btns[i].querySelector('.letter-badge').textContent = '✗';
    btns[q.correct].classList.add('correct');
    btns[q.correct].querySelector('.letter-badge').textContent = '✓';
  }

  const fb = document.getElementById('fb');
  fb.style.display = 'block';
  fb.textContent = q.hint;
  document.getElementById('nb').style.display = 'inline-block';
}

function next() {
  current++;
  answered = false;
  render();
}

function renderResult(body) {
  const pct = Math.round((score / questions.length) * 100);
  let emoji, msg;
  if (pct >= 90)      { emoji = '🏆'; msg = 'Отличный результат! Вы настоящий знаток KondiZ!'; }
  else if (pct >= 70) { emoji = '🥇'; msg = 'Хороший результат! Вы хорошо знаете фабрику.'; }
  else if (pct >= 50) { emoji = '👍'; msg = 'Неплохо! Есть куда стремиться — попробуйте ещё раз.'; }
  else                { emoji = '📚'; msg = 'Изучите информацию о фабрике и попробуйте снова!'; }

  body.innerHTML = `
    <div class="result-screen">
      <div class="result-emoji">${emoji}</div>
      <div class="result-score-big">${score}/${questions.length}</div>
      <div class="result-out-of">правильных ответов — ${pct}%</div>
      <div class="result-msg">${msg}</div>
      <div class="stats-row">
        <span class="stat-chip ok">✓ Верно: ${score}</span>
        <span class="stat-chip bad">✗ Неверно: ${questions.length - score}</span>
      </div>
      <button class="retry-btn" onclick="restart()">Пройти снова</button>
    </div>`;
}

function restart() {
  current = 0; score = 0; answered = false;
  render();
}

render();
</script>
</body>
</html>
