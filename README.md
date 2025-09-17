<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Search Button Example</title>
  <style>
    /* Styling the search bar */
    .search-container {
      display: flex;
      justify-content: center;
      align-items: center;
      margin-top: 50px;
    }

    .search-box {
      width: 300px;
      padding: 10px;
      border: 2px solid #ccc;
      border-radius: 5px;
      font-size: 16px;
    }

    .search-button {
      padding: 10px 20px;
      margin-left: 10px;
      background-color: #4CAF50;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 16px;
    }

    .search-button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <div class="search-container">
    <input type="text" class="search-box" placeholder="Search...">
    <button class="search-button">Search</button>
  </div>
</body>
</html>

