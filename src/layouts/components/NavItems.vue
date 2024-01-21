<script setup>
import VerticalNavSectionTitle from '@/@layouts/components/VerticalNavSectionTitle.vue'
import VerticalNavGroup from '@layouts/components/VerticalNavGroup.vue'
import VerticalNavLink from '@layouts/components/VerticalNavLink.vue'
</script>

<template>
  <!-- 👉 Dashboards -->
  <VerticalNavGroup
    :item="{
      title: 'Dashboards',
      badgeContent: 1,
      badgeClass: 'bg-primary',
      icon: 'ri-home-smile-line',
    }"
  >
    <VerticalNavLink
      :item="{
        title: 'Analytics',
        to: '/dashboard',
      }"
    />
  </VerticalNavGroup>

  <!-- 👉 Front Pages -->
  <VerticalNavGroup
    :item="{
      title: 'Front Pages',
      icon: 'ri-file-copy-line',
      badgeContent: 'Pro',
      badgeClass: 'bg-light-primary text-primary',
    }"
  >
    <VerticalNavLink
      :item="{
        title: 'Landing',
        href: 'https://demos.themeselection.com/materio-vuetify-vuejs-admin-template/demo-1/front-pages/landing-page',
        target: '_blank',
      }"
    />
    <VerticalNavLink
      :item="{
        title: 'Pricing',
        href: 'https://demos.themeselection.com/materio-vuetify-vuejs-admin-template/demo-1/front-pages/pricing',
        target: '_blank',
      }"
    />
    <VerticalNavLink
      :item="{
        title: 'Payment',
        href: 'https://demos.themeselection.com/materio-vuetify-vuejs-admin-template/demo-1/front-pages/payment',
        target: '_blank',
      }"
    />
    <VerticalNavLink
      :item="{
        title: 'Checkout',
        href: 'https://demos.themeselection.com/materio-vuetify-vuejs-admin-template/demo-1/front-pages/checkout',
        target: '_blank',
      }"
    />
    <VerticalNavLink
      :item="{
        title: 'Help Center',
        href: 'https://demos.themeselection.com/materio-vuetify-vuejs-admin-template/demo-1/front-pages/help-center',
        target: '_blank',
      }"
    />
  </VerticalNavGroup>

  <!-- 👉 Comissão de Serviço -->
  <VerticalNavSectionTitle
    :item="{
      heading: 'Comissão de Serviço',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Account Settings',
      icon: 'ri-user-settings-line',
      to: '/account-settings',
    }"
  />


  <!-- 👉 Apps & Pages -->
  <VerticalNavSectionTitle
    :item="{
      heading: 'Apps & Pages',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Account Settings',
      icon: 'ri-user-settings-line',
      to: '/account-settings',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Login',
      icon: 'ri-login-box-line',
      to: '/login',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Register',
      icon: 'ri-user-add-line',
      to: '/register',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Error',
      icon: 'ri-information-line',
      to: '/no-existence',
    }"
  />

  <!-- 👉 User Interface -->
  <VerticalNavSectionTitle
    :item="{
      heading: 'User Interface',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Typography',
      icon: 'ri-text',
      to: '/typography',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Icons',
      icon: 'ri-remixicon-line',
      to: '/icons',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Cards',
      icon: 'ri-bar-chart-box-line',
      to: '/cards',
    }"
  />

  <!-- 👉 Forms & Tables -->
  <VerticalNavSectionTitle
    :item="{
      heading: 'Forms & Tables',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Form Layouts',
      icon: 'ri-layout-4-line',
      to: '/form-layouts',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Tables',
      icon: 'ri-table-alt-line',
      to: '/tables',
    }"
  />

  <!-- 👉 Others -->
  <VerticalNavSectionTitle
    :item="{
      heading: 'Links Úteis',
    }"
  />
  <!-- <VerticalNavLink
    :item="{
      title: 'Access Control',
      icon: 'ri-shield-line',
      href: 'https://demos.themeselection.com/materio-vuetify-vuejs-admin-template/demo-1/access-control',
      target: '_blank',
      badgeContent: 'Pro',
      badgeClass: 'bg-light-primary text-primary',
    }"
  /> -->
  <VerticalNavLink
    :item="{
      title: 'Documentation',
      icon: 'ri-article-line',
      href: 'https://demos.themeselection.com/materio-vuetify-vuejs-admin-template/documentation/',
      target: '_blank',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Quadro de Anúncios',
      href: 'https://sites.google.com/view/cong-paraiso',
      icon: 'ri-dashboard-line',
      target: '_blank',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Enviar Relatório',
      href: 'https://docs.google.com/forms/d/e/1FAIpQLSeLQw2g8sQEjWduGodv0xVCAs1h9JOBJX8gnTKLQelrEgH6WA/viewform',
      icon: 'ri-draft-line',
      target: '_blank',
    }"
  />
  <VerticalNavLink
    :item="{
      title: 'Enviar Donativo',
      href: 'https://donate.jw.org/ui/T/donate-home.html#/donate',
      icon: 'ri-secure-payment-line',
      target: '_blank',
    }"
  />
</template>
