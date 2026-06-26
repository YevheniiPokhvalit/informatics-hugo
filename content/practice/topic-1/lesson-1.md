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
  
  <div class="quest-nav">
    <button type="button" id="btn-back-1" class="quest-nav-btn" style="display: none;" disabled>
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="15 18 9 12 15 6"></polyline></svg>
      Назад
    </button>
    <button type="button" id="btn-next-1" class="quest-btn" disabled onclick="goToStep2()">
      Далі
      <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><line x1="5" y1="12" x2="19" y2="12"></line><polyline points="12 5 19 12 12 19"></polyline></svg>
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

  <div id="quiz-feedback-2" class="feedback-box"></div>

  <div class="quest-nav">
    <button type="button" id="btn-back-2" class="quest-nav-btn" style="display: none;" onclick="showStep(1)">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="15 18 9 12 15 6"></polyline></svg>
      Назад
    </button>
    <button type="button" id="btn-submit-2" class="quest-btn" onclick="checkBlock2Answer()">
      Перевірити відповідь
    </button>
    <button type="button" id="btn-next-2" class="quest-nav-btn" style="display: none;" disabled onclick="showStep(3)">
      Далі
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="9 18 15 12 9 6"></polyline></svg>
    </button>
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

  <div class="quest-nav">
    <button type="button" id="btn-back-3" class="quest-nav-btn" style="display: none;" onclick="showStep(2)">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="15 18 9 12 15 6"></polyline></svg>
      Назад
    </button>
    <button type="button" id="btn-finish-3" class="quest-btn" disabled onclick="finishQuest()">
      Завершити квест
      <svg width="18" height="18" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><path d="M22 11.08V12a10 10 0 1 1-5.93-9.14"></path><polyline points="22 4 12 14.01 9 11.01"></polyline></svg>
    </button>
  </div>
</div>

<!-- Block 4: Success Screen -->
<div class="step-block" id="step-4" style="display: none; text-align: center; padding: 40px 24px;">
  <div style="font-size: 4rem; margin-bottom: 20px;">🎉</div>
  <h2 style="color: #10b981 !important; font-weight: 700; margin-bottom: 15px;">Урок успішно завершено!</h2>
  <p style="font-size: 1.1rem; max-width: 650px; margin: 0 auto 25px auto; line-height: 1.6;">
    Вітаємо! Ти успішно пройшов усі теоретичні етапи, дав правильну відповідь на тест та повністю виконав завдання квесту про історію обчислювальної техніки. Твій прогрес збережено та надіслано на платформу.
  </p>
  
  <div style="display: flex; justify-content: center; gap: 20px; margin-bottom: 35px; flex-wrap: wrap;">
    <div class="stat-badge">
      <span>🎓 Твоя оцінка:</span>
      <strong id="final-score">12</strong>
      <span>балів</span>
    </div>
    <div class="coin-badge">
      <span>🪙 Нараховано монет:</span>
      <strong id="final-coins">+60</strong>
    </div>
  </div>

  <div class="quest-nav" style="justify-content: center; gap: 20px; border-top: none; margin-top: 10px;">
    <button type="button" id="btn-back-4" class="quest-nav-btn" style="display: none;" onclick="showStep(3)">
      <svg width="16" height="16" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5"><polyline points="15 18 9 12 15 6"></polyline></svg>
      Назад
    </button>
    <button type="button" class="quest-btn" onclick="goToLessons()">
      Повернутися до уроків
    </button>
  </div>
</div>

<script>
  // Quest Configuration
  const totalTests = 1;
  let isCompleted = false;
  let reviewMode = false;

  // Event listener for message from React parent to activate Review Mode
  window.addEventListener('message', function(event) {
    if (event.data.type === 'SET_COMPLETED_STATUS' && event.data.isCompleted) {
      activateReviewMode();
    }
  });

  // Grade calculation formula: (CorrectAnswers / TotalTests) * 12
  function calculateScore(correctAnswers, total) {
    return Math.round((correctAnswers / total) * 12);
  }

  // Timer State configurations
  const timers = {
    step1: { duration: 40, elapsed: 0, interval: null, btnId: 'btn-next-1', timerId: 'timer-1', containerId: 'timer-container-1', iconId: 'timer-icon-1' },
    step3: { duration: 20, elapsed: 0, interval: null, btnId: 'btn-finish-3', timerId: 'timer-3', containerId: 'timer-container-3', iconId: 'timer-icon-3' }
  };

  // Start countdown function
  function startQuestTimer(timerKey) {
    if (isCompleted) return; // Skip if already completed
    
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

  // Activate Review Mode (bypass limitations, enable nav, skip tests, prevent score duplication)
  function activateReviewMode() {
    reviewMode = true;
    isCompleted = true;
    
    // Clear any running intervals/timers
    if (timers.step1.interval) clearInterval(timers.step1.interval);
    if (timers.step3.interval) clearInterval(timers.step3.interval);
    
    // Enable all primary buttons
    const btnNext1 = document.getElementById('btn-next-1');
    const btnNext2 = document.getElementById('btn-next-2');
    const btnFinish3 = document.getElementById('btn-finish-3');
    
    if (btnNext1) btnNext1.disabled = false;
    if (btnNext2) {
      btnNext2.disabled = false;
      btnNext2.style.display = 'inline-block';
    }
    if (btnFinish3) btnFinish3.disabled = false;
    
    // Reset timer labels (no count down text)
    const t1 = document.getElementById('timer-1');
    const t3 = document.getElementById('timer-3');
    if (t1) t1.textContent = 'Матеріал вивчено.';
    if (t3) t3.textContent = 'Матеріал вивчено.';
    
    const container1 = document.getElementById('timer-container-1');
    const container3 = document.getElementById('timer-container-3');
    if (container1) container1.classList.add('active');
    if (container3) container3.classList.add('active');
    
    const icon1 = document.getElementById('timer-icon-1');
    const icon3 = document.getElementById('timer-icon-3');
    if (icon1) icon1.textContent = '✅';
    if (icon3) icon3.textContent = '✅';

    // Auto-check correct answer B
    const radioB = document.querySelector('input[name="q-block2"][value="B"]');
    if (radioB) radioB.checked = true;

    // Show Back buttons for simple navigation
    const back2 = document.getElementById('btn-back-2');
    const back3 = document.getElementById('btn-back-3');
    const back4 = document.getElementById('btn-back-4');
    
    if (back2) back2.style.display = 'inline-block';
    if (back3) back3.style.display = 'inline-block';
    if (back4) back4.style.display = 'inline-block';

    // Set dynamic score values on final page
    const final12Score = calculateScore(1, totalTests);
    document.getElementById('final-score').textContent = final12Score;
    document.getElementById('final-coins').textContent = `+${final12Score * 5}`;
    
    // Switch to final block immediately
    showStep(4);
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
    // Show target step
    const targetStep = document.getElementById(`step-${stepNum}`);
    if (targetStep) {
      targetStep.style.display = 'block';
      
      // Auto-trigger step 3 timer
      if (stepNum === 3 && !isCompleted) {
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
      feedback.textContent = 'Правильно! Прогрес надіслано на платформу.';
      
      const final12Score = calculateScore(1, totalTests);
      
      // Send LESSON_COMPLETED only if we are NOT in reviewMode
      if (!reviewMode) {
        window.parent.postMessage({
          type: 'LESSON_COMPLETED',
          lesson_id: 1,
          score: final12Score,
          step: 3
        }, '*');
      }
      
      // Enable next step button on Card 2
      const btnNext2 = document.getElementById('btn-next-2');
      if (btnNext2) {
        btnNext2.disabled = false;
        btnNext2.style.display = 'inline-block';
      }
      
      proceedToStep3();
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
    const final12Score = calculateScore(1, totalTests);
    
    // Dynamically write score and coin values
    document.getElementById('final-score').textContent = final12Score;
    document.getElementById('final-coins').textContent = `+${final12Score * 5}`;
    
    showStep(4);
    
    const finalPayload = {
      lessonId: 'lebedev-mesm-quest',
      topicId: 'topic-1',
      grade: 7,
      status: 'finished',
      score: final12Score,
      timestamp: new Date().toISOString()
    };
    
    if (window.parent && window.parent !== window && !reviewMode) {
      window.parent.postMessage({
        type: 'QUEST_FINISHED',
        payload: finalPayload
      }, '*');
    }
  }

  // PostMessage interface to return to the React platform
  function goToLessons() {
    if (window.parent && window.parent !== window) {
      window.parent.postMessage({ type: 'GO_TO_LESSONS' }, '*');
    }
  }

  // Start timer on load
  document.addEventListener('DOMContentLoaded', () => {
    // Notify parent React app that we are ready to receive state
    if (window.parent && window.parent !== window) {
      window.parent.postMessage({ type: 'IFRAME_READY', lesson_id: 1 }, '*');
    }
    
    // Fallback: Start timer 500ms after load if no completed status is received
    setTimeout(() => {
      if (!isCompleted) {
        startQuestTimer('step1');
      }
    }, 500);
  });
</script>
{{< /rawhtml >}}
