<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timber Tonic Creations - Handcrafted Wood Products</title>
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    <script>tailwind.config={theme:{extend:{colors:{primary:'#8B4513',secondary:'#D2B48C'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.5.0/fonts/remixicon.css" rel="stylesheet">
    <style>
        :where([class^="ri-"])::before { content: "\f3c2"; }
        body {
            font-family: 'Poppins', sans-serif;
        }
        h1, h2, h3, h4, h5 {
            font-family: 'Playfair Display', serif;
        }
        .hero-section {
            background-image: url('https://public.readdy.ai/ai/img_res/db2f66a886551ae8760dc041cbe72b07.jpg');
            background-size: cover;
            background-position: center;
        }
        input:focus, textarea:focus {
            outline: none;
        }
        input[type="number"]::-webkit-inner-spin-button,
        input[type="number"]::-webkit-outer-spin-button {
            -webkit-appearance: none;
            margin: 0;
        }
    </style>
</head>
<body class="bg-white min-h-screen">
    <!-- Header & Navigation -->
    <header class="w-full bg-white shadow-sm sticky top-0 z-50">
        <div class="container mx-auto px-4 py-4 flex items-center justify-between">
            <a href="#" class="text-3xl font-['Pacifico'] text-primary">logo</a>
            
            <nav class="hidden md:flex space-x-8">
                <a href="#" class="text-gray-800 hover:text-primary font-medium transition">Home</a>
                <a href="#products" class="text-gray-800 hover:text-primary font-medium transition">Products</a>
                <a href="#about" class="text-gray-800 hover:text-primary font-medium transition">About Us</a>
                <a href="#contact" class="text-gray-800 hover:text-primary font-medium transition">Contact</a>
            </nav>
            
            <div class="flex items-center space-x-4">
                <a href="#" class="w-10 h-10 flex items-center justify-center text-gray-700 hover:text-primary transition">
                    <i class="ri-search-line ri-lg"></i>
                </a>
                <a href="#" class="w-10 h-10 flex items-center justify-center text-gray-700 hover:text-primary transition">
                    <i class="ri-shopping-cart-line ri-lg"></i>
                </a>
                <button class="bg-primary text-white px-6 py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition hidden md:block">Shop Now</button>
                <button class="w-10 h-10 flex items-center justify-center text-gray-700 md:hidden">
                    <i class="ri-menu-line ri-lg"></i>
                </button>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="hero-section relative">
        <div class="absolute inset-0 bg-black bg-opacity-40"></div>
        <div class="container mx-auto px-4 py-32 relative z-10">
            <div class="w-full max-w-xl text-white">
                <h1 class="text-5xl md:text-6xl font-bold mb-6 leading-tight">Handcrafted Wood Products with Soul</h1>
                <p class="text-xl mb-8">Combining traditional craftsmanship with contemporary design to create timeless wooden masterpieces for your home.</p>
                <div class="flex flex-wrap gap-4">
                    <button class="bg-primary text-white px-8 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition font-medium">Explore Collection</button>
                    <button class="bg-white text-primary px-8 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition font-medium">Custom Orders</button>
                </div>
            </div>
        </div>
    </section>

    <!-- Product Categories Section -->
    <section id="products" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold mb-4">Our Crafted Collection</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Discover our range of handcrafted wooden products, each piece meticulously created to bring warmth and character to your space.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="bg-white rounded shadow-md overflow-hidden transition-transform hover:shadow-lg hover:-translate-y-1">
                    <div class="h-64 overflow-hidden">
                        <img src="https://public.readdy.ai/ai/img_res/aeb3dc100a38a66d199912c252da5767.jpg" alt="Custom Furniture" class="w-full h-full object-cover object-top">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Custom Furniture</h3>
                        <p class="text-gray-600 mb-4">Bespoke furniture pieces tailored to your specific needs and aesthetic preferences.</p>
                        <a href="#" class="inline-flex items-center text-primary font-medium">
                            Explore 
                            <span class="w-6 h-6 flex items-center justify-center ml-2">
                                <i class="ri-arrow-right-line"></i>
                            </span>
                        </a>
                    </div>
                </div>
                
                <div class="bg-white rounded shadow-md overflow-hidden transition-transform hover:shadow-lg hover:-translate-y-1">
                    <div class="h-64 overflow-hidden">
                        <img src="https://public.readdy.ai/ai/img_res/c3900a8513be2996f3439c5e5c49335c.jpg" alt="Home Décor" class="w-full h-full object-cover object-top">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Home Décor</h3>
                        <p class="text-gray-600 mb-4">Decorative items that add a touch of nature and elegance to your living spaces.</p>
                        <a href="#" class="inline-flex items-center text-primary font-medium">
                            Explore 
                            <span class="w-6 h-6 flex items-center justify-center ml-2">
                                <i class="ri-arrow-right-line"></i>
                            </span>
                        </a>
                    </div>
                </div>
                
                <div class="bg-white rounded shadow-md overflow-hidden transition-transform hover:shadow-lg hover:-translate-y-1">
                    <div class="h-64 overflow-hidden">
                        <img src="https://public.readdy.ai/ai/img_res/5773a26970ab6f4ab7d57c047eaba47e.jpg" alt="Kitchenware" class="w-full h-full object-cover object-top">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Kitchenware</h3>
                        <p class="text-gray-600 mb-4">Enhance your culinary experience with our handcrafted wooden kitchen essentials.</p>
                        <a href="#" class="inline-flex items-center text-primary font-medium">
                            Explore 
                            <span class="w-6 h-6 flex items-center justify-center ml-2">
                                <i class="ri-arrow-right-line"></i>
                            </span>
                        </a>
                    </div>
                </div>
                
                <div class="bg-white rounded shadow-md overflow-hidden transition-transform hover:shadow-lg hover:-translate-y-1">
                    <div class="h-64 overflow-hidden">
                        <img src="https://public.readdy.ai/ai/img_res/5fa43e99a510f76a1380686d72cbe648.jpg" alt="Personalized Gifts" class="w-full h-full object-cover object-top">
                    </div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Personalized Gifts</h3>
                        <p class="text-gray-600 mb-4">Celebrate special occasions with unique, personalized wooden keepsakes.</p>
                        <a href="#" class="inline-flex items-center text-primary font-medium">
                            Explore 
                            <span class="w-6 h-6 flex items-center justify-center ml-2">
                                <i class="ri-arrow-right-line"></i>
                            </span>
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Featured Products Section -->
    <section class="py-20">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold mb-4">Featured Creations</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Our most popular handcrafted pieces, showcasing the exceptional quality and artistry that defines Timber Tonic Creations.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white rounded shadow-md overflow-hidden">
                    <div class="h-72 overflow-hidden">
                        <img src="https://public.readdy.ai/ai/img_res/66a3f8e18932cd984bb52a113a9410db.jpg" alt="Walnut Dining Table" class="w-full h-full object-cover object-top">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-3">
                            <h3 class="text-xl font-bold">Walnut Dining Table</h3>
                            <span class="text-primary font-semibold">$1,899</span>
                        </div>
                        <p class="text-gray-600 mb-4">Hand-crafted walnut dining table with live edge design and black metal legs.</p>
                        <button class="w-full bg-primary text-white py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition">Add to Cart</button>
                    </div>
                </div>
                
                <div class="bg-white rounded shadow-md overflow-hidden">
                    <div class="h-72 overflow-hidden">
                        <img src="https://public.readdy.ai/ai/img_res/017777492783be25a656596fe5c5a6b4.jpg" alt="Oak Bookshelf" class="w-full h-full object-cover object-top">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-3">
                            <h3 class="text-xl font-bold">Oak Bookshelf</h3>
                            <span class="text-primary font-semibold">$899</span>
                        </div>
                        <p class="text-gray-600 mb-4">Solid oak bookshelf with adjustable shelves and natural oil finish.</p>
                        <button class="w-full bg-primary text-white py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition">Add to Cart</button>
                    </div>
                </div>
                
                <div class="bg-white rounded shadow-md overflow-hidden">
                    <div class="h-72 overflow-hidden">
                        <img src="https://public.readdy.ai/ai/img_res/80c58dc371ee33c9b3b4d90db8f22526.jpg" alt="Cutting Board Set" class="w-full h-full object-cover object-top">
                    </div>
                    <div class="p-6">
                        <div class="flex justify-between items-center mb-3">
                            <h3 class="text-xl font-bold">Cutting Board Set</h3>
                            <span class="text-primary font-semibold">$129</span>
                        </div>
                        <p class="text-gray-600 mb-4">Set of 3 maple and walnut cutting boards in various sizes with juice groove.</p>
                        <button class="w-full bg-primary text-white py-2 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition">Add to Cart</button>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <button class="bg-white border border-primary text-primary px-8 py-3 !rounded-button whitespace-nowrap hover:bg-primary hover:text-white transition font-medium">View All Products</button>
            </div>
        </div>
    </section>

    <!-- Commitment Section -->
    <section id="about" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="flex flex-col lg:flex-row items-center gap-12">
                <div class="lg:w-1/2">
                    <img src="https://public.readdy.ai/ai/img_res/9b220e0ae63d5a3d905118722014c476.jpg" alt="Woodworking Process" class="w-full h-auto rounded-lg shadow-lg">
                </div>
                <div class="lg:w-1/2">
                    <h2 class="text-4xl font-bold mb-6">Our Commitment to Craftsmanship</h2>
                    <p class="text-gray-600 mb-6">At Timber Tonic Creations, we are dedicated to preserving the art of traditional woodworking while embracing modern design sensibilities. Each piece we create tells a story of careful craftsmanship and attention to detail.</p>
                    <p class="text-gray-600 mb-8">We source our materials responsibly, ensuring that each piece not only enriches your space but also respects the environment. Our artisans pay meticulous attention to detail, ensuring that every product meets our high standards of quality.</p>
                    
                    <div class="flex flex-wrap gap-6">
                        <div class="flex items-center">
                            <span class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4">
                                <i class="ri-leaf-line ri-lg"></i>
                            </span>
                            <span class="font-medium">Sustainable Materials</span>
                        </div>
                        <div class="flex items-center">
                            <span class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4">
                                <i class="ri-hand-heart-line ri-lg"></i>
                            </span>
                            <span class="font-medium">Handcrafted Quality</span>
                        </div>
                        <div class="flex items-center">
                            <span class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4">
                                <i class="ri-recycle-line ri-lg"></i>
                            </span>
                            <span class="font-medium">Eco-Friendly Practices</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Testimonials Section -->
    <section class="py-20">
        <div class="container mx-auto px-4">
            <div class="text-center mb-16">
                <h2 class="text-4xl font-bold mb-4">What Our Customers Say</h2>
                <p class="text-gray-600 max-w-2xl mx-auto">Hear from our satisfied customers about their experience with our handcrafted wooden creations.</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-8 rounded shadow-md">
                    <div class="flex text-primary mb-4">
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                    </div>
                    <p class="text-gray-600 mb-6">"The custom dining table we ordered exceeded our expectations. The craftsmanship is impeccable, and it has become the centerpiece of our home. Worth every penny!"</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 bg-gray-200 rounded-full mr-4 flex items-center justify-center text-gray-500">
                            <i class="ri-user-line ri-lg"></i>
                        </div>
                        <div>
                            <h4 class="font-medium">Rebecca Anderson</h4>
                            <p class="text-gray-500 text-sm">Portland, OR</p>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white p-8 rounded shadow-md">
                    <div class="flex text-primary mb-4">
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                    </div>
                    <p class="text-gray-600 mb-6">"I purchased several pieces from the kitchenware collection as gifts, and everyone loved them. The attention to detail and quality of the wood is outstanding. Will definitely order again!"</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 bg-gray-200 rounded-full mr-4 flex items-center justify-center text-gray-500">
                            <i class="ri-user-line ri-lg"></i>
                        </div>
                        <div>
                            <h4 class="font-medium">Michael Thompson</h4>
                            <p class="text-gray-500 text-sm">Austin, TX</p>
                        </div>
                    </div>
                </div>
                
                <div class="bg-white p-8 rounded shadow-md">
                    <div class="flex text-primary mb-4">
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                        <i class="ri-star-fill"></i>
                    </div>
                    <p class="text-gray-600 mb-6">"The personalized keepsake box I ordered for my husband's birthday was absolutely beautiful. The engraving was perfect, and the wood quality is exceptional. A truly special gift!"</p>
                    <div class="flex items-center">
                        <div class="w-12 h-12 bg-gray-200 rounded-full mr-4 flex items-center justify-center text-gray-500">
                            <i class="ri-user-line ri-lg"></i>
                        </div>
                        <div>
                            <h4 class="font-medium">Jennifer Blackwell</h4>
                            <p class="text-gray-500 text-sm">Chicago, IL</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gray-50">
        <div class="container mx-auto px-4">
            <div class="flex flex-col lg:flex-row gap-12">
                <div class="lg:w-1/2">
                    <h2 class="text-4xl font-bold mb-6">Get In Touch</h2>
                    <p class="text-gray-600 mb-8">Have questions about our products or interested in a custom order? Reach out to us and our team will get back to you as soon as possible.</p>
                    
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <span class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4 mt-1">
                                <i class="ri-map-pin-line ri-lg"></i>
                            </span>
                            <div>
                                <h4 class="font-medium mb-1">Workshop Location</h4>
                                <p class="text-gray-600">1234 Woodcraft Lane, Portland, OR 97205</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <span class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4 mt-1">
                                <i class="ri-mail-line ri-lg"></i>
                            </span>
                            <div>
                                <h4 class="font-medium mb-1">Email Us</h4>
                                <p class="text-gray-600">info@timbertoniccreations.com</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <span class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4 mt-1">
                                <i class="ri-phone-line ri-lg"></i>
                            </span>
                            <div>
                                <h4 class="font-medium mb-1">Call Us</h4>
                                <p class="text-gray-600">(503) 555-0123</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <span class="w-12 h-12 flex items-center justify-center bg-primary bg-opacity-10 rounded-full text-primary mr-4 mt-1">
                                <i class="ri-time-line ri-lg"></i>
                            </span>
                            <div>
                                <h4 class="font-medium mb-1">Workshop Hours</h4>
                                <p class="text-gray-600">Monday - Friday: 9am - 6pm<br>Saturday: 10am - 4pm<br>Sunday: Closed</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div class="lg:w-1/2">
                    <div class="bg-white p-8 rounded shadow-md">
                        <h3 class="text-2xl font-bold mb-6">Send Us a Message</h3>
                        <form>
                            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-6">
                                <div>
                                    <label for="name" class="block text-gray-700 mb-2">Full Name</label>
                                    <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" placeholder="Your name">
                                </div>
                                <div>
                                    <label for="email" class="block text-gray-700 mb-2">Email Address</label>
                                    <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" placeholder="Your email">
                                </div>
                            </div>
                            
                            <div class="mb-6">
                                <label for="subject" class="block text-gray-700 mb-2">Subject</label>
                                <input type="text" id="subject" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" placeholder="Subject">
                            </div>
                            
                            <div class="mb-6">
                                <label for="inquiry" class="block text-gray-700 mb-2">Type of Inquiry</label>
                                <div class="relative">
                                    <select id="inquiry" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary appearance-none pr-8">
                                        <option value="">Select an option</option>
                                        <option value="custom">Custom Order</option>
                                        <option value="product">Product Inquiry</option>
                                        <option value="wholesale">Wholesale</option>
                                        <option value="other">Other</option>
                                    </select>
                                    <div class="absolute right-3 top-1/2 transform -translate-y-1/2 pointer-events-none">
                                        <i class="ri-arrow-down-s-line"></i>
                                    </div>
                                </div>
                            </div>
                            
                            <div class="mb-6">
                                <label for="message" class="block text-gray-700 mb-2">Message</label>
                                <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded focus:border-primary" placeholder="Your message"></textarea>
                            </div>
                            
                            <button type="submit" class="w-full bg-primary text-white py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition font-medium">Send Message</button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>
    <!-- Newsletter Section -->
    <section class="py-16 bg-primary bg-opacity-10">
        <div class="container mx-auto px-4">
            <div class="text-center max-w-2xl mx-auto">
                <h2 class="text-3xl font-bold mb-4">Join Our Newsletter</h2>
                <p class="text-gray-600 mb-8">Subscribe to receive updates on new products, special offers, and woodworking tips.</p>
                <form class="flex flex-col sm:flex-row gap-4">
                    <input type="email" class="flex-1 px-4 py-3 border-none rounded shadow-sm focus:ring-2 focus:ring-primary" placeholder="Your email address">
                    <button type="submit" class="bg-primary text-white px-6 py-3 !rounded-button whitespace-nowrap hover:bg-opacity-90 transition font-medium">Subscribe</button>
                </form>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white pt-16 pb-8">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-8 mb-12">
                <div>
                    <a href="#" class="text-3xl font-['Pacifico'] text-white mb-6 inline-block">logo</a>
                    <p class="text-gray-400 mb-6">Handcrafted wooden products that bring warmth and elegance to any space. Where craftsmanship meets creativity.</p>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-700 rounded-full hover:bg-primary transition">
                            <i class="ri-facebook-fill"></i>
                        </a>
                        <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-700 rounded-full hover:bg-primary transition">
                            <i class="ri-instagram-line"></i>
                        </a>
                        <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-700 rounded-full hover:bg-primary transition">
                            <i class="ri-pinterest-line"></i>
                        </a>
                        <a href="#" class="w-10 h-10 flex items-center justify-center bg-gray-700 rounded-full hover:bg-primary transition">
                            <i class="ri-twitter-x-line"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-xl font-bold mb-6">Quick Links</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Home</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Shop</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">About Us</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Custom Orders</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Contact</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-xl font-bold mb-6">Products</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Custom Furniture</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Home Décor</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Kitchenware</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Personalized Gifts</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">New Arrivals</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-xl font-bold mb-6">Customer Service</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Shipping & Returns</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Care Instructions</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">FAQ</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Privacy Policy</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Terms & Conditions</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="pt-8 border-t border-gray-700 text-center text-gray-400">
                <p>&copy; 2025 Timber Tonic Creations. All rights reserved.</p>
                <div class="flex justify-center mt-4 space-x-6">
                    <i class="ri-visa-fill ri-lg"></i>
                    <i class="ri-mastercard-fill ri-lg"></i>
                    <i class="ri-paypal-fill ri-lg"></i>
                    <i class="ri-apple-fill ri-lg"></i>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Mock data for products
        const featuredProducts = [
            {
                id: 1,
                name: "Walnut Dining Table",
                price: "$1,899",
                description: "Hand-crafted walnut dining table with live edge design and black metal legs.",
                image: "https://public.readdy.ai/ai/img_res/cc44e26f905449b661315220f30252a2.jpg"
            },
            {
                id: 2,
                name: "Oak Bookshelf",
                price: "$899",
                description: "Solid oak bookshelf with adjustable shelves and natural oil finish.",
                image: "https://public.readdy.ai/ai/img_res/1f3fc47a824cb4f2e5c509b18a6725ec.jpg"
            },
            {
                id: 3,
                name: "Cutting Board Set",
                price: "$129",
                description: "Set of 3 maple and walnut cutting boards in various sizes with juice groove.",
                image: "https://public.readdy.ai/ai/img_res/1c0a4b779865f82157084839fc8164a2.jpg"
            }
        ];

        // Mock data for testimonials
        const testimonials = [
            {
                id: 1,
                text: "The custom dining table we ordered exceeded our expectations. The craftsmanship is impeccable, and it has become the centerpiece of our home. Worth every penny!",
                name: "Rebecca Anderson",
                location: "Portland, OR",
                rating: 5
            },
            {
                id: 2,
                text: "I purchased several pieces from the kitchenware collection as gifts, and everyone loved them. The attention to detail and quality of the wood is outstanding. Will definitely order again!",
                name: "Michael Thompson",
                location: "Austin, TX",
                rating: 5
            },
            {
                id: 3,
                text: "The personalized keepsake box I ordered for my husband's birthday was absolutely beautiful. The engraving was perfect, and the wood quality is exceptional. A truly special gift!",
                name: "Jennifer Blackwell",
                location: "Chicago, IL",
                rating: 5
            }
        ];
        // Mobile menu toggle
        document.addEventListener('DOMContentLoaded', function() {
            const menuButton = document.querySelector('.ri-menu-line').parentElement;
            menuButton.addEventListener('click', function() {
                // Mobile menu functionality would go here
                console.log('Menu clicked');
            });
        });
    </script>
</body>
</html>
