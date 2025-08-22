/* === Reset básico === */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  line-height: 1.6;
  background: #fdfdfd;
  color: #333;
}

/* === Encabezado === */
header {
  background: #222;
  color: #fff;
  padding: 20px;
  position: sticky;
  top: 0;
  z-index: 1000;
}

header h1 {
  margin-bottom: 10px;
  text-align: center;
}

nav {
  display: flex;
  justify-content: center;
  gap: 20px;
  flex-wrap: wrap;
}

nav a {
  color: #fff;
  text-decoration: none;
  font-weight: 500;
  transition: color 0.3s ease;
}

nav a:hover {
  color: #ff9800;
}

/* === Secciones === */
section {
  padding: 60px 20px;
  text-align: center;
  max-width: 1000px;
  margin: auto;
}

section h2 {
  font-size: 2rem;
  margin-bottom: 20px;
  color: #222;
}

section p {
  font-size: 1.1rem;
  margin-bottom: 20px;
}

/* === Botones === */
.btn {
  display: inline-block;
  padding: 12px 24px;
  margin-top: 10px;
  background: #ff9800;
  color: #fff;
  border-radius: 6px;
  text-decoration: none;
  font-weight: bold;
  transition: background 0.3s ease;
}

.btn:hover {
  background: #e68900;
}

/* === Galería de portafolio === */
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
  margin-top: 30px;
}

.card {
  background: #fff;
  padding: 15px;
  border-radius: 8px;
  box-shadow: 0 2px 6px rgba(0,0,0,0.1);
  transition: transform 0.3s ease;
}

.card:hover {
  transform: translateY(-5px);
}

.card img {
  max-width: 100%;
  border-radius: 8px;
}

/* === Footer === */
footer {
  background: #222;
  color: #fff;
  text-align: center;
  padding: 20px;
  margin-top: 40px;
}
