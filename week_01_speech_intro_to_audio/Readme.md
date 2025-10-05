## Материалы модуля 1

<div align="center">
  <img src="../images/dls.png">
</div>

### Введение в аудио.

В этом модуле вы познакомитесь с основами Digital Signal Processing и узнаете что такое звук и как он представляется в самом базовом виде.
<!-- 
<table style="border-collapse: collapse; width: auto; margin: 0 0 16px 0; font-size: 14px; float: left;">
  <thead>
    <tr>
      <th style="border: 1px solid #ccc; padding: 6px 12px; text-align: center;">Type</th>
      <th style="border: 1px solid #ccc; padding: 6px 12px; text-align: center;">Links</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="border: 1px solid #ccc; padding: 6px 12px; text-align: center;">Lecture</td>
      <td style="border: 1px solid #ccc; padding: 6px 12px; text-align: center;">
        <div style="display: flex; gap: 12px; justify-content: center; align-items: center;">
          <a href="https://youtu.be/YOUR_VIDEO_ID" target="_blank" rel="noopener" aria-label="Watch on YouTube">
            <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="24" />
          </a>
          <a href="https://vk.com/video-123456789_456239012" target="_blank" rel="noopener" aria-label="Watch on VK">
            <img src="https://cdn.simpleicons.org/vk" alt="VK" width="24" />
          </a>
        </div>
      </td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 6px 12px; text-align: center;">Seminar</td>
      <td style="border: 1px solid #ccc; padding: 6px 12px; text-align: center;">
        <div style="display: flex; gap: 12px; justify-content: center; align-items: center;">
          <a href="https://youtu.be/YOUR_VIDEO_ID" target="_blank" rel="noopener" aria-label="Watch on YouTube">
            <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="24" />
          </a>
          <a href="https://vk.com/video-123456789_456239012" target="_blank" rel="noopener" aria-label="Watch on VK">
            <img src="https://cdn.simpleicons.org/vk" alt="VK" width="24" />
          </a>
        </div>
      </td>
    </tr>
  </tbody>
</table> -->

<!-- Optional: clear float if content follows -->
<div style="clear: both;"></div>

### Лекция

<div style="display: flex; gap: 8px; align-items: bottom;">
  <span>
  Запись лекции &laquo;Введение в аудио&raquo; доступна на
  </span>
  
  <a href="https://youtu.be/ijqgeA17hLo" target="_blank" rel="noopener" aria-label="Watch on YouTube" 
    style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="20"/>
    &nbsp;
    YouTube
  </a>

  <span>и</span>

  <a href="https://vkvideo.ru/video-155161349_456239309" target="_blank" rel="noopener" aria-label="Watch on VK"
     style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/vk" alt="VK" width="20"/>
    &nbsp;
    VK Видео
  </a>
</div>



В этой лекции вы познакомитесь с такими базовыми понятиями как звуковая волна и важными определениями, которые со звуковой волной связаны, такие как амплитуда, частота, фаза, гармоники. Также мы подробно разберем с вами почему амплитуда измеряется в децибелах, небольшое историческое введение этой единицы измерения и почему она связана с мощностью и интенсивностью. Непрерывный сигнал, к сожалению, мы не можем хранить на компьютере, поэтому мы с вами поговорим о том, как мы дискретизуем звуковой сигнал по времени и по амплитуде, а также немного затронем интуицию, которая стоит за теоремой Шеннона-Найквиста. Последняя часть лекции затронет разные варианты форматов хранения аудио.


Занятие ведёт Асель Ермекова.


### Семинар

<div style="display: flex; gap: 8px; align-items: bottom;">
  <span>
  Запись семинара &laquo;Введение в аудио&raquo; доступна на
  </span>
  
  <a href="https://youtu.be/n8JTX9GJ2Pk" target="_blank" rel="noopener" aria-label="Watch on YouTube" 
    style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="20"/>
    &nbsp;
    YouTube
  </a>

  <span>и</span>

  <a href="https://vkvideo.ru/video-155161349_456239319" target="_blank" rel="noopener" aria-label="Watch on VK"
     style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/vk" alt="VK" width="20"/>
    &nbsp;
    VK Видео
  </a>
</div>

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DeepLearningSchool/part_2_nlp/blob/main/week_01_speech_intro_to_audio/Practice/DLS_Speech_Seminar_1_Intro_to_audio.ipynb)


В этом семинаре вы познакомитесь с основными библиотеками для работы с аудио данными, такими как librosa, torchaudio и soundfile. Также мы рассмотрим базовые характеристики волн, как амплитуда, частота, фаза. 


Занятие ведет Асель Ермекова.


### Домашнее задание

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DeepLearningSchool/part_2_nlp/blob/main/week_01_speech_intro_to_audio/Practice/Homework_1_Environmental_Sound_Classification_for_students.ipynb)


В этом домашнем задании вам нужно будет решить задачу классификации звуков, сделать препросессинг данных, поэкспериментировать с аугментацией аудио данных и написать архитектуру модели.

ВАЖНО: вам нельзя переводить wav репрезентации в MelSpectrograms. В этом домашнем задании необходимо тренировать модель только на wav репрезентации.

Есть две части этого домашнего задания: 

    Решить задачу классификации звуков и отправить предсказания лучшей модели на Stepik. Результат вашей лучшей модели будет оцениваться на тестовой выборке по метрике Accuracy. За прохождение определенных порогов будут начисляться баллы. Критерии оценивания можно найти в ноутбуке. Этот пункт оценивается до 5 баллов. Для этого мы предварительно разделили данные в задании на три части.
        train.csv. На этом наборе данных вам необходимо создать и обучить модель.
        valid.csv. На этом наборе данных вы можете валидировать вашу модель.
        test.csv. Предсказания для этого набора необходимо записать в файл submission.csv и сдать в соответствующий шаг на Stepik. Количество попыток ограничено до 100 штук.
    В конце ноутбука вам необходимо будет описать работу, которую вы сделали, чтобы получить лучший результат. В этом пункте вам необходимо отправить файл в формате .ipynb на Stepik --- для этого в домашнем задании есть отдельный шаг. Этот пункт оценивается до 5 баллов.

