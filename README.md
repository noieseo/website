<!DOCTYPE html>
<html lang="ko">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Carrygood Homepage</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      line-height: 1.6;
    }

    header {
      background: #333;
      color: #fff;
      padding: 1rem;
      text-align: center;
    }

    nav {
      background: #444;
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
    }

    nav a {
      color: white;
      padding: 1rem;
      text-decoration: none;
      transition: background 0.3s;
    }

    nav a:hover {
      background: #666;
    }

    .container {
      display: flex;
      flex-wrap: wrap;
      padding: 1rem;
    }

    .main {
      flex: 3;
      padding: 1rem;
      min-width: 250px;
    }

    .sidebar {
      flex: 1;
