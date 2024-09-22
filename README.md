
<!DOCTYPE html>
<html lang="en">
<head>
  <title>Got Milk?</title>

  <!-- Include Tailwind CSS from CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Include FontAwesome from CDN -->
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>

  <style>
    @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400&display=swap');
    body {
      font-family: 'Roboto', sans-serif;
    }
    .nav-link {
      margin: 0 10px;
    }
    .nav-link::after {
      content: '|';
      margin-left: 10px;
    }
    .nav-link:last-child::after {
      content: '';
    }
  </style>
</head>
<body class="bg-white text-black flex flex-col items-center">
  <!-- Navigation Bar -->
  <nav class="mt-4">
    <ul class="flex space-x-4 text-lg">
      <li class="nav-link">got milk?</li>
      <li class="nav-link">recipes</li>
      <li class="nav-link">store</li>
      <li class="nav-link">fun</li>
      <li class="nav-link">news</li>
    </ul>
  </nav>

  <!-- Main Image -->
  <div class="mt-8">
    <!-- Ensure to replace the src path with the correct relative URL from your GitHub repo -->
    <img alt="got milk? text in a unique font" class="mx-auto" height="100" src="assets/images/got_milk_image.png" width="400"/>
  </div>

  <!-- Image Cards Section -->
  <div class="mt-8 flex space-x-4">
    <!-- First Image Card -->
    <div class="w-24 h-32 bg-white border border-gray-300 flex items-center justify-center">
      <img alt="Image of a product with a drink" class="w-full h-full object-cover" height="120" src="assets/images/product_image_1.png" width="80"/>
    </div>

    <!-- Second Image Card -->
    <div class="w-24 h-32 bg-black flex items-center justify-center">
      <img alt="Number 10 with got milk? text" class="w-full h-full object-cover" height="80" src="assets/images/number_10_image.png" width="80"/>
    </div>

    <!-- Third Image Card -->
    <div class="w-24 h-32 bg-blue-500 flex items-center justify-center">
      <img alt="Image of a person jumping" class="w-full h-full object-cover" height="80" src="assets/images/person_jumping_image.png" width="80"/>
    </div>
  </div>
</body>
</html>
