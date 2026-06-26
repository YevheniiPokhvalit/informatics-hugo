---
title: "Пошук в Інтернеті. Розширений пошук"
weight: 1
---

# Пошук в Інтернеті. Розширений пошук

Вітаємо на першому уроці інформатики для 7 класу! Сьогодні ми дізнаємося, як зробити ваш пошук в Інтернеті професійним, швидким та точним.

## 1. Навіщо потрібен розширений пошук?

Коли ми вводимо простий запит у пошуковий рядок Google, система повертає мільйони вебсторінок. Більшість із них можуть бути нерелевантними. Для того щоб звузити коло пошуку та швидко знайти потрібні відомості (наприклад, конкретний документ, статтю певною мовою чи зображення з певними ліцензійними правами), використовують **інструменти пошуку** та **розширений пошук**.

## 2. Фільтри та Інструменти пошуку Google

Під пошуковим рядком Google після введення запиту відображаються вкладки: *Усі*, *Зображення*, *Відео*, *Новини*, *Карти* тощо.

Праворуч від цих вкладок знаходиться кнопка **Інструменти** (Tools). Вона відкриває додаткове меню фільтрації:
* **Будь-яка мова:** дозволяє шукати вебсторінки лише вказаною мовою (наприклад, тільки українською).
* **За весь час:** фільтрує результати за періодом публікації (за останню годину, 24 години, тиждень, місяць, рік або за вказаний період). Це дуже корисно для пошуку свіжих новин.
* **Усі результати:** дає змогу перемикатися між звичайним пошуком та пошуком «слово в слово» (точний збіг).

При пошуку зображень у меню «Інструменти» з'являються додаткові фільтри: *Розмір*, *Колір*, *Тип лінії*, *Час завантаження* та *Права на використання*.

## 3. Оператори пошуку (Пошукові команди)

Для створення складних запитів можна використовувати спеціальні символи та слова безпосередньо у пошуковому рядку:

| Оператор | Опис | Приклад запиту | Результат |
| :--- | :--- | :--- | :--- |
| **`" "`** (лапки) | Пошук точного збігу фрази | `"печера Чорногора"` | Сторінки, де ці слова йдуть саме в такому порядку |
| **`-`** (мінус) | Виключення слова з пошуку | `печери -кришталева` | Інформація про печери, крім Кришталевої |
| **`site:`** | Пошук на конкретному сайті або домені | `екологія site:gov.ua` | Матеріали про екологію лише на державних сайтах України |
| **`filetype:`** | Пошук файлів конкретного формату | `алгоритми filetype:pdf` | Тільки документи у форматі PDF про алгоритми |

---

## Відеоурок

Нижче наведено відеоматеріал до уроку. (Заглушка для відео)

<div class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; height: auto; margin-bottom: 20px; border-radius: 8px; box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);">
  <iframe src="" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

---

## Перевір свої знання! (Мікротест)

Дай відповіді на запитання, щоб перевірити, як добре ти засвоїв матеріал. У разі успішного проходження прогрес буде збережено!

<div id="quiz-container" class="quiz-card">
  <div class="quiz-header">
    <h3>Контрольний тест: Розширений пошук</h3>
  </div>
  
  <div class="quiz-body">
    <!-- Question 1 -->
    <div class="question-block" id="q1-block">
      <p class="question-text"><strong>Запитання 1.</strong> Який оператор допоможе знайти файли конкретного формату (наприклад, презентацію PowerPoint або документ PDF)?</p>
      <div class="options-list">
        <label class="option-item">
          <input type="radio" name="q1" value="A">
          <span class="option-text">A) site:</span>
        </label>
        <label class="option-item">
          <input type="radio" name="q1" value="B">
          <span class="option-text">B) filetype:</span>
        </label>
        <label class="option-item">
          <input type="radio" name="q1" value="C">
          <span class="option-text">C) " " (лапки)</span>
        </label>
        <label class="option-item">
          <input type="radio" name="q1" value="D">
          <span class="option-text">D) - (мінус)</span>
        </label>
      </div>
    </div>

    <!-- Question 2 -->
    <div class="question-block" id="q2-block">
      <p class="question-text"><strong>Запитання 2.</strong> Як правильно написати пошуковий запит, щоб знайти інформацію про печери, але повністю виключити з результатів печеру "Оптимістична"?</p>
      <div class="options-list">
        <label class="option-item">
          <input type="radio" name="q2" value="A">
          <span class="option-text">A) печера +Оптимістична</span>
        </label>
        <label class="option-item">
          <input type="radio" name="q2" value="B">
          <span class="option-text">B) печера "Оптимістична"</span>
        </label>
        <label class="option-item">
          <input type="radio" name="q2" value="C">
          <span class="option-text">C) печера -Оптимістична</span>
        </label>
        <label class="option-item">
          <input type="radio" name="q2" value="D">
          <span class="option-text">D) site:печера Оптимістична</span>
        </label>
      </div>
    </div>
  </div>
  
  <div class="quiz-footer">
    <button type="button" id="check-btn" onclick="checkQuiz()">Перевірити відповіді</button>
    <div id="quiz-feedback" class="feedback-box"></div>
  </div>
</div>

<style>
  .quiz-card {
    background-color: var(--quiz-bg, #f8f9fa);
    border: 1px solid var(--quiz-border, #e9ecef);
    border-radius: 12px;
    padding: 24px;
    margin: 30px 0;
    box-shadow: 0 8px 16px rgba(0, 0, 0, 0.05);
    font-family: inherit;
    transition: all 0.3s ease;
  }
  
  /* Dark mode compatibility for Hugo Book theme */
  @media (prefers-color-scheme: dark) {
    .quiz-card {
      --quiz-bg: #1e1e24;
      --quiz-border: #2d2d34;
      color: #e9ecef;
    }
  }

  .quiz-header h3 {
    margin-top: 0;
    margin-bottom: 20px;
    color: #007bff;
    font-size: 1.35rem;
    font-weight: 600;
  }

  .question-block {
    margin-bottom: 24px;
    border-bottom: 1px solid rgba(0, 0, 0, 0.05);
    padding-bottom: 16px;
  }
  
  .question-block:last-child {
    border-bottom: none;
    padding-bottom: 0;
  }

  .question-text {
    font-size: 1.05rem;
    margin-bottom: 12px;
  }

  .options-list {
    display: flex;
    flex-direction: column;
    gap: 10px;
  }

  .option-item {
    display: flex;
    align-items: center;
    padding: 10px 14px;
    border: 1px solid var(--option-border, #dee2e6);
    border-radius: 6px;
    cursor: pointer;
    background-color: var(--option-bg, #ffffff);
    transition: all 0.2s ease;
  }
  
  @media (prefers-color-scheme: dark) {
    .option-item {
      --option-bg: #2d2d34;
      --option-border: #3e3e46;
    }
  }

  .option-item:hover {
    border-color: #007bff;
    background-color: var(--option-hover-bg, #f1f7ff);
  }
  
  @media (prefers-color-scheme: dark) {
    .option-item:hover {
      --option-hover-bg: #26354a;
    }
  }

  .option-item input[type="radio"] {
    margin-right: 12px;
    accent-color: #007bff;
    transform: scale(1.15);
  }

  #check-btn {
    background: linear-gradient(135deg, #007bff 0%, #0056b3 100%);
    color: white;
    border: none;
    padding: 12px 24px;
    font-size: 1rem;
    font-weight: 600;
    border-radius: 8px;
    cursor: pointer;
    transition: all 0.2s ease;
    box-shadow: 0 4px 6px rgba(0, 123, 255, 0.2);
  }

  #check-btn:hover {
    transform: translateY(-2px);
    box-shadow: 0 6px 12px rgba(0, 123, 255, 0.3);
  }

  #check-btn:active {
    transform: translateY(0);
  }

  .feedback-box {
    margin-top: 16px;
    padding: 12px 16px;
    border-radius: 8px;
    font-size: 0.95rem;
    display: none;
    font-weight: 500;
  }

  .feedback-success {
    display: block;
    background-color: #d4edda;
    color: #155724;
    border: 1px solid #c3e6cb;
  }

  .feedback-error {
    display: block;
    background-color: #f8d7da;
    color: #721c24;
    border: 1px solid #f5c6cb;
  }
  
  @media (prefers-color-scheme: dark) {
    .feedback-success {
      background-color: #1c4d2d;
      color: #d4edda;
      border: 1px solid #285a36;
    }
    .feedback-error {
      background-color: #5d252a;
      color: #f8d7da;
      border: 1px solid #712f35;
    }
  }
</style>

<script>
  function checkQuiz() {
    const q1Val = document.querySelector('input[name="q1"]:checked');
    const q2Val = document.querySelector('input[name="q2"]:checked');
    const feedback = document.getElementById('quiz-feedback');

    if (!q1Val || !q2Val) {
      feedback.className = 'feedback-box feedback-error';
      feedback.textContent = 'Будь ласка, дай відповідь на всі запитання перед перевіркою!';
      return;
    }

    if (q1Val.value === 'B' && q2Val.value === 'C') {
      feedback.className = 'feedback-box feedback-success';
      feedback.textContent = 'Чудово! Всі відповіді правильні. Твій прогрес зберігається...';
      
      // Send progress to Node.js backend
      fetch('http://localhost:5000/api/student/save-progress', {
        method: 'POST',
        headers: {
          'Content-Type': 'application/json'
        },
        body: JSON.stringify({
          lessonId: 'lesson-1',
          topicId: 'topic-1',
          grade: 7,
          status: 'completed',
          score: 100,
          timestamp: new Date().toISOString()
        })
      })
      .then(response => {
        if (response.ok) {
          feedback.textContent = 'Вітаємо! Всі відповіді правильні. Прогрес успішно збережено на сервері!';
        } else {
          feedback.textContent = 'Правильно! Прогрес пройдено, але сервер повернув помилку (можливо, Node.js бекенд ще не запущений).';
        }
      })
      .catch(error => {
        console.error('Помилка надсилання прогресу:', error);
        feedback.textContent = 'Чудова робота! Всі відповіді правильні. (Сервер збереження прогресу недоступний, але тест зараховано!)';
      });
      
    } else {
      feedback.className = 'feedback-box feedback-error';
      feedback.textContent = 'Є помилки у відповідях. Спробуй ще раз, перечитавши конспект уроку!';
    }
  }
</script>
