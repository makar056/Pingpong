# 🎮 ULTRA Ping Pong - 2 игрока | Динамичная аркада на Pygame

<div align="center">
  <img src="https://media.giphy.com/media/xT5LMHxhOfscxPfIfm/giphy.gif" width="500" alt="ULTRA Ping Pong Demo">
  
  [![Python 3.6+](https://img.shields.io/badge/Python-3.6+-yellow?logo=python)](https://python.org)
  [![Pygame](https://img.shields.io/badge/Pygame-2.1.3+-orange?logo=game)](https://pygame.org)
  [![License MIT](https://img.shields.io/badge/License-MIT-blueviolet)](LICENSE)
  ![Code Size](https://img.shields.io/github/languages/code-size/makar056/ultra-ping-pong)
</div>

## 🌟 Особенности

- 🚀 Ультра-динамичный геймплей для двух игроков
- ✨ Визуальные эффекты (частицы, свечение, трейлы)
- 🎧 Фоновая музыка и звуковые эффекты
- 🕹️ Прогрессирующая сложность (мяч ускоряется)
- 🎮 Раздельное управление для каждого игрока
- 💥 Специальные бонусы за голы (x3 очка)

## 🛠 Установка

```bash
# Клонировать репозиторий
git clone https://github.com/makar056/ultra-ping-pong.git

# Установить зависимости
pip install pygame
```

```bash
# Запустить игру
python ultra_ping_pong.py
```

## 🕹️ Управление

| Игрок | Команды       | Действие               |
|-------|---------------|------------------------|
| 1     | ← / →         | Движение нижней платформы |
| 2     | A / D         | Движение верхней платформы |
|       | ESC           | Выход из игры          |
|       | P             | Пауза                  |

## 🏆 Игровая механика

```python
class UltraPingPong:
    def __init__(self):
        self.player1_score = 0  # Счет нижнего игрока
        self.player2_score = 0  # Счет верхнего игрока
        self.ball_speed = 5     # Начальная скорость мяча
        self.max_speed = 15     # Максимальная скорость
```

- 🔵 Нижний игрок (синий) - управление стрелками
- 🟢 Верхний игрок (зеленый) - управление клавишами A/D
- 🔴 Мяч ускоряется после каждого отскока от платформы
- 💥 Голы приносят по 3 очка
- ✨ Эффекты частиц при столкновениях

## 📌 Системные требования

- Python 3.6+
- Pygame 2.1.3+
- 800x600 разрешение экрана

## 📧 Контакты

📧 Email | maka7404055@gmail.com  
💻 GitHub | makar056  
🎮 Discord | zxctynder
