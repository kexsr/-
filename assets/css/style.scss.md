---
---

@import "{{ site.theme }}";

// Стили для боковой панели
.wrapper {
  display: flex;
  flex-wrap: wrap;
}

.sidebar {
  width: 25%;
  padding: 1rem;
  
  @media screen and (max-width: 800px) {
    width: 100%;
  }
}

.content {
  width: 75%;
  padding: 1rem;
  
  @media screen and (max-width: 800px) {
    width: 100%;
  }
}

.sidebar-nav {
  display: flex;
  flex-direction: column;
}

.sidebar-link {
  display: block;
  padding: 10px 15px;
  margin-bottom: 5px;
  background-color: #f0f0f0;
  border-radius: 4px;
  text-decoration: none;
  color: #333;
  
  &:hover {
    background-color: #e0e0e0;
  }
}

// Стили для логотипа
.logo {
  height: 40px;
  vertical-align: middle;
  margin-right: 10px;
}

// Фиксированный футер
.site-footer {
  position: fixed;
  bottom: 0;
  width: 100%;
  background-color: #f8f8f8;
}