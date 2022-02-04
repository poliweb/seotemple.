<template>
  <div>
    <div
      class="container mx-auto flex justify-between p-5 flex-row items-center"
    >
      <NuxtLink to="/">
        <Logo class="logo" />
      </NuxtLink>

      <div class="">
        <nav
          class="md:ml-auto md:mr-auto hidden md:flex flex-wrap items-center text-base justify-center"
        >
          <!-- Список верхнего меню сайта -->
          <NuxtLink
            v-for="menuLink in menuLinks"
            :key="menuLink.index"
            :to="menuLink.to"
            class="nav-link mr-5 transition duration-700 ease-in-out"
            >{{ menuLink.title }}</NuxtLink
          >
        </nav>
      </div>
      <div class="">
        <SocIcons/>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: function () {
    return {
      menuLinks: [
        {
          title: "Home",
          to: "/",
        },
        {
          title: "Products",
          to: "/products",
        },
        {
          title: "About",
          to: "/about",
        },
        {
          title: "Portfolio",
          to: "/portfolio",
        },
        {
          title: "Contact",
          to: "/contact",
        },
      ],
    };
  },
};
</script>

<style>
.logo {
  width: 152px;
  height: 30px;
}

/* Настройка тега А в меню */
a.nav-link {
  color: dimgrey !important;
  text-decoration: none;
  position: relative;
  font-family: Montserrat;
  font-size: 18px;
}
/* Тег А в активном састояние класс nuxt-link-exact-active */
a.nuxt-link-exact-active.nav-link {
  color: #2c97dd !important;
}
a.nuxt-link-exact-active.nav-link:after {
  left: 0;
  width: 100%;
  position: relative;
}
/* Настройка поведения Тег А при состояние псевдокласса :hover */
a.nav-link:hover {
  color: #2c97dd !important;
}
a.nav-link:after {
  bottom: 0;
  content: "";
  display: block;
  height: 2px;
  left: 50%;
  position: absolute;
  background: #2c97dd;
  transition: width 0.4s ease 0s, left 0.4s ease 0s;
  width: 0;
}
a.nav-link:hover:after {
  width: 100%;
  left: 0;
}
</style>
