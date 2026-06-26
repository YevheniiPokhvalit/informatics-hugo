---
title: "Пошук в Інтернеті. Розширений пошук"
weight: 1
---

{{< rawhtml >}}
<!-- Block 1: Theory (Lebedev's MESM and Video) -->
<div class="step-block" id="step-1" style="display: block;">
  <h2>Крок 1. Перший комп'ютер Європи — МЕОМ Лебедєва</h2>
  
  <p>Вітаємо у навчальному квесті! Для початку уважно ознайомся з теоретичним матеріалом та переглянь навчальне відео.</p>
  
  <div style="background: rgba(255,255,255,0.02); border-left: 4px solid #3b82f6; padding: 15px; margin: 20px 0; border-radius: 0 8px 8px 0;">
    <p><strong>МЕОМ</strong> (Мала електронна обчислювальна машина) — це перша в континентальній Європі електронно-обчислювальна машина з накопиченням програми в оперативній пам'яті. Вона була створена в Києві (у селищі Феофанія) в Інституті електротехніки Академії наук УРСР під керівництвом видатного вченого <strong>Сергія Олексійовича Лебедєва</strong> в 1948–1951 роках.</p>
    <p>Машина займала площу близько 60 м², містила понад 6000 електронних ламп і могла виконувати близько 3000 операцій за хвилину.</p>
  </div>

  <h3>Навчальний відеоурок</h3>
  <div class="video-container" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; margin-bottom: 20px; border-radius: 12px; border: 1px solid rgba(255,255,255,0.1); box-shadow: 0 8px 24px rgba(0,0,0,0.2);">
    <!-- Embedded Video Placeholder -->
    <iframe src="" style="position: absolute; top: 0; left: 0; width: 100%; height: 100%; border: 0;" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>

  <div class="timer-container" id="timer-container-1">
    <span id="timer-icon-1">⏳</span> <span id="timer-1">Зачекайте 40 с...</span>
  </div>
  
  <div>
    <button type="button" id="btn-next-1" class="quest-btn" disabled onclick="goToStep2()">
      Далі
      <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg>
    </button>
  </div>
</div>

<!-- Block 2: Test (1 Question only) -->
<div class="step-block" id="step-2" style="display: none;">
  <h2>Крок 2. Перевірка знань</h2>
  <p>Дай правильну відповідь на запитання, щоб відкрити наступну частину теорії.</p>

  <div class="question-block" style="border: none; padding: 0; margin-bottom: 20px;">
    <p class="question-text" style="font-size: 1.1rem; line-height: 1.5;"><strong>Запитання:</strong> Хто очолював розробку МЕОМ — першої електронно-обчислювальної машини в континентальній Європі, створеної в Києві?</p>
    
    <div class="options-list">
      <label class="option-item">
        <input type="radio" name="q-block2" value="A">
        <span class="option-text">А) Віктор Глушков</span>
      </label>
      <label class="option-item">
        <input type="radio" name="q-block2" value="B">
        <span class="option-text">Б) Сергій Лебедєв</span>
      </label>
      <label class="option-item">
        <input type="radio" name="q-block2" value="C">
        <span class="option-text">В) Алан Тюрінг</span>
      </label>
      <label class="option-item">
        <input type="radio" name="q-block2" value="D">
        <span class="option-text">Г) Джон фон Нейман</span>
      </label>
    </div>
  </div>

  <div style="display: flex; flex-direction: column; gap: 15px; align-items: flex-start;">
    <button type="button" id="btn-submit-2" class="quest-btn" onclick="checkBlock2Answer()">
      Перевірити відповідь
    </button>
    <div id="quiz-feedback-2" class="feedback-box"></div>
  </div>
</div>

<!-- Block 3: Next part of Theory with New Timer -->
<div class="step-block" id="step-3" style="display: none;">
  <h2>Крок 3. Наступники МЕОМ та внесок Віктора Глушкова</h2>
  <p>Чудова робота! Тепер ознайомся з наступним важливим етапом розвитку обчислювальної техніки в Україні.</p>

  <div style="background: rgba(255,255,255,0.02); border-left: 4px solid #10b981; padding: 15px; margin: 20px 0; border-radius: 0 8px 8px 0;">
    <p>Розвиток кібернетики в Україні продовжив видатний вчений <strong>Віктор Михайлович Глушков</strong>. Він заснував Інститут кібернетики Академії наук України.</p>
    <p>Під його керівництвом було створено унікальну серію машин <strong>«МІР»</strong> (Машина для Інженерних Розрахунків), які стали предками персональних комп'ютерів. Вони мали вбудовану мову високого рівня, дисплей зі світловим пером для введення формул безпосередньо з екрана, та були розраховані на роботу безпосередньо інженером, а не штатом операторів.</p>
  </div>

  <div class="timer-container" id="timer-container-3">
    <span id="timer-icon-3">⏳</span> <span id="timer-3">Зачекайте 20 с...</span>
  </div>

  <div>
    <button type="button" id="btn-finish-3" class="quest-btn" disabled onclick="finishQuest()">
      Завершити квест
      <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path><polyline points="22 4 12 14.01 9 11.01"></polyline></svg>
    </button>
  </div>
</div>

<!-- Block 4: Success Screen -->
<div class="step-block" id="step-4" style="display: none; text-align: center; padding: 40px 20px;">
  <div style="font-size: 4rem; margin-bottom: 20px;">🎉</div>
  <h2 style="color: #10b981 !important;">Урок успішно завершено!</h2>
  <p style="font-size: 1.1rem; max-width: 600px; margin: 0 auto 30px auto;">
    Вітаємо! Ти успішно пройшов усі теоретичні етапи, дав правильну відповідь на тест та повністю виконав завдання квесту про історію обчислювальної техніки.
  </p>
  <div style="background: rgba(16, 185, 129, 0.1); border: 1px solid rgba(16, 185, 129, 0.2); padding: 15px; border-radius: 8px; display: inline-block;">
    <span style="color: #2ece6b; font-weight: bold;">Твій прогрес збережено та надіслано на платформу.</span>
  </div>
</div>

<script>
  // Timer State configurations
  const timers = {
    step1: { duration: 40, elapsed: 0, interval: null, btnId: 'btn-next-1', timerId: 'timer-1', containerId: 'timer-container-1', iconId: 'timer-icon-1' },
    step3: { duration: 20, elapsed: 0, interval: null, btnId: 'btn-finish-3', timerId: 'timer-3', containerId: 'timer-container-3', iconId: 'timer-icon-3' }
  };

  // Start countdown function
  function startQuestTimer(timerKey) {
    const t = timers[timerKey];
    const timerText = document.getElementById(t.timerId);
    const btn = document.getElementById(t.btnId);
    const container = document.getElementById(t.containerId);
    const icon = document.getElementById(t.iconId);
    
    if (!timerText || !btn || !container) return;
    
    btn.disabled = true;
    timerText.textContent = `Зачекайте ${t.duration - t.elapsed} с...`;
    
    t.interval = setInterval(() => {
      t.elapsed++;
      const remaining = t.duration - t.elapsed;
      
      if (remaining <= 0) {
        clearInterval(t.interval);
        container.classList.add('active');
        if (icon) icon.textContent = '✅';
        timerText.textContent = 'Матеріал вивчено! Можна продовжувати.';
        btn.disabled = false;
      } else {
        timerText.textContent = `Зачекайте ${remaining} с...`;
      }
    }, 1000);
  }

  // Handle step transitions
  function showStep(stepNum) {
    // Hide all steps
    for (let i = 1; i <= 4; i++) {
      const stepEl = document.getElementById(`step-${i}`);
      if (stepEl) {
        stepEl.style.display = 'none';
      }
    }
    // Show specific step
    const targetStep = document.getElementById(`step-${stepNum}`);
    if (targetStep) {
      targetStep.style.display = 'block';
      
      // Auto-trigger timers on step display
      if (stepNum === 3) {
        startQuestTimer('step3');
      }
    }
  }

  function goToStep2() {
    showStep(2);
  }

  // Check the answer in Block 2
  function checkBlock2Answer() {
    const selected = document.querySelector('input[name="q-block2"]:checked');
    const feedback = document.getElementById('quiz-feedback-2');
    
    if (!selected) {
      feedback.className = 'feedback-box feedback-error';
      feedback.textContent = 'Будь ласка, оберіть варіант відповіді!';
      return;
    }
    
    if (selected.value === 'B') {
      feedback.className = 'feedback-box feedback-success';
      feedback.textContent = 'Правильно! Відправляємо прогрес на платформу...';
      
      const payload = {
        lessonId: 'lebedev-mesm-quest',
        topicId: 'topic-1',
        grade: 7,
        status: 'completed',
        score: 100,
        timestamp: new Date().toISOString()
      };
      
      // 1. window.parent.postMessage (for integration in React iframe)
      if (window.parent && window.parent !== window) {
        window.parent.postMessage({
          type: 'STUDENT_PROGRESS',
          payload: payload
        }, '*');
      }
      
      // 2. Fetch API request to /api/student/save-progress
      fetch('/api/student/save-progress', {
        method: 'POST',
        headers: {
          'Content-Type': 'application/json'
        },
        body: JSON.stringify(payload)
      })
      .then(res => {
        console.log('Progress reported successfully via fetch');
        proceedToStep3();
      })
      .catch(err => {
        console.warn('Backend fetch failed (probably offline), continuing quest anyway...', err);
        proceedToStep3();
      });
      
    } else {
      feedback.className = 'feedback-box feedback-error';
      feedback.textContent = 'Неправильно. Згадайте, хто очолював розробку МЕОМ (це зазначено в тексті Кроку 1). Спробуйте ще раз!';
    }
  }

  function proceedToStep3() {
    setTimeout(() => {
      showStep(3);
    }, 1500);
  }

  // Complete the quest
  function finishQuest() {
    showStep(4);
    
    const finalPayload = {
      lessonId: 'lebedev-mesm-quest',
      topicId: 'topic-1',
      grade: 7,
      status: 'finished',
      timestamp: new Date().toISOString()
    };
    
    if (window.parent && window.parent !== window) {
      window.parent.postMessage({
        type: 'QUEST_FINISHED',
        payload: finalPayload
      }, '*');
    }
  }

  // Initialize first timer on load
  document.addEventListener('DOMContentLoaded', () => {
    startQuestTimer('step1');
  });
</script>
{{< /rawhtml >}}
