<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>質問回答トレーニング</title>
    <style>
        body {
            text-align: center; /* ページ全体を中央に配置 */
            background-color: #ffffcc; /* もうちょっと薄い黄色に設定 */
            color: black; /* テキストカラーを黒に設定 */
        }

        #omikuji_btn {
            padding: 40px 80px; /* パディングを調整してボタンの大きさを変更 */
            font-size: 40px; /* フォントサイズを変更 */
            margin-top: 20px; /* 上部マージンを追加してボタンを下にずらす */
            background-color: #ff7f50; /* オレンジっぽい色に設定 */
            color: white; /* テキストカラーを白に設定 */
            border: none; /* ボーダーをなくす */
            border-radius: 10px; /* 角を丸くする */
            cursor: pointer; /* カーソルをポインターに変更 */
        }
    </style>
</head>
<body>
    <h1>質問回答トレーニング</h1>
    <input id="omikuji_btn" type="button" value="英語の質問に回答する">
    <script>
        document.getElementById("omikuji_btn").onclick = function() {
            var rnd = Math.floor(Math.random() * 6);
            var omikuji;
            if (rnd === 0) omikuji = "テスト";
            if (rnd === 1) omikuji = "テスト２";
            if (rnd === 2) omikuji = "テスト３";
            if (rnd === 3) omikuji = "テスト４";
            if (rnd === 4) omikuji = "テスト５";
            if (rnd === 5) omikuji = "テスト６";
            alert(omikuji);
        }
    </script>
</body>
</html>
