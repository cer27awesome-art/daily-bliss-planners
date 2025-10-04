# Daily Bliss Planners

This is the final ready-to-sell version of the Daily Bliss Planners website. It includes a visible Buy Now button and improved layout.

## Features
- Fully functional Buy Now button linking to sample PDF
- Product image, Features, and About sections
- Clean and responsive design
- Ready for GitHub Pages deployment

## Usage
1. Replace `sample_planner.pdf` with your actual product or Gumroad/Payhip link.
2. Update `images/planner-mockup.png` with your real product image.
3. Push all files to GitHub and view your site via GitHub Pages.

## License
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Daily Bliss Planners</title>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Pacifico&display=swap" rel="stylesheet">
    <style>
        /* Reset some default styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Montserrat', sans-serif;
            background: #fdf6f0;
            color: #333;
            line-height: 1.6;
        }

        header {
            background: #f8b400;
            padding: 2rem;
            text-align: center;
            color: white;
        }

        header h1 {
            font-family: 'Pacifico', cursive;
            font-size: 3rem;
            margin-bottom: 0.5rem;
        }

        header p {
            font-size: 1.2rem;
        }

        .container {
            max-width: 1000px;
            margin: 2rem auto;
            padding: 0 1rem;
        }

        .product {
            background: white;
            border-radius: 15px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            overflow: hidden;
            margin-bottom: 2rem;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 25px rgba(0,0,0,0.2);
        }

        .product img {
            width: 100%;
            display: block;
        }

        .product-content {
            padding: 1.5rem;
        }

        .product-content h2 {
            font-size: 1.8rem;
            margin-bottom: 0.5rem;
            color: #f8b400;
        }

        .product-content p {
            margin-bottom: 1rem;
        }

        .btn-buy {
            display: inline-block;
            padding: 0.7rem 1.5rem;
            background: #f85a3e;
            color: white;
            border-radius: 50px;
            text-decoration: none;
            font-weight: bold;
            transition: background 0.3s;
        }

        .btn-buy:hover {
            background: #ff7b5c;
        }

        footer {
            text-align: center;
            padding: 2rem;
            background: #333;
            color: white;
        }

        @media (min-width: 768px) {
            .product-grid {
                display: grid;
                grid-template-columns: repeat(2, 1fr);
                gap: 2rem;
            }
        }

        @media (min-width: 1200px) {
            .product-grid {
                grid-template-columns: repeat(3, 1fr);
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Daily Bliss Planners</h1>
        <p>Organize your day, your way 🌸</p>
    </header>

    <div class="container">
        <div class="product-grid">
            <div class="product">
                <img src="planner1.jpg" alt="Planner 1">
                <div class="product-content">
                    <h2>Floral Daily Planner</h2>
                    <p>Keep your schedule bright and organized with this beautiful floral planner.</p>
                    <a href="BUY_LINK_HERE" class="btn-buy">Buy Now</a>
                </div>
            </div>

            <div class="product">
                <img src="planner2.jpg" alt="Planner 2">
                <div class="product-content">
                    <h2>Minimalist Weekly Planner</h2>
                    <p>Focus on what matters with this clean, simple weekly layout.</p>
                    <a href="BUY_LINK_HERE" class="btn-buy">Buy Now</a>
                </div>
            </div>

            <div class="product">
                <img src="planner3.jpg" alt="Planner 3">
                <div class="product-content">
                    <h2>Colorful Goal Planner</h2>
                    <p>Set your goals and track your progress in a fun, colorful way!</p>
                    <a href="BUY_LINK_HERE" class="btn-buy">Buy Now</a>
                </div>
            </div>
        </div>
    </div>

    <footer>
        &copy; 2025 Daily Bliss Planners. All rights reserved.
    </footer>
</body>
</html>

# Daily Bliss Planners

This is the final ready-to-sell version of the Daily Bliss Planners website. It includes a visible Buy Now button and improved layout.

## Features
- Fully functional Buy Now button linking to sample PDF
- Product image, Features, and About sections
- Clean and responsive design
- Ready for GitHub Pages deployment

## Usage
1. Replace `sample_planner.pdf` with your actual product or Gumroad/Payhip link.
2. Update `images/planner-mockup.png` with your real product image.
3. Push all files to GitHub and view your site via GitHub Pages.

## License
MIT License[sample_planner.pdf](https://github.com/user-attachments/files/22704029/sample_planner.pdf)
[style.css](https://github.com/user-attachments/files/22704030/style.css)[README.md](https://github.com/user-attachments/files/22704031/README.md)
[sample_planner.pdf](https://github.com/user-attachments/files/22704032/samp[index.html](https://github.com/user-attachments/files/22704034/index.html)
le_planner.pdf)[style.css](https://github.com/user-attachments/files/2270403[README.md](https://github.com/user-attachments/files/22704035/README.md)[style.css](https://github.com/user-attachments/files/22704037/style.css)
[sample_planner.pdf](https://github.com/user-attachments/files/22704036/sample_planner.pdf)
3/style.css)


%PDF-1.4
%Sample PDF content for Daily Bliss Planner
%%EOF
body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #fdf6f0; color: #333; }
header { background: #f28a8a; padding: 20px; text-align: center; color: white; }
.container { max-width: 900px; margin: 20px auto; padding: 20px; text-align: center; }
.product-section { margin-bottom: 40px; }
.features-section, .about-section { margin: 30px 0; text-align: left; padding: 0 20px; }
button { background: #f28a8a; color: white; padding: 12px 24px; border: none; cursor: pointer; font-size: 16px; border-radius: 6px; margin-top: 10px; }
button:hover { background: #d76b6b; }
.product-image { max-width: 100%; margin: 20px 0; border-radius:[style.css](https://github.com/user-attachments/files/22704028/style.css)
 12px; }footer { text-align: center; margin-top: 50px; padding: 20px; background: #eee; }
ul { padding-left: 20px; }
