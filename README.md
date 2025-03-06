<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>金融アンケート調査 - ページ1</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>金融アンケート調査 - ページ1</h1>
        <form action="page2.html">
            <div class="question">
                <label for="q1">質問1: あなたの年齢は？</label>
                <input type="number" id="q1" name="q1">
            </div>
            <div class="question">
                <label for="q2">質問2: 性別は？</label>
                <input type="text" id="q2" name="q2">
            </div>
            <div class="question">
                <label for="q3">質問3: 収入額は？</label>
                <input type="number" id="q3" name="q3">
            </div>
            <div class="question">
                <label for="q4">質問4: 貯蓄額は？</label>
                <input type="number" id="q4" name="q4">
            </div>
            <button type="submit">次へ</button>
        </form>
    </div>
</body>
</html>
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>金融アンケート調査 - ページ2</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="container">
        <h1>金融アンケート調査 - ページ2</h1>
        <form action="submit.html">
            <div class="question">
                <label for="q5">質問5: 投資経験はありますか？</label>
                <input type="text" id="q5" name="q5">
            </div>
            <div class="question">
                <label for="q6">質問6: 使用している金融サービスは？</label>
                <input type="text" id="q6" name="q6">
            </div>
            <div class="question">
                <label for="q7">質問7: どのくらいの頻度で金融ニュースを見ますか？</label>
                <input type="text" id="q7" name="q7">
            </div>
            <div class="question">
                <label for="q8">質問8: 金融に関する知識をどのくらい持っていますか？</label>
                <input type="text" id="q8" name="q8">
            </div>
            <button type="submit">送信</button>
        </form>
    </div>
</body>
</html>
