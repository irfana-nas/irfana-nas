* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: "Arial", sans-serif;
  background-color: #fff;
}

/* Navbar Styles */
.navbar {
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #4e3db7;
  padding: 20px;
}

.nav-links {
  display: flex;
}

.nav-links li {
  margin-left: 20px;
}

.nav-links a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

.logo h1 {
  color: #fff;
}

.enroll-btn {
  background-color: #fff;
  color: #4e3db7;
  padding: 10px 20px;
  border-radius: 5px;
  font-weight: bold;
}

/* Hero Section */
.hero {
  display: flex;
  justify-content: space-between;
  align-items: center;
  padding: 50px;
  background-color: #7059d9;
  color: #fff;
  min-height: 90vh;
}

.hero-text h1 {
  font-size: 3rem;
  line-height: 1.3;
}

.hero-text p {
  font-size: 1.2rem;
  margin-top: 20px;
}

.hero-images {
  display: flex;
  gap: 15px;
}

.hero-images img {
  width: 200px;
  height: auto;
  border-radius: 10px;
}

.enroll-btn:hover {
  background-color: #f4f4f4;
}

/* Responsive Design */
@media (max-width: 768px) {
  .hero {
    flex-direction: column;
    text-align: center;
  }

  .hero-images {
    margin-top: 30px;
  }

  .hero-text h1 {
    font-size: 2rem;
  }

  .hero-text p {
    font-size: 1rem;
  }
}
/* Courses Features Section */
.courses-features {
  background-color: #fff;
  padding: 60px 20px;
  text-align: center;
}

.courses-features h2 {
  font-size: 2rem;
  margin-bottom: 10px;
  color: #4e3db7;
}

.courses-features p {
  margin-bottom: 40px;
  font-size: 1.1rem;
  color: #777;
}

/* Categories Tabs */
.course-tabs {
  display: flex;
  justify-content: center;
  margin-bottom: 30px;
}

.course-tabs .tab {
  background-color: #eee;
  border: none;
  padding: 10px 20px;
  margin: 0 5px;
  border-radius: 20px;
  cursor: pointer;
}

.course-tabs .tab.active,
.course-tabs .tab:hover {
  background-color: #4e3db7;
  color: #fff;
}

/* Courses Grid */
.courses-grid {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
}

.course-card {
  background-color: #f4f4f4;
  border-radius: 10px;
  width: 30%;
  margin-bottom: 30px;
  overflow: hidden;
  transition: transform 0.3s ease;
}

.course-card:hover {
  transform: scale(1.05);
}

.course-card img {
  width: 100%;
  height: 180px;
  object-fit: cover;
}

.course-info {
  padding: 20px;
}

.course-reviews {
  margin-bottom: 10px;
}

.course-reviews span {
  font-size: 1rem;
  color: #ffb100;
}

.course-info h3 {
  font-size: 1.5rem;
  margin-bottom: 10px;
  color: #333;
}

.course-info p {
  margin-bottom: 5px;
  color: #777;
}

.course-info .instructor {
  font-weight: bold;
}

.course-info .price {
  color: #4e3db7;
  font-size: 1.2rem;
  font-weight: bold;
  margin: 10px 0;
}

.enroll-btn {
  background-color: #4e3db7;
  color: #fff;
  padding: 10px 20px;
  border-radius: 5px;
  text-decoration: none;
}

.enroll-btn:hover {
  background-color: #3a2c9d;
}

/* Pagination */
.pagination {
  margin-top: 30px;
}

.pagination span {
  font-size: 1.5rem;
  color: #bbb;
  margin: 0 5px;
  cursor: pointer;
}

.pagination span:hover {
  color: #4e3db7;
}

/* Responsive Design */
@media (max-width: 768px) {
  .course-card {
    width: 45%;
  }
}

@media (max-width: 480px) {
  .course-card {
    width: 100%;
  }
}
/* Statistics Section */
.statistics-section {
  background-color: #e0f4ff;
  padding: 50px 0;
}

.stats-container {
  display: flex;
  justify-content: space-around;
  text-align: center;
}

.stat-box h2 {
  font-size: 2.5rem;
  color: #4e3db7;
}

.stat-box p {
  margin-top: 10px;
  font-size: 1.1rem;
  color: #777;
}

/* Mentors Section */
.mentors-section {
  background-color: #fff;
  padding: 60px 20px;
  text-align: center;
}

.mentors-section h2 {
  font-size: 2rem;
  margin-bottom: 40px;
  color: #4e3db7;
}

.mentors-grid {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.mentor-card {
  background-color: #f4f4f4;
  border-radius: 10px;
  width: 22%;
  text-align: center;
  padding: 20px;
  margin-bottom: 30px;
  transition: transform 0.3s ease;
}

.mentor-card:hover {
  transform: translateY(-10px);
}

.mentor-card img {
  width: 100px;
  height: 100px;
  border-radius: 50%;
  object-fit: cover;
  margin-bottom: 20px;
}

.mentor-card h3 {
  font-size: 1.5rem;
  color: #333;
  margin-bottom: 10px;
}

.mentor-card p {
  color: #777;
}

/* Responsive Design */
@media (max-width: 768px) {
  .stat-box h2 {
    font-size: 2rem;
  }
  
  .mentor-card {
    width: 45%;
  }
}

@media (max-width: 480px) {
  .mentor-card {
    width: 100%;
  }
}
/* Students Reviews Section */
.students-reviews-section {
  background-color: #4e3db7;
  color: #fff;
  padding: 60px 20px;
  text-align: center;
}

.students-reviews-section h2 {
  font-size: 2rem;
  margin-bottom: 40px;
}

.reviews-grid {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.review-card {
  background-color: #fff;
  color: #333;
  width: 30%;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  text-align: center;
  margin-bottom: 30px;
}

.review-card img {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  margin-bottom: 20px;
}

.review-card h3 {
  font-size: 1.5rem;
  margin-bottom: 10px;
}

.review-card .role {
  color: #4e3db7;
  margin-bottom: 20px;
}

.review-card .review {
  font-size: 1rem;
  color: #666;
}

/* Latest Post from Blog Section */
.latest-post-section {
  background-color: #f7f7f7;
  padding: 60px 20px;
}

.blog-header h2 {
  font-size: 2rem;
  margin-bottom: 10px;
  text-align: left;
}

.blog-header p {
  font-size: 1.1rem;
  margin-bottom: 40px;
  text-align: left;
  color: #666;
}

.blog-grid {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
}

.blog-card {
  background-color: #fff;
  width: 45%;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
  overflow: hidden;
  margin-bottom: 30px;
}

.blog-card img {
  width: 100%;
  height: 200px;
  object-fit: cover;
}

.blog-card h3 {
  font-size: 1.5rem;
  padding: 20px;
}

.blog-card .post-summary {
  font-size: 1rem;
  color: #666;
  padding: 0 20px 20px 20px;
}

/* Responsive Design */
@media (max-width: 768px) {
  .review-card {
    width: 45%;
  }

  .blog-card {
    width: 100%;
  }
}

@media (max-width: 480px) {
  .review-card {
    width: 100%;
  }

  .blog-card {
    width: 100%;
  }

  .blog-header h2, .blog-header p {
    text-align: center;
  }
}
/* Reset CSS */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Body and Font Settings */
body {
    font-family: 'Arial', sans-serif;
    background-color: #f4f4f4;
}

/* Header Styling */
header {
    background-color: #3A3A3C;
    color: white;
    padding: 10px 0;
}

.header-container {
    display: flex;
    justify-content: space-between;
    align-items: center;
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 20px;
}

.logo h1 {
    font-size: 24px;
    font-weight: bold;
}

.navbar ul {
    list-style: none;
    display: flex;
}

.navbar ul li {
    margin: 0 15px;
}

.navbar ul li a {
    color: white;
    text-decoration: none;
    font-size: 16px;
}

.navbar ul li a:hover {
    text-decoration: underline;
}

/* Newsletter Section */
.newsletter {
    background-color: #4C5CE0;
    color: white;
    text-align: center;
    padding: 40px 20px;
}

.newsletter h2 {
    font-size: 28px;
    margin-bottom: 10px;
}

.newsletter p {
    font-size: 16px;
    margin-bottom: 20px;
}

.newsletter form {
    display: inline-block;
}

.newsletter input[type="email"] {
    padding: 10px;
    width: 250px;
    border: none;
    border-radius: 5px;
    margin-right: 10px;
}

.newsletter button {
    padding: 10px 20px;
    background-color: #fff;
    color: #4C5CE0;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

.newsletter button:hover {
    background-color: #3A3A3C;
    color: white;
}

/* Responsive Styles */
@media (max-width: 768px) {
    .header-container {
        flex-direction: column;
        text-align: center;
    }

    .navbar ul {
        flex-direction: column;
        margin-top: 10px;
    }

    .navbar ul li {
        margin: 10px 0;
    }

    .newsletter input[type="email"] {
        width: 100%;
        margin-bottom: 10px;
    }
}
