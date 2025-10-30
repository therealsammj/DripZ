<!DOCTYPE html>
<html lang="en" class="dark">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DripZ | Redefine Your Style</title>
    <link rel="stylesheet" href="style.css">
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/feather-icons/dist/feather.min.js"></script>
    <script src="https://unpkg.com/feather-icons"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Montserrat:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        primary: '#000000',
                        secondary: '#ffffff',
                        accent: '#ff0000',
                    },
                    fontFamily: {
                        bebas: ['Bebas Neue', 'sans-serif'],
                        montserrat: ['Montserrat', 'sans-serif'],
                    },
                }
            }
        }
    </script>
</head>
<body class="bg-primary text-secondary font-montserrat min-h-screen flex flex-col">
    <custom-navbar></custom-navbar>

    <main class="flex-grow">
        <!-- Hero Section -->
        <section class="relative h-screen flex items-center justify-center bg-gradient-to-b from-black to-gray-900 overflow-hidden">
            <div class="absolute inset-0 bg-black opacity-50"></div>
            <div class="relative z-10 text-center px-4">
                <h1 class="text-5xl md:text-7xl lg:text-8xl font-bebas tracking-wider mb-4 animate-fadeIn">Welcome to <span class="text-accent">DripZ</span></h1>
                <p class="text-xl md:text-2xl mb-8 max-w-2xl mx-auto">Redefine Your Style with Premium Streetwear</p>
                <a href="/shop.html" class="inline-block bg-accent hover:bg-red-700 text-white font-bold py-3 px-8 rounded-full text-lg transition-all duration-300 transform hover:scale-105">Shop Now</a>
            </div>
        </section>

        <!-- Featured Categories -->
        <section class="py-16 px-4 md:px-8 lg:px-16 bg-gray-900">
            <h2 class="text-3xl md:text-4xl font-bebas text-center mb-12">Featured Collections</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8 max-w-7xl mx-auto">
                <a href="/men.html" class="category-card group">
                    <div class="relative overflow-hidden rounded-lg h-96">
                        <img src="http://static.photos/black/1024x576/1" alt="Men's Collection" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-80"></div>
                        <div class="absolute bottom-0 left-0 p-6">
                            <h3 class="text-3xl font-bebas text-white">Men</h3>
                            <p class="text-gray-300">Explore latest trends</p>
                        </div>
                    </div>
                </a>
                <a href="/women.html" class="category-card group">
                    <div class="relative overflow-hidden rounded-lg h-96">
                        <img src="http://static.photos/black/1024x576/2" alt="Women's Collection" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-80"></div>
                        <div class="absolute bottom-0 left-0 p-6">
                            <h3 class="text-3xl font-bebas text-white">Women</h3>
                            <p class="text-gray-300">Stylish & Comfortable</p>
                        </div>
                    </div>
                </a>
                <a href="/sneakers.html" class="category-card group">
                    <div class="relative overflow-hidden rounded-lg h-96">
                        <img src="http://static.photos/black/1024x576/3" alt="Sneakers Collection" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-500">
                        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent opacity-80"></div>
                        <div class="absolute bottom-0 left-0 p-6">
                            <h3 class="text-3xl font-bebas text-white">Sneakers</h3>
                            <p class="text-gray-300">Step up your game</p>
                        </div>
                    </div>
                </a>
            </div>
        </section>

        <!-- Best Sellers -->
        <section class="py-16 px-4 md:px-8 lg:px-16 bg-black">
            <div class="max-w-7xl mx-auto">
                <h2 class="text-3xl md:text-4xl font-bebas text-center mb-12">Best Sellers</h2>
                <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                    <!-- Product 1 -->
                    <div class="product-card group">
                        <div class="relative overflow-hidden rounded-lg">
                            <img src="http://static.photos/black/640x360/4" alt="DripZ Signature Hoodie" class="w-full h-80 object-cover group-hover:opacity-90 transition-opacity duration-300">
                            <button class="absolute bottom-4 left-1/2 transform -translate-x-1/2 bg-accent text-white py-2 px-6 rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300">Quick View</button>
                        </div>
                        <div class="mt-4">
                            <h3 class="text-lg font-semibold">Signature Hoodie</h3>
                            <p class="text-accent font-bold">$89.99</p>
                        </div>
                    </div>
                    <!-- Product 2 -->
                    <div class="product-card group">
                        <div class="relative overflow-hidden rounded-lg">
                            <img src="http://static.photos/black/640x360/5" alt="DripZ Classic Tee" class="w-full h-80 object-cover group-hover:opacity-90 transition-opacity duration-300">
                            <button class="absolute bottom-4 left-1/2 transform -translate-x-1/2 bg-accent text-white py-2 px-6 rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300">Quick View</button>
                        </div>
                        <div class="mt-4">
                            <h3 class="text-lg font-semibold">Classic Tee</h3>
                            <p class="text-accent font-bold">$39.99</p>
                        </div>
                    </div>
                    <!-- Product 3 -->
                    <div class="product-card group">
                        <div class="relative overflow-hidden rounded-lg">
                            <img src="http://static.photos/black/640x360/6" alt="DripZ Joggers" class="w-full h-80 object-cover group-hover:opacity-90 transition-opacity duration-300">
                            <button class="absolute bottom-4 left-1/2 transform -translate-x-1/2 bg-accent text-white py-2 px-6 rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300">Quick View</button>
                        </div>
                        <div class="mt-4">
                            <h3 class="text-lg font-semibold">Premium Joggers</h3>
                            <p class="text-accent font-bold">$69.99</p>
                        </div>
                    </div>
                    <!-- Product 4 -->
                    <div class="product-card group">
                        <div class="relative overflow-hidden rounded-lg">
                            <img src="http://static.photos/black/640x360/7" alt="DripZ Sneakers" class="w-full h-80 object-cover group-hover:opacity-90 transition-opacity duration-300">
                            <button class="absolute bottom-4 left-1/2 transform -translate-x-1/2 bg-accent text-white py-2 px-6 rounded-full opacity-0 group-hover:opacity-100 transition-opacity duration-300">Quick View</button>
                        </div>
                        <div class="mt-4">
                            <h3 class="text-lg font-semibold">High-Top Sneakers</h3>
                            <p class="text-accent font-bold">$129.99</p>
                        </div>
                    </div>
                </div>
                <div class="text-center mt-12">
                    <a href="/shop.html" class="inline-block border-2 border-accent text-accent hover:bg-accent hover:text-white font-bold py-3 px-8 rounded-full text-lg transition-all duration-300">View All Products</a>
                </div>
            </div>
        </section>

        <!-- Newsletter -->
        <section class="py-16 px-4 md:px-8 lg:px-16 bg-gray-900">
            <div class="max-w-4xl mx-auto text-center">
                <h2 class="text-3xl md:text-4xl font-bebas mb-4">Join the DripZ Movement</h2>
                <p class="text-gray-300 mb-8 max-w-2xl mx-auto">Subscribe to our newsletter for exclusive drops, early access, and 10% off your first order.</p>
                <form class="flex flex-col md:flex-row gap-4 max-w-md mx-auto">
                    <input type="email" placeholder="Your email address" class="flex-grow px-4 py-3 rounded-full bg-gray-800 text-white focus:outline-none focus:ring-2 focus:ring-accent">
                    <button type="submit" class="bg-accent hover:bg-red-700 text-white font-bold py-3 px-6 rounded-full transition-all duration-300">Subscribe</button>
                </form>
            </div>
        </section>
    </main>

    <custom-footer></custom-footer>

    <!-- Scripts -->
    <script src="components/navbar.js"></script>
    <script src="components/footer.js"></script>
    <script src="script.js"></script>
    <script>
        feather.replace();
    </script>
</body>
</html>
