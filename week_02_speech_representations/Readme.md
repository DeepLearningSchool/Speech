## Материалы модуля 2

<div align="center">
  <img src="../images/dls.png">
</div>

### Введение в аудио.

В этом модуле вы познакомитесь с Fourier Serier, Fourier Transform, STFT и Mel-Scale и узнаете как представлять звук в частотном спектре.

### Лекция


<div style="display: flex; gap: 8px; align-items: bottom;">
  <span>
  Запись лекции, часть 1 &laquo;Спектрограммы&raquo; доступна на
  </span>
  
  <a href="https://youtu.be/qZRc-dyZASI" target="_blank" rel="noopener" aria-label="Watch on YouTube" 
    style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="20"/>
    &nbsp;
    YouTube
  </a>

  <span>и</span>

  <a href="https://vkvideo.ru/video-155161349_456239316" target="_blank" rel="noopener" aria-label="Watch on VK"
     style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/vk" alt="VK" width="20"/>
    &nbsp;
    VK Видео
  </a>
</div>


<div style="display: flex; gap: 8px; align-items: bottom;">
  <span>
  Запись лекции, часть 2 &laquo;Спектрограммы, преобразование Фурье&raquo; доступна на
  </span>
  
  <a href="https://youtu.be/6kWSmYiEBYY" target="_blank" rel="noopener" aria-label="Watch on YouTube" 
    style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="20"/>
    &nbsp;
    YouTube
  </a>

  <span>и</span>

  <a href="https://vkvideo.ru/video-155161349_456239317" target="_blank" rel="noopener" aria-label="Watch on VK"
     style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/vk" alt="VK" width="20"/>
    &nbsp;
    VK Видео
  </a>
</div>


<div style="display: flex; gap: 8px; align-items: bottom;">
  <span>
  Запись лекции, часть 3 &laquo;Спектрограммы, STFT&raquo; доступна на
  </span>
  
  <a href="https://youtu.be/rnoSYreDzQI" target="_blank" rel="noopener" aria-label="Watch on YouTube" 
    style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="20"/>
    &nbsp;
    YouTube
  </a>

  <span>и</span>

  <a href="https://vkvideo.ru/video-155161349_456239318" target="_blank" rel="noopener" aria-label="Watch on VK"
     style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/vk" alt="VK" width="20"/>
    &nbsp;
    VK Видео
  </a>
</div>


<div style="display: flex; gap: 8px; align-items: bottom;">
  <span>
  Запись лекции, часть 4 &laquo;Спектрограммы, мел-спектрограммы&raquo; доступна на
  </span>
  
  <a href="https://youtu.be/DXHjXzvC0gQ" target="_blank" rel="noopener" aria-label="Watch on YouTube" 
    style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/youtube" alt="YouTube" width="20"/>
    &nbsp;
    YouTube
  </a>

  <span>и</span>

  <a href="https://vkvideo.ru/video-155161349_456239315" target="_blank" rel="noopener" aria-label="Watch on VK"
     style="display: flex; align-items: center">
    <img src="https://cdn.simpleicons.org/vk" alt="VK" width="20"/>
    &nbsp;
    VK Видео
  </a>
</div>



В этой лекции вы познакомитесь со вторым способом представлять аудиозаписи, а именно спектрограммами. Мы с вами разберем как при помощи ряда Фурье мы можем разложить любой сложный периодичный сигнал в суммы более простых. Интуитивно разберемся как можно применять ряд Фурье для не периодичных функций. Разберем как строить спектрограмму при помощи Short-Time Fourier Transform и научимся переводить спектрограммы в мел-спектрограммы.


Занятие ведёт Асель Ермекова.


### Домашнее задание

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/DeepLearningSchool/part_2_nlp/blob/main/week_02_speech_representations/Homework/unsolved_DLS_HW2__Beyond_the_Fundamental_A_Spectral_Adventure.ipynb)

В этом домашнем задании вы:

1. Проанализируете их частотные спектры, чтобы увидеть, чем отличаются гармоники,

2. Узнаете, почему выбор оконной функции важен при вычислении спектрограмм,

3. Реализуете Mel-спектрограмму — представление, имитирующее человеческий слух,

4. Обучите простой классификатор распознавать инструменты по их тембру.
