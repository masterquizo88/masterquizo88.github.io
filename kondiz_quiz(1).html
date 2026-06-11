
<style>
  * { box-sizing: border-box; margin: 0; padding: 0; }
  body { font-family: var(--font-sans); }
  .quiz-wrap { max-width: 680px; padding: 2rem 0; }
  .hero { background: linear-gradient(135deg, #d85a30 0%, #ba7517 100%); border-radius: var(--border-radius-lg); padding: 2.5rem 2rem; margin-bottom: 2rem; color: #fff; text-align: center; position: relative; overflow: hidden; }
  .hero::before { content: "🍪"; font-size: 80px; position: absolute; top: -10px; right: -10px; opacity: 0.15; transform: rotate(15deg); }
  .hero::after { content: "🎂"; font-size: 60px; position: absolute; bottom: -5px; left: -5px; opacity: 0.15; transform: rotate(-10deg); }
  .hero-badge { background: rgba(255,255,255,0.2); border: 1px solid rgba(255,255,255,0.35); border-radius: 20px; display: inline-block; padding: 4px 14px; font-size: 12px; letter-spacing: 0.05em; margin-bottom: 0.75rem; color: rgba(255,255,255,0.9); }
  .hero h1 { font-size: 26px; font-weight: 500; line-height: 1.3; margin-bottom: 0.5rem; }
  .hero p { font-size: 14px; opacity: 0.85; }
  .progress-bar { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: 20px; height: 8px; margin-bottom: 0.5rem; overflow: hidden; }
  .progress-fill { height: 100%; background: #d85a30; border-radius: 20px; transition: width 0.4s ease; }
  .progress-text { font-size: 12px; color: var(--color-text-secondary); margin-bottom: 1.5rem; }
  .question-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 1.5rem; margin-bottom: 1rem; }
  .question-num { font-size: 11px; color: var(--color-text-tertiary); letter-spacing: 0.08em; text-transform: uppercase; margin-bottom: 0.5rem; }
  .question-text { font-size: 17px; font-weight: 500; color: var(--color-text-primary); line-height: 1.5; margin-bottom: 1.25rem; }
  .options { display: flex; flex-direction: column; gap: 8px; }
  .opt-btn { background: var(--color-background-secondary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-md); padding: 0.75rem 1rem; text-align: left; cursor: pointer; font-size: 14px; color: var(--color-text-primary); transition: border-color 0.15s, background 0.15s; display: flex; align-items: center; gap: 10px; }
  .opt-btn:hover:not(:disabled) { border-color: #d85a30; background: #faece7; color: #993c1d; }
  .opt-btn.correct { background: #eaf3de; border-color: #639922; color: #3b6d11; }
  .opt-btn.wrong { background: #fcebeb; border-color: #e24b4a; color: #a32d2d; }
  .opt-btn.reveal { background: #eaf3de; border-color: #639922; color: #3b6d11; opacity: 0.7; }
  .opt-btn:disabled { cursor: default; }
  .opt-letter { width: 24px; height: 24px; border-radius: 50%; background: rgba(0,0,0,0.06); display: flex; align-items: center; justify-content: center; font-size: 12px; font-weight: 500; flex-shrink: 0; }
  .opt-btn.correct .opt-letter { background: #639922; color: #fff; }
  .opt-btn.wrong .opt-letter { background: #e24b4a; color: #fff; }
  .opt-btn.reveal .opt-letter { background: #639922; color: #fff; }
  .explanation { margin-top: 1rem; padding: 0.75rem 1rem; background: var(--color-background-info, #e6f1fb); border-left: 3px solid #378add; border-radius: 0 var(--border-radius-md) var(--border-radius-md) 0; font-size: 13px; color: var(--color-text-secondary); line-height: 1.6; display: none; }
  .nav-row { display: flex; gap: 10px; justify-content: flex-end; margin-top: 1rem; }
  .btn-next { background: #d85a30; border: none; border-radius: var(--border-radius-md); padding: 10px 22px; color: #fff; font-size: 14px; font-weight: 500; cursor: pointer; transition: opacity 0.15s; display: none; }
  .btn-next:hover { opacity: 0.88; }
  .result-card { background: var(--color-background-primary); border: 0.5px solid var(--color-border-tertiary); border-radius: var(--border-radius-lg); padding: 2rem; text-align: center; display: none; }
  .result-icon { font-size: 56px; margin-bottom: 1rem; }
  .result-score { font-size: 42px; font-weight: 500; color: #d85a30; }
  .result-label { font-size: 14px; color: var(--color-text-secondary); margin-bottom: 0.5rem; }
  .result-msg { font-size: 16px; font-weight: 500; margin: 0.5rem 0 1.5rem; color: var(--color-text-primary); }
  .result-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 10px; margin-bottom: 1.5rem; }
  .stat-box { background: var(--color-background-secondary); border-radius: var(--border-radius-md); padding: 0.75rem; }
  .stat-val { font-size: 22px; font-weight: 500; color: var(--color-text-primary); }
  .stat-lbl { font-size: 12px; color: var(--color-text-secondary); margin-top: 2px; }
  .btn-restart { background: transparent; border: 0.5px solid #d85a30; border-radius: var(--border-radius-md); padding: 10px 24px; color: #d85a30; font-size: 14px; cursor: pointer; transition: background 0.15s; }
  .btn-restart:hover { background: #faece7; }
</style>

<h2 class="sr-only" style="position:absolute;width:1px;height:1px;overflow:hidden;">Викторина о кондитерской фабрике ТОО KondiZ Distribution — проверьте свои знания</h2>

<div class="quiz-wrap">
  <div class="hero">
    <div class="hero-badge">ВИКТОРИНА</div>
    <h1>ТОО KondiZ Distribution</h1>
    <p>Проверьте, насколько хорошо вы знаете любимую кондитерскую фабрику Казахстана</p>
  </div>

  <div id="quiz-body">
    <div class="progress-bar"><div class="progress-fill" id="progress-fill" style="width:10%"></div></div>
    <div class="progress-text" id="progress-text">Вопрос 1 из 10</div>

    <div class="question-card" id="qcard">
      <div class="question-num" id="qnum">Вопрос 1</div>
      <div class="question-text" id="qtext"></div>
      <div class="options" id="opts"></div>
      <div class="explanation" id="explanation"></div>
    </div>

    <div class="nav-row">
      <button class="btn-next" id="btn-next">Следующий вопрос →</button>
    </div>
  </div>

  <div class="result-card" id="result-card">
    <div class="result-icon" id="res-icon">🏆</div>
    <div class="result-label">Ваш результат</div>
    <div class="result-score" id="res-score">0/10</div>
    <div class="result-msg" id="res-msg"></div>
    <div class="result-grid">
      <div class="stat-box"><div class="stat-val" id="stat-right">0</div><div class="stat-lbl">Правильных ответов</div></div>
      <div class="stat-box"><div class="stat-val" id="stat-wrong">0</div><div class="stat-lbl">Неправильных ответов</div></div>
    </div>
    <button class="btn-restart" id="btn-restart">Пройти ещё раз</button>
  </div>
</div>

<script>
const questions = [
  {
    text: "В каком году было основано ТОО «KondiZ»?",
    opts: ["2010", "2013", "2016", "2018"],
    correct: 1,
    explanation: "Основы ТОО «KondiZ» были заложены в 2013 году, а уже в марте 2014 года фабрика выпустила свою первую продукцию."
  },
  {
    text: "В каком городе Казахстана расположена фабрика KondiZ?",
    opts: ["Алматы", "Нур-Султан (Астана)", "Семей", "Шымкент"],
    correct: 2,
    explanation: "Фабрика находится в городе Семей, Абайская область, по адресу: ул. Сорокина, 39."
  },
  {
    text: "Сколько тонн мучных кондитерских изделий в год может производить фабрика KondiZ?",
    opts: ["5 000 тонн", "10 000 тонн", "22 000 тонн", "50 000 тонн"],
    correct: 2,
    explanation: "Производственная мощность KondiZ составляет 22 000 тонн мучных кондитерских изделий в год."
  },
  {
    text: "В каком году KondiZ Distribution участвовала в Шанхайской международной выставке импортных товаров (CIIE)?",
    opts: ["2018", "2019", "2020", "2021"],
    correct: 2,
    explanation: "В 2020 году в 3-й Шанхайской выставке CIIE участвовали 35 казахстанских производителей, среди которых была ТОО «Kondiz Distribution»."
  },
  {
    text: "Как называется крекер с оригинальной формой рыбок в ассортименте KondiZ?",
    opts: ["«Нежность»", "«Рыбки»", "«Калейдоскоп»", "«Полинка»"],
    correct: 1,
    explanation: "«Рыбки» — популярный крекер KondiZ. Он выпускается в нескольких вариантах: классический и с какао."
  },
  {
    text: "В какие страны KondiZ экспортирует свою продукцию помимо рынков Казахстана?",
    opts: ["Германия, Франция, Польша", "Россия, Кыргызстан, Таджикистан", "Китай, Япония, Корея", "США, Канада, Австралия"],
    correct: 1,
    explanation: "KondiZ экспортирует продукцию в Российскую Федерацию, Кыргызстан и Таджикистан, а также поставляет во все регионы Казахстана."
  },
  {
    text: "Как называется слоган кондитерской фабрики KondiZ?",
    opts: ["«Вкус счастья!»", "«Сладкий миг вкуса!»", "«Качество без границ!»", "«Сладость каждый день!»"],
    correct: 1,
    explanation: "Официальный слоган фабрики — «Сладкий миг вкуса!», отражающий уникальность и нежность каждого изделия."
  },
  {
    text: "Как называется печенье KondiZ с формой национального символа — купола юрты?",
    opts: ["«Тамаша»", "«Тойбастар»", "«Шанырак»", "«Капризка»"],
    correct: 2,
    explanation: "«Шанырак» — затяжное печенье, вдохновлённое шаныраком — верхним кольцом традиционной казахской юрты. Выпускается также в шоколадной глазури."
  },
  {
    text: "Какой тип печенья у KondiZ называется «Solominka»?",
    opts: ["Сахарное", "Сдобно-отсадное", "Крекер", "Затяжное"],
    correct: 3,
    explanation: "«Solominka» относится к категории затяжного печенья в ассортименте KondiZ."
  },
  {
    text: "Какой сертификат качества подтверждает соответствие продукции KondiZ?",
    opts: ["ISO 9001", "Халяль-сертификат", "ГОСТ России", "Органик-сертификат"],
    correct: 1,
    explanation: "Продукция ТОО «KondiZ» distribution сертифицирована по стандарту Халяль (регион Абай), что подтверждает её соответствие высоким международным стандартам."
  }
];

let current = 0;
let score = 0;
let answered = false;

function render() {
  const q = questions[current];
  document.getElementById('qnum').textContent = 'Вопрос ' + (current + 1);
  document.getElementById('qtext').textContent = q.text;
  document.getElementById('progress-text').textContent = 'Вопрос ' + (current + 1) + ' из ' + questions.length;
  document.getElementById('progress-fill').style.width = ((current + 1) / questions.length * 100) + '%';
  document.getElementById('explanation').style.display = 'none';
  document.getElementById('btn-next').style.display = 'none';
  answered = false;

  const letters = ['А', 'Б', 'В', 'Г'];
  const optsEl = document.getElementById('opts');
  optsEl.innerHTML = '';
  q.opts.forEach((opt, i) => {
    const btn = document.createElement('button');
    btn.className = 'opt-btn';
    btn.innerHTML = '<span class="opt-letter">' + letters[i] + '</span>' + opt;
    btn.addEventListener('click', () => choose(i));
    optsEl.appendChild(btn);
  });
}

function choose(idx) {
  if (answered) return;
  answered = true;
  const q = questions[current];
  const btns = document.querySelectorAll('.opt-btn');

  btns.forEach((btn, i) => {
    btn.disabled = true;
    if (i === q.correct) btn.classList.add('reveal');
    if (i === idx && i !== q.correct) btn.classList.add('wrong');
    if (i === idx && i === q.correct) { btn.classList.remove('reveal'); btn.classList.add('correct'); }
  });

  if (idx === q.correct) score++;

  const expEl = document.getElementById('explanation');
  expEl.textContent = q.explanation;
  expEl.style.display = 'block';

  const isLast = current === questions.length - 1;
  const btn = document.getElementById('btn-next');
  btn.textContent = isLast ? 'Посмотреть результат' : 'Следующий вопрос →';
  btn.style.display = 'inline-block';
}

document.getElementById('btn-next').addEventListener('click', () => {
  current++;
  if (current >= questions.length) {
    showResult();
  } else {
    render();
  }
});

document.getElementById('btn-restart').addEventListener('click', () => {
  current = 0; score = 0;
  document.getElementById('result-card').style.display = 'none';
  document.getElementById('quiz-body').style.display = 'block';
  render();
});

function showResult() {
  document.getElementById('quiz-body').style.display = 'none';
  const rc = document.getElementById('result-card');
  rc.style.display = 'block';
  document.getElementById('res-score').textContent = score + ' / ' + questions.length;
  document.getElementById('stat-right').textContent = score;
  document.getElementById('stat-wrong').textContent = questions.length - score;

  let icon, msg;
  if (score === 10) { icon = '🏆'; msg = 'Абсолютный чемпион! Вы — настоящий знаток KondiZ!'; }
  else if (score >= 7) { icon = '🌟'; msg = 'Отличный результат! Вы хорошо знаете фабрику KondiZ.'; }
  else if (score >= 5) { icon = '👍'; msg = 'Неплохо! Ещё немного и вы станете экспертом по KondiZ.'; }
  else if (score >= 3) { icon = '📚'; msg = 'Есть, над чем поработать. Попробуйте ещё раз!'; }
  else { icon = '🍪'; msg = 'Самое время поближе познакомиться с миром KondiZ!'; }

  document.getElementById('res-icon').textContent = icon;
  document.getElementById('res-msg').textContent = msg;
}

render();
</script>
