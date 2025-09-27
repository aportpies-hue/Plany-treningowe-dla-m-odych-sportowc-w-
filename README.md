# Plany-treningowe-dla-m-odych-sportowc-w-
Chcesz być silniejszy a może chcesz poprostu potrenować ale nie wiesz jak zacząć. Zapraszamy na naszą strone Plany treningowe dla młodych sportowców znajdziesz tu wszystko czego potrzebujesz od rozgrzewki po treningi siłowe.
<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Trening Piłkarski</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Reset */
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Roboto', sans-serif; }

        body {
            background: url('https://i.imgur.com/OZ6bTzB.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
        }

        nav {
            background-color: rgba(0,0,0,0.7);
            padding: 15px 30px;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 100;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin-left: 20px;
            font-weight: 700;
        }

        header {
            text-align: center;
            padding: 100px 20px;
            background: rgba(0,0,0,0.5);
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        header p {
            font-size: 1.2em;
        }

        section {
            padding: 60px 20px;
            background: rgba(0,0,0,0.6);
            margin: 20px;
            border-radius: 15px;
        }

        .products, .plans {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background: rgba(255,255,255,0.1);
            padding: 20px;
            border-radius: 15px;
        }

        table {
            width: 100%;
            border-collapse: collapse;
        }

        table th, table td {
            padding: 10px;
            border: 1px solid #fff;
            text-align: center;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0,0,0,0.7);
        }
    </style>
</head>
<body>

    <nav>
        <div class="logo"><strong>Trening Piłkarski</strong></div>
        <div class="menu">
            <a href="#plans">Plany treningowe</a>
            <a href="#products">Produkty</a>
            <a href="#football">Piłka nożna</a>
        </div>
    </nav>

    <header>
        <h1>Witaj w Treningu Piłkarskim</h1>
        <p>Podziel się swoimi planami treningowymi, odkrywaj produkty i popraw swoją formę!</p>
    </header>

    <section id="plans">
        <h2>Plany treningowe</h2>
        <div class="plans">
            <div class="card">
                <h3>Plan A</h3>
                <p>Trening siłowy i wytrzymałościowy dla początkujących.</p>
            </div>
            <div class="card">
                <h3>Plan B</h3>
                <p>Plan interwałowy dla średniozaawansowanych.</p>
            </div>
        </div>
    </section>

    <section id="products">
        <h2>Produkty</h2>
        <div class="products">
            <div class="card">
                <h3>Hantle 5kg</h3>
                <p>Idealne do treningu siłowego.</p>
            </div>
            <div class="card">
                <h3>Piłka nożna</h3>
                <p>Do treningów technicznych.</p>
            </div>
        </div>
    </section>

    <!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plany Treningowe</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; font-family: 'Roboto', sans-serif; }

        body {
            background: url('https://i.imgur.com/OZ6bTzB.jpg') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
        }

        nav {
            background-color: rgba(0,0,0,0.7);
            padding: 15px 30px;
            display: flex;
            justify-content: center;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 15px;
            font-weight: 700;
        }

        header {
            text-align: center;
            padding: 80px 20px;
            background: rgba(0,0,0,0.5);
        }

        header h1 {
            font-size: 3em;
            margin-bottom: 20px;
        }

        section {
            padding: 60px 20px;
            background: rgba(0,0,0,0.6);
            margin: 20px auto;
            border-radius: 15px;
            max-width: 1000px;
        }

        .plan-card {
            background: rgba(255,255,255,0.1);
            padding: 20px;
            border-radius: 15px;
            margin-bottom: 20px;
        }

        #newPlanForm {
            display: flex;
            flex-direction: column;
            margin-bottom: 30px;
        }

        #newPlanForm input, #newPlanForm textarea, #newPlanForm button {
            padding: 10px;
            margin-bottom: 10px;
            border-radius: 8px;
            border: none;
        }

        #newPlanForm button {
            background-color: #28a745;
            color: #fff;
            font-weight: bold;
            cursor: pointer;
        }

        footer {
            text-align: center;
            padding: 20px;
            background: rgba(0,0,0,0.7);
        }
    </style>
</head>
<body>

    <nav>
        <a href="#plans">Plany treningowe</a>
    </nav>

    <header>
        <h1>Twoje Plany Treningowe</h1>
        <p>Dodawaj i dziel się swoimi treningami!</p>
    </header>

    <section id="plans">
        <form id="newPlanForm">
            <input type="text" id="planTitle" placeholder="Tytuł planu" required>
            <textarea id="planContent" rows="4" placeholder="Opis planu" required></textarea>
            <button type="submit">Dodaj plan</button>
        </form>

        <div id="plansContainer">
            <!-- Tutaj będą wyświetlane plany treningowe -->
        </div>
    </section>

    <footer>
        &copy; 2025 Twoje Plany Treningowe
    </footer>

    <script>
        const form = document.getElementById('newPlanForm');
        const plansContainer = document.getElementById('plansContainer');

        form.addEventListener('submit', function(e) {
            e.preventDefault();
            const title = document.getElementById('planTitle').value;
            const content = document.getElementById('planContent').value;

            const planCard = document.createElement('div');
            planCard.classList.add('plan-card');
            planCard.innerHTML = `<h3>${title}</h3><p>${content}</p>`;

            plansContainer.prepend(planCard);

            form.reset();
        });
    </script>

</body>
</html>
