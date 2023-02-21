<!DOCTYPE html>
<html lang="en">
<head>
    <style>
        .container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 1.5em;
}

.menu {
  font-family: "Inter", sans-serif;
  font-size: 14px;
}

.menu-group-heading {
  margin: 0;
  padding-bottom: 1em;
  border-bottom: 2px solid #ccc;
}

.menu-group {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1.5em;
  padding: 1.5em 0;
}

.menu-item {
  display: flex;
}

.menu-item-image {
  width: 80px;
  height: 80px;
  flex-shrink: 0;
  object-fit: cover;
  margin-right: 1.5em;
}

.menu-item-text {
  flex-grow: 1;
}

.menu-item-heading {
  display: flex;
  justify-content: space-between;
  margin: 0;
}

.menu-item-name {
  margin-right: 1.5em;
}

.menu-item-description {
  line-height: 1.6;
}

@media screen and (min-width: 992px) {
  .menu {
    font-size: 16px;
  }

  .menu-group {
    grid-template-columns: repeat(2, 1fr);
  }

  .menu-item-image {
    width: 125px;
    height: 125px;
  }
}

    </style>
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Restaurant Menu</title>
  <link rel="preconnect" href="https://fonts.gstatic.com">
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700&display=swap" rel="stylesheet">
</head>

<body>
  <div class="container">
    <div class="menu">
      <h2 class="menu-group-heading">
        Des Pâtes
      </h2>
      <div class="menu-group">
        <div class="menu-item">
          <img class="menu-item-image" src="images/rigatoni.png" alt="Rigatoni">
          <div class="menu-item-text">
            <h3 class="menu-item-heading">
              <span class="menu-item-name">Rigatoni</span>
              <span class="menu-item-price">$11</span>
            </h3>
            <p class="menu-item-description">
             Le Rigatoni est servi dans le pesto rouge. La sauce riche a des noix, fromages et ails.
            </p>
          </div>
        </div>
        <div class="menu-item">
          <img class="menu-item-image" src="images/linguini.png" alt="Bruschetta">
          <div class="menu-item-text">
            <h3 class="menu-item-heading">
              <span class="menu-item-name">Linguini</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
            <p class="menu-item-description">
              Nunc efficitur felis vel mi efficitur, sed molestie sem scelerisque. Fusce orci risus,
              congue eu mauris nec, pretium tincidunt nulla.
            </p>
          </div>
        </div>
                  <div class="menu-item">
          <img class="menu-item-image" src="images/penne.png" alt="Bruschetta">
          <div class="menu-item-text">
            <h3 class="menu-item-heading">
              <span class="menu-item-name">Penne</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
            <p class="menu-item-description">
              Nunc efficitur felis vel mi efficitur, sed molestie sem scelerisque. Fusce orci risus,
              congue eu mauris nec, pretium tincidunt nulla.
            </p>
          </div>
        </div>
        <div class="menu-item">
          <img class="menu-item-image" src="images/spaghetti.png" alt="Bruschetta">
          <div class="menu-item-text">
            <h3 class="menu-item-heading">
              <span class="menu-item-name">Spaghetti</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
            <p class="menu-item-description">
              Nunc efficitur felis vel mi efficitur, sed molestie sem scelerisque. Fusce orci risus,
              congue eu mauris nec, pretium tincidunt nulla.
            </p>
          </div>

        </div>
                <div class="menu-item">
          <img class="menu-item-image" src="images/tomato.png" alt="Bruschetta">
          <div class="menu-item-text">
            <h3 class="menu-item-heading">
              <span class="menu-item-name">Ravioli</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
            <p class="menu-item-description">
              Nunc efficitur felis vel mi efficitur, sed molestie sem scelerisque. Fusce orci risus,
              congue eu mauris nec, pretium tincidunt nulla.
            </p>
          </div>

        </div>
                <div class="menu-item">
          <img class="menu-item-image" src="images/gnocchi.png" alt="Bruschetta">
          <div class="menu-item-text">
            <h3 class="menu-item-heading">
              <span class="menu-item-name">Gnocchi</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
            <p class="menu-item-description">
              Nunc efficitur felis vel mi efficitur, sed molestie sem scelerisque. Fusce orci risus,
              congue eu mauris nec, pretium tincidunt nulla.
            </p>
          </div>

        </div>

      </div>
      <h2 class="menu-group-heading">
        Les Spécialités
      </h2>
      <div class="menu-group">
        <div class="menu-item">
          <img class="menu-item-image" src="images/homard.png" alt="Bruschetta">
          <div class="menu-item-text">
            <h3 class="menu-item-heading">
              <span class="menu-item-name">Homard</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
            <p class="menu-item-description">
              Nunc efficitur felis vel mi efficitur, sed molestie sem scelerisque. Fusce orci risus,
              congue eu mauris nec, pretium tincidunt nulla.
            </p>
          </div>
        </div>

        <div class="menu-item">
          <img class="menu-item-image" src="images/truffe.png" alt="Bruschetta">
          <div class="menu-item-text">
            <h3 class="menu-item-heading">
              <span class="menu-item-name">Truffes</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
            <p class="menu-item-description">
              Nunc efficitur felis vel mi efficitur, sed molestie sem scelerisque. Fusce orci risus,
              congue eu mauris nec, pretium tincidunt nulla.
            </p>
          </div>
        </div>
        <div class="menu-item">
          <img class="menu-item-image" src="images/foie.png" alt="Bruschetta">
          <div class="menu-item-text">
            <h3 class="menu-item-heading">
              <span class="menu-item-name">Foie Gras</span>
              <span class="menu-item-price">$12.90</span>
            </h3>
            <p class="menu-item-description">
              Nunc efficitur felis vel mi efficitur, sed molestie sem scelerisque. Fusce orci risus,
              congue eu mauris nec, pretium tincidunt nulla.
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</body>

</html>
</html>
