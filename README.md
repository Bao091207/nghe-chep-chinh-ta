# nghe-chep-chinh-ta
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Dictation Practice</title>
  <style>
    body { font-family: Arial; padding: 40px; }
    textarea { width: 100%; height: 150px; margin-top: 10px; }
    #answer { display: none; background: #f0f0f0; padding: 15px; margin-top: 15px; white-space: pre-wrap; }
    button { margin-top: 10px; padding: 10px 20px; font-size: 16px; }
  </style>
</head>
<body>
  <h1>Luyện Nghe Chép Chính Tả</h1>
  <audio controls>
    <source src="RPReplay_Final1744110325.mp3" type="audio/mp3">
    Trình duyệt của bạn không hỗ trợ audio.
  </audio>

  <h3>Nhập nội dung bạn nghe được:</h3>
  <textarea placeholder="Gõ ở đây..."></textarea>
  <br>
  <button onclick="document.getElementById('answer').style.display = 'block'">Hiện đáp án</button>

  <div id="answer">
    <h3>Đáp án gợi ý:</h3>
    <p>...</p> <!-- Bạn có thể chép đoạn script ở đây -->
  </div>
</body>
</html>