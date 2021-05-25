<template>
  <header class="tech-header header">
    <div class="container-fluid">
      <nav
        class="navbar navbar-toggleable-md navbar-inverse fixed-top bg-inverse"
      >
        <button
          class="navbar-toggler navbar-toggler-right"
          type="button"
          data-toggle="collapse"
          data-target="#navbarCollapse"
          aria-controls="navbarCollapse"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <a class="navbar-brand" href="tech-index.html"
          ><img src="images/version/tech-logo.png" alt=""
        /></a>
        <div class="ml-5 collapse navbar-collapse" id="navbarCollapse">
          <ul class="navbar-nav mr-auto">
            <li class="nav-item">
              <router-link to="/" class="nav-link">Home</router-link>
            </li>
            <li
              class="nav-item dropdown has-submenu menu-large hidden-md-down hidden-sm-down hidden-xs-down"
            >
              <a
                class="nav-link dropdown-toggle"
                href="#"
                id="dropdown01"
                data-toggle="dropdown"
                aria-haspopup="true"
                aria-expanded="false"
                >Categories</a
              >
              <ul class="dropdown-menu megamenu" aria-labelledby="dropdown01">
                <li>
                  <div class="container">
                    <div class="tab">
                      <button
                        class="tablinks active"
                        onclick="openCategory(event, 'cat01')"
                      >
                        Web Development
                      </button>
                      <button
                        class="tablinks"
                        onclick="openCategory(event, 'cat02')"
                      >
                        Python
                      </button>
                      <button
                        class="tablinks"
                        onclick="openCategory(event, 'cat03')"
                      >
                        Django
                      </button>
                      <button
                        class="tablinks"
                        onclick="openCategory(event, 'cat04')"
                      >
                        Vue.js
                      </button>
                      <button
                        class="tablinks"
                        onclick="openCategory(event, 'cat05')"
                      >
                        Node.js
                      </button>
                    </div>
                  </div>
                </li>
              </ul>
            </li>

            <li class="nav-item">
              <router-link to="/contact" class="nav-link"
                >Contact Us</router-link
              >
            </li>
          </ul>
          <div>
            <form class="d-flex">
              <input
                class="form-control me-2"
                type="search"
                placeholder="Search"
                aria-label="Search"
              />
              <button class="btn btn-outline-success" type="submit">
                Search
              </button>
            </form>
          </div>
        </div>
      </nav>
    </div>
    <!-- end container-fluid -->
  </header>
  <!-- end market-header -->
</template>
<script>
export default {
  name: "headerlayout",
};
</script>
