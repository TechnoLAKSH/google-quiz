# google-quiz.html by melting maths 
It is a mix quiz for grade 1 to 5 and There are total 10 questions and each contains 5 marks made by Laksh Agarwal founder of melting maths
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Melting Maths – Google Quiz</title>

<style>
    body {
        background: #fff7d6;
        font-family: 'Comic Sans MS', cursive;
        margin: 0;
        padding: 0;
    }

    .container {
        max-width: 900px;
        margin: 40px auto;
        background: #ffffff;
        border: 5px dashed #ff9800;
        border-radius: 20px;
        padding: 20px;
        box-shadow: 0 0 20px rgba(0,0,0,0.2);
        animation: fadeIn 1s ease-in-out;
    }

    h1 {
        text-align: center;
        color: #e53935;
        text-shadow: 2px 2px #ffe6a8;
        font-size: 40px;
        margin-bottom: 10px;
    }

    p {
        text-align: center;
        font-size: 18px;
        color: #444;
    }

    iframe {
        display: block;
        margin: 20px auto;
        border-radius: 10px;
        border: 4px solid #ffb74d;
    }

    /* Button to go back */
    .back-btn {
        display: block;
        margin: 15px auto;
        padding: 12px 25px;
        background: #ff9800;
        color: white;
        text-decoration: none;
        font-size: 20px;
        border-radius: 10px;
        box-shadow: 3px 3px 10px rgba(0,0,0,0.3);
        transition: 0.3s;
        text-align: center;
        width: 200px;
    }

    .back-btn:hover {
        background: #e68a00;
        transform: scale(1.1);
    }

    @keyframes fadeIn {
        from { opacity: 0; transform: scale(0.8);}
        to { opacity: 1; transform: scale(1);}
    }
</style>
</head>

<body>

<div class="container">
    <h1>⭐ Melting Maths – Google Quiz ⭐</h1>
    <p>Answer all questions and check your score instantly!</p>

    <iframe 
        src="https://docs.google.com/forms/d/e/1FAIpQLScbSAqK77g_vHiUtSAMlk3mDO5h8outsBMOYkyg-1kW99Y9zA/viewform?embedded=true"
        width="750"
        height="1500"
        frameborder="0"
        marginheight="0"
        marginwidth="0">
    </iframe>

    <a href="index.html" class="back-btn">⬅ Back to Home</a>
</div>

</body>
</html>
