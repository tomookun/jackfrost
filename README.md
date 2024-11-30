/* General Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

/* Body and Background */
body {
  background: linear-gradient(to bottom, #2B2D42, #8ECBF4);
  color: #F0F8FF;
  line-height: 1.6;
}

/* Header */
header {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 20px;
  background: #2B2D42;
  color: #F0F8FF;
}

header .logo {
  font-size: 1.5rem;
  font-weight: bold;
}

header nav ul {
  list-style: none;
  display: flex;
}

header nav ul li {
  margin: 0 10px;
}

header nav ul li a {
  text-decoration: none;
  color: #F0F8FF;
  transition: color 0.3s ease;
}

header nav ul li a:hover {
  color: #8ECBF4;
}

/* Hero Section */
.hero {
  text-align: center;
  padding: 100px 20px;
  background: url('https://cdn.pixabay.com/photo/2016/11/19/14/00/ice-1838659_1280.jpg') no-repeat center center/cover;
  color: #F0F8FF;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 20px;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 30px;
}

.cta-buttons {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.cta-buttons .btn {
  padding: 10px 20px;
  border: none;
  background: #8ECBF4;
  color: #2B2D42;
  font-weight: bold;
  border-radius: 5px;
  text-decoration: none;
  transition: background 0.3s ease;
}

.cta-buttons .btn:hover {
  background: #F0F8FF;
}

.btn-secondary {
  background: transparent;
  border: 2px solid #8ECBF4;
  color: #8ECBF4;
}

.btn-secondary:hover {
  background: #8ECBF4;
  color: #2B2D42;
}

/* Features Section */
.features {
  text-align: center;
  padding: 50px 20px;
  background: #F0F8FF;
  color: #2B2D42;
}

.features h2 {
  font-size: 2rem;
  margin-bottom: 30px;
}

.feature-cards {
  display: flex;
  justify-content: center;
  gap: 20px;
}

.card {
  background: #8ECBF4;
  color: #2B2D42;
  padding: 20px;
  border-radius: 10px;
  width: 300px;
  box-shadow: 0 5px 10px rgba(0, 0, 0, 0.2);
  text-align: center;
}

.card h3 {
  margin-bottom: 10px;
}

/* Footer */
footer {
  text-align: center;
  padding: 20px;
  background: #2B2D42;
  color: #F0F8FF;
}

footer .social-links a {
  color: #F0F8FF;
  text-decoration: none;
  margin: 0 10px;
  transition: color 0.3s ease;
}

footer .social-links a:hover {
  color: #8ECBF4;
}
