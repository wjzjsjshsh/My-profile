<!DOCTYPE html>
<html lang="ku">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TikTok | al_italyy22</title>
    <style>
        /* ڕێکخستنا گشتی یا لاپەڕی */
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            /* وێنەکێ سروشتی یێ گەلەک جوان بۆ پشتپەردێ */
            background: url('https://images.unsplash.com/photo-1470071459604-3b5ec3a7fe05?q=80&w=1200&auto=format&fit=crop') no-repeat center center fixed;
            background-size: cover;
            font-family: 'Segoe UI', Roboto, Helvetica, Arial, sans-serif;
            overflow: hidden;
        }

        /* کارتێ شووشەیی یا ناڤەڕاستێ (Glassmorphism) */
        .tiktok-card {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(10px);
            -webkit-backdrop-filter: blur(10px);
            border: 1px solid rgba(255, 255, 255, 0.25);
            padding: 40px 30px;
            border-radius: 25px;
            text-align: center;
            box-shadow: 0 15px 35px rgba(0, 0, 0, 0.2);
            max-width: 350px;
            width: 85%;
            animation: fadeIn 1.5s ease-in-out;
        }

        /* لۆگۆیێ تیکتۆکێ ب شێوازەکێ مۆدێرن */
        .tiktok-icon {
            font-size: 4rem;
            color: #ffffff;
            margin-bottom: 15px;
            display: inline-block;
            text-shadow: 2px 2px 0px #ff0050, -2px -2px 0px #00f2fe; /* ڕەنگێن تیکتۆکێ یێن ناسراو */
            animation: float 3s ease-in-out infinite;
        }

        /* ستایلێ ناڤێ تیکتۆکێ */
        h1 {
            color: #ffffff;
            font-size: 1.4rem;
            margin: 5px 0;
            font-weight: 500;
            letter-spacing: 0.5px;
        }

        /* ستایلێ یوزەرنایێ تە al_italyy22 */
        .username {
            color: #ffffff;
            font-size: 2rem;
            margin: 10px 0 25px 0;
            font-weight: bold;
            text-shadow: 0 2px 10px rgba(0,0,0,0.3);
        }

        /* دوگمەیا چوونێ بۆ تیکتۆکێ */
        .tiktok-btn {
            display: inline-block;
            padding: 12px 35px;
            background-color: #ffffff;
            color: #000000;
            text-decoration: none;
            font-size: 1.1rem;
            font-weight: bold;
            border-radius: 50px;
            box-shadow: 0 5px 15px rgba(0,0,0,0.15);
            transition: all 0.3s ease;
        }

        /* دەما ماوس دچیتە سەر دوگمێ */
        .tiktok-btn:hover {
            background-color: #010101;
            color: #ffffff;
            transform: translateY(-3px);
            box-shadow: 0 8px 20px rgba(255, 0, 80, 0.4);
        }

        /* ئەنیمەیشنا لێدانا لۆگۆی (بەرزبوون و نزمبوون) */
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-10px); }
            100% { transform: translateY(0px); }
        }

        /* ئەنیمەیشنا دیاربوونا کارتێ */
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }
    </style>
</head>
<body>

    <div class="tiktok-card">
        <div class="tiktok-icon">🎵</div>
        
        <h1>TikTok Profile</h1>
        <div class="username">@al_italyy22</div>
        
        <a href="https://www.tiktok.com/@al_italyy22" target="_blank" class="tiktok-btn">Follow Me</a>
    </div>

</body>
</html>
